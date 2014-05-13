# Contents and Usage

The contents of this package are explained here. This project structure is compatible with [CMMI Maturity Level 2 v1.3](CMMI.md) or [PMBOK Guide Fifth Edition](PMBOK.md) standards based on the [Unified Process](UP.md) for Software Development. 

## Folder Structure

The folder structure is divided and organized by content and not by process steps. There are 9 First Level folders which contain all work products or project related files. It's contents are explained as follows (ordered by name):

* **Architecture:** Contains all the project's architecture/workflow files (UML, models, classes, prototypes, workflow definitions, ...).
* **Deliverables:** Contains all the project's deliverables (compiled releases of source code, packages, manuals, documentation, assets, ...).
* **Development:** Contains all the project's development files (source code, developed assets, components used, database models and scripts, ...).
* **Maintenance:** Contains all the project's maintenance cycle files.
* **Management:** Contains all the project's files related to the project's management (business analysis, configuration management, monitoring, policies, requirements, ...).
* **Precedents:** Contains all the files obtained from the client related to the project (the project's request format, assets, documents, files, ...).
* **References:** Contains all the reference materials for the project (links, publications, white papers, technical reports, specs, ...).
* **Templates:** Contains all the templates that should be used to generate the required project documentation.
* **tmp:** This is a temporary folder for any purpose.

The whole folder structure is explained in detail in the [STRUCTURE.md](STRUCTURE.md) file which contains all subfolders explanation.

## Templates

The templates are not organized by folder as this facilitates searching for a specific template. Instead they have a self-explanatory name which includes the path to be used by the generated document. Every directory in the filename is separated by an underscore \_ whereas the last group is the document's generic name (it's purpose is also self-explanatory).

Example:

	Filename: Management_BusinessAnalysis_BusinessCases_ProjectRoiEvaluation.dotx
	
	Folder: Management/BusinessAnalysis/BusinessCases/
	Filename: <prefix>_ProjectRoiEvaluation_<suffix>.docx

The `<prefix>` y `<suffix>` are explained in the [Naming Conventions](#naming-conventions) section.

## Naming Conventions

The suggested naming conventions to be used for filenames are as follows:

* The filenames should use the [Pascal Case Notation (or Upper Camel Case Notation)](http://en.wikipedia.org/wiki/CamelCase) which capitalizes the first character of each word (including acronyms over two letters in length). For words (or acronyms) that consist of two or fewer letters the Upper Case Notation should be used (all letters are capitalized).

Examples:

	ProjectRoiEvaluation
	Usability
	QualityControl
	HWRequirements

* No special characters should be used in the names. All characters should be changed for their non-special character equivalent.

Examples:

	Evaluación ---> Evaluacion
	Tamaño ---> Tamano

Most common special characters conversions:

	[Á, Ä], [á, ä] ---> [A], [a]
	[É, Ë], [é, ë] ---> [E], [e]
	[Í, Ï], [í, ï] ---> [I], [i]
	[Ó, Ö], [ó, ö] ---> [O], [o]
	[Ú, Ü], [ú, ü] ---> [U], [u]
	[Ñ], [ñ] ---> [N], [n] 