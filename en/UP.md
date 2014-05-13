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

Inception is the smallest phase in the project and ideally it should be quite short. If the Inception Phase is long then it may be an indication of excessive up-front specification, which is contrary to the spirit of the Unified Process.

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