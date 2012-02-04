# CMMI Nivel de Madurez 2

Esta estructura del directorio de proyecto está basada en el [Reporte Técnico CMMI-DEV v1.3](http://www.sei.cmu.edu/library/abstracts/reports/10tr033.cfm) publicado en Noviembre de 2010 por el [Instituto de Ingeniería de Software](http://www.sei.cmu.edu) de la universidad [Carnegie Mellon University](http://www.cmu.edu).

## Áreas de Proceso

La especificación CMMI-DEV describe 7 Áreas de Proceso (PA por sus siglas en inglés) que comprenden el nivel de madurez 2 (N2). Las PAs que son cubiertas por esta estructura de directorio y plantillas son (por orden alfabético en inglés):

* Administración de la Configuración (CM)
* Medición y Análisis (MA)
* Monitoreo y Control del Proyecto (PMC)
* Planeación de Proyecto (PP)
* Aseguramiento de la Calidad del Proceso y el Producto (PPQA)
* Administración de Requerimientos (REQM)
* Administración de Acuerdos con Proveedores (SAM)

Las PAs serán descritas en breve. Esta información ha sido tomada tal cual de la [Referencia Rápida de CMMI-DEV v1.3](http://www.sei.cmu.edu/cmmi/tools/cmmiv1-3/upload/CMMI-DEV_Quick_Ref.pdf) y traducida lo mejor posible para mantener su esencia.

### Metas y Prácticas

Existen dos categorías de Metas y Prácticas: Genéricas y Específicas. Las Metas Específicas (SG) y Prácticas Específicas (SP) son específicas a un Área de Proceso. Las Metas Genéricas (GG) y Prácticas Genéricas (GP) son parte de cada una de las PAs. Se cumple con un Área de Proceso cuando los procesos organizacionales cubren todas las Metas y Prácticas Genéricas y Específicas para esa PA.

#### Metas y Prácticas Genéricas

Las Metas y Prácticas Genéricas son parte de cada Área de Proceso.

* GG 1 - Lograr las Metas Específicas
	* GP 1.1 - Realizar las Prácticas Específicas
* GG 2 - Institucionalizar un Proceso Administrado
	* GP 2.1 - Establecer una Política Organizacional
	* GP 2.2 - Planificar el Proceso
	* GP 2.3 - Proveer los Recursos
	* GP 2.4 - Asignar las Responsabilidades
	* GP 2.5 - Capacitar al Personal
	* GP 2.6 - Controlar los Productos del Trabajo
	* GP 2.7 - Identificar e Involucrar a los Interesados (_stakeholders_) Relevantes
	* GP 2.8 - Monitorear y Controlar el Proceso
	* GP 2.9 - Evaluar Objetivamente la Adherencia
	* GP 2.10 - Revisar el Estatus con la Gerencia de un Nivel más Elevado
* GG 3 - Institucionalizar un Proceso Definido
	* GP 3.1 - Establecer un Proceso Definido
	* GP 3.2 - Recolectar Experiencias Relativas al Proceso

#### Metas y Prácticas Específicas

Cada Área de Proceso es definida por un conjunto de Metas y Prácticas Específicas. Estas Metas y Prácticas aparecen solamente en esa PA.

### Administración de la Configuración (CM)

El propósito de la Administración de la Configuración es establecer y mantener la integridad de los productos del trabajo utilizando identificación de la configuración, control de la configuración, seguimiento del estatus de la configuración y auditorías de configuración.

#### SG 1 - Se establecen Líneas Base de los productos de trabajo identificados.

* SP 1.1 - Identificar los elementos y los componentes de la configuracón, así como los productos del trabajo relacionados para ser incluidos dentro de la administración de la configuración.
* SP 1.2 - Establecer y mantener un sistema de administración de la configuración y administración de los cambios para controlar los productos del trabajo.
* SP 1.3 - Crear o publicar líneas base para uso interno y entrega al cliente.

#### SG 2 - Los cambios a los productos del trabajo bajo la administración de la configuración son registrados y controlados.

* SP 2.1 - Registrar las peticiones de cambio para los elementos de la configuración.
* SP 2.2 - Controlar los cambios a los elementos de la configuración.

#### SG 3 - La integridad de las líneas base es establecida y mantenida.

* SP 3.1 - Establecer y mantener registros que describan los elementos de la configuración.
* SP 3.2 - Realizar auditorías de configuración para mantener la integridad de las líneas base de la configuración.

### Measurement and Analysis (MA)

The purpose of Measurement and Analysis (MA) is to develop and sustain a measurement capability used to support management information needs.

#### SG 1 - Measurement objectives and activities are aligned with identified information needs and objectives.

* SP 1.1 - Establish and maintain measurement objectives derived from identified information needs and objectives.
* SP 1.2 - Specify measures to address measurement objectives.
* SP 1.3 - Specify how measurement data are obtained and stored.
* SP 1.4 - Specify how measurement data are analyzed and communicated.

#### SG 2 - Measurement results, which address identified information needs and objectives, are provided.

* SP 2.1 - Obtain specified measurement data.
* SP 2.2 - Analyze and interpret measurement data.
* SP 2.3 - Manage and store measurement data, measurement specifications, and analysis results.
* SP 2.4 - Communicate results of measurement and analysis activities to all relevant stakeholders.

### Project Monitoring and Control (PMC)

The purpose of Project Monitoring and Control (PMC) is to provide an understanding of the project’s progress so that appropriate corrective actions can be taken when the project’s performance deviates significantly from the plan.

#### SG 1 - Actual project performance and progress are monitored against the project plan.

* SP 1.1 - Monitor actual values of project planning parameters against the project plan.
* SP 1.2 - Monitor commitments against those identified in the project plan.
* SP 1.3 - Monitor risks against those risks identified in the project plan.
* SP 1.4 - Monitor the management of project data against the project plan.
* SP 1.5 - Monitor stakeholder involvement against the project plan.
* SP 1.6 - Periodically review the project’s progress, performance, and issues.
* SP 1.7 - Review the project’s accomplishments and results at selected project milestones.

#### SG 2 - Corrective actions are managed to closure when the project’s performance or results deviate significantly from the plan.

* SP 2.1 - Collect and analyze issues and determine corrective actions to address them.
* SP 2.2 - Take corrective action on identified issues.
* SP 2.3 - Manage corrective actions to closure.

### Project Planning (PP)

The purpose of Project Planning (PP) is to establish and maintain plans that define project activities.

#### SG 1 - Estimates of project planning parameters are established and maintained.

* SP 1.1 - Establish a top-level work breakdown structure (WBS) to estimate the scope of the project.
* SP 1.2 - Establish and maintain estimates of work product and task attributes.
* SP 1.3 - Define project lifecycle phases on which to scope the planning effort.
* SP 1.4 - Estimate the project’s effort and cost for work products and tasks based on estimation rationale.

#### SG 2 - A project plan is established and maintained as the basis for managing the project.

* SP 2.1 - Establish and maintain the project’s budget and schedule.
* SP 2.2 - Identify and analyze project risks.
* SP 2.3 - Plan for the management of project data.
* SP 2.4 - Plan for resources to perform the project.
* SP 2.5 - Plan for knowledge and skills needed to perform the project.
* SP 2.6 - Plan the involvement of identified stakeholders.
* SP 2.7 - Establish and maintain the overall project plan.

#### SG 3 - Commitments to the project plan are established and maintained.

* SP 3.1 - Review all plans that affect the project to understand project commitments.
* SP 3.2 - Adjust the project plan to reconcile available and estimated resources.
* SP 3.3 - Obtain commitment from relevant stakeholders responsible for performing and supporting plan execution.

### Process and Product Quality Assurance (PPQA)

The purpose of Process and Product Quality Assurance (PPQA) is to provide staff and management with objective insight into processes and associated work products.

#### SG 1 - Adherence of the performed process and associated work products to applicable process descriptions, standards, and procedures is objectively evaluated.

* SP 1.1 - Objectively evaluate selected performed processes against applicable process descriptions, standards, and procedures.
* SP 1.2 - Objectively evaluate selected work products against applicable process descriptions, standards, and procedures.

#### SG 2 - Noncompliance issues are objectively tracked and communicated, and resolution is ensured.

* SP 2.1 - Communicate quality issues and ensure the resolution of noncompliance issues with the staff and managers.
* SP 2.2 - Establish and maintain records of quality assurance activities.

### Requirements Management (REQM)

The purpose of Requirements Management (REQM) is to manage requirements of the project’s products and product components and to ensure alignment between those requirements and the project’s plans and work products.

#### SG 1 - Requirements are managed and inconsistencies with plans and work products are identified.

* SP 1.1 - Develop an understanding with the requirements providers on the meaning of the requirements.
* SP 1.2 - Obtain commitment to requirements from project participants.
* SP 1.3 - Manage changes to requirements as they evolve during the project.
* SP 1.4 - Maintain bidirectional traceability among requirements and work products.
* SP 1.5 - Ensure that project plans and work products remain aligned with the requirements.

### Supplier Agreement Managemnt (SAM)

The purpose of Supplier Agreement Management (SAM) is to manage the acquisition of products and services from suppliers.

#### SG 1 - Agreements with the suppliers are established and maintained.

* SP 1.1 - Determine the type of acquisition for each product or product component to be acquired.
* SP 1.2 - Select suppliers based on an evaluation of their ability to meet the specified requirements and established criteria.
* SP 1.3 - Establish and maintain supplier agreements.

#### SG 2 - Agreements with suppliers are satisfied by both the project and the supplier.

* SP 2.1 - Perform activities with the supplier as specified in the supplier agreement.
* SP 2.2 - Ensure that the supplier agreement is satisfied before accepting the acquired product.
* SP 2.3 - Ensure the transition of products acquired from the supplier.

# Unified Process

This folder structure is based on the software development process framework [Unified Process](http://en.wikipedia.org/wiki/Unified_Process) which defines the development as a use case driven, architecture centric process using an iterative and incremental live cycle.

## Project Lifecycle

The Unified Process divides the project into four phases:

* Inception
* Elaboration
* Construction
* Transition

Each of them can have one or multiple iteration throughout the process, though [the relative effort and emphasis will change over the course of the project](http://en.wikipedia.org/wiki/File:Development-iterative.gif).

### Inception Phase

Inception is the smallest phase in the project, and ideally it should be quite short. If the Inception Phase is long then it may be an indication of excessive up-front specification, which is contrary to the spirit of the Unified Process.

The following are typical goals for the Inception phase.

* Establish a justification or business case for the project
* Establish the project scope and boundary conditions
* Outline the use cases and key requirements that will drive the design tradeoffs
* Outline one or more candidate architectures
* Identify risks
* Prepare a preliminary project schedule and cost estimate

The Lifecycle Objective Milestone marks the end of the Inception phase.

Develop an approximate vision of the system, make the business case, define the scope, and produce rough estimate for cost and schedule.

### Elaboration Phase

During the Elaboration phase the project team is expected to capture a healthy majority of the system requirements. However, the primary goals of Elaboration are to address known risk factors and to establish and validate the system architecture. Common processes undertaken in this phase include the creation of use case diagrams, conceptual diagrams (class diagrams with only basic notation) and package diagrams (architectural diagrams).

The architecture is validated primarily through the implementation of an Executable Architecture Baseline. This is a partial implementation of the system which includes the core, most architecturally significant, components. It is built in a series of small, timeboxed iterations. By the end of the Elaboration phase the system architecture must have stabilized and the executable architecture baseline must demonstrate that the architecture will support the key system functionality and exhibit the right behavior in terms of performance, scalability and cost.

The final Elaboration phase deliverable is a plan (including cost and schedule estimates) for the Construction phase. At this point the plan should be accurate and credible, since it should be based on the Elaboration phase experience and since significant risk factors should have been addressed during the Elaboration phase.

### Construction Phase

Construction is the largest phase in the project. In this phase the remainder of the system is built on the foundation laid in Elaboration. System features are implemented in a series of short, timeboxed iterations. Each iteration results in an executable release of the software. It is customary to write full text use cases during the construction phase and each one becomes the start of a new iteration. Common UML (Unified Modelling Language) diagrams used during this phase include Activity, Sequence, Collaboration, State (Transition) and Interaction Overview diagrams.

### Transition Phase

The final project phase is Transition. In this phase the system is deployed to the target users. Feedback received from an initial release (or initial releases) may result in further refinements to be incorporated over the course of several Transition phase iterations. The Transition phase also includes system conversions and user training.

## More Information

For more information please visit [Unified Process](http://en.wikipedia.org/wiki/Unified_Process). There are also many refinements of the Unified Process that can be found [here](http://en.wikipedia.org/wiki/Unified_Process#Refinements_and_Variations).

# Contents & Usage

The contents of this package are explained here.

## Folder Structure

The folder structure is divided and organized by content and not by process steps. There are 9 First Level folders which contain all generated or related files for the project, it's contents are explained as follows:

* **Architecture:** Contains all the project's architecture files (UML, models, classes, prototipes, ... ).
* **Development:** Contains all the project's development files (source code).
* **Deliverables:** Contains all the project's deliverables (including compiled releases of source code).
* **Maintenance:** Contains all the project's maintenance cycle files.
* **Management:** Contains all the project's files related to the project's management.
* **Policies:** Contains all the policies that should be observed by the whole process of the project.
* **Precedents:** Contains all the files obtained from the client related to the project (including the project's request format).
* **References:** Contains all the reference materials for the project (links, publications, white papers, technical reports, specs, ... ).
* **Templates:** Contains all the templates to be used by the documents/files/diagrams of the project.

## Templates

The templates are not organized by folder as this facilitate the searching for a specific template. But they instead have a name that explains where the document should be placed inside the folder structure.