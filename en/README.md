# Contents and Usage

The contents of this package are explained here. This project structure is compatible with [CMMI-DEV v1.3 Maturity Level 2 (L2)](CMMI.md) or [PMBOK Guide Fifth Edition](PMBOK.md) standards based on the use of the [Unified Process](UP.md) for Software Development.

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

## Naming Conventions

The suggested naming conventions to be used for filenames are as follows:

1. The filenames should follow a pre-defined form explained below. This pattern should be defined on a project basis and used across all filenames inside it.

	Pattern:
	
		(<prefix>_)<name>(_<suffix>)(.<extension>)
	
	Tag explanation:
	
	* _(Optional)_ `<prefix>`: Is a pre-name string. This is usually set to the code of the project. This can also be set to the file creation date.
	* _(Required)_ `<name>`: This part of the pattern is the significative and descriptive filename that summarizes the content of the file.
	* _(Optional)_ `<suffix>`: Is a post-name string. This is usually set to the version of the document to track changes (when no [VCS](http://en.wikipedia.org/wiki/Revision_control) is being used). This can also be set to the file creation date.
	* _(Optional)_ `<extension>`: Is the file extension when appropriate.
	
	**Important:** The `_` _(underscore)_ character should not be used inside any of the tags, it is meant as a separator between the pattern parts and should only be included when a prefix and/or suffix are present.

2. In general, the file name should use the [Pascal Case Notation (or Upper Camel Case Notation)](http://en.wikipedia.org/wiki/CamelCase) which capitalizes the first character of each word (including acronyms over two letters in length). For words (or acronyms) that consist of two or fewer letters the Upper Case Notation should be used (all letters are capitalized).

	Examples:
	
		ProjectRoiEvaluation
		Usability
		QualityControl
		HWRequirements

3. No special characters should be used in the names. All characters should be changed for their non-special character equivalent.

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

4. The file versioning scheme should follow the concepts behind the rules set forth in the [Semanting Versioning Specification v2.0.0](http://semver.org/spec/v2.0.0.html).

## Templates

The templates are not organized by folder as this facilitates searching for a specific template. Instead they have a self-explanatory name which includes the path to be used by the generated document. Every directory in the filename is separated by an underscore `_` whereas the last group is the document's generic name (it's purpose is also self-explanatory).

A document based on the template:

	Management_BusinessAnalysis_BusinessCases_ProjectRoiEvaluation.dotx

should be saved in:

	Management/BusinessAnalysis/BusinessCases/

with filename:

	MYPROJ_ProjectRoiEvaluation_v1.0.docx

The `<prefix>`, `<suffix>` and `<extension>` parts used in this example are `MYPROJ`, `v1.0` and `docx` respectively.

