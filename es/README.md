# Contenido y Uso

Esta estructura de proyecto es compatible con los estándares [CMMI-DEV v1.3 Nivel de Madurez 2 (L2)](CMMI.md) o [Guía PMBOK Quinta Edición](PMBOK.md) con base en la utilización del [Proceso Unificado](UP.md) para el Desarrollo de Software. El objetivo es contar con una estructura estándar para la organización de los proyectos. El contenido y uso de esta estructura se describe a continuación.

## Estructura de Directorio

La estructura de directorio está dividida y organizada por contenido y no por etapas del proyecto o formatos de archivo. Hay 9 directorios de Primer Nivel que contienen todos los productos de trabajo o archivos relacionados al proyecto. Su contenido se explica a continuación (ordenados por nombre):

* **Administracion:** Contiene todos los archivos del proyecto relativos a la administración del proyecto (análisis de negocio, administración de configuración, monitoreo, políticas, requerimientos, ...).
* **Arquitectura:** Contiene todos los archivos de arquitectura / flujos de trabajo del proyecto (UML, modelos, clases, prototipos, definición de flujos de trabajo, ...).
* **Desarrollo:** Contiene todos los archivos de desarrollo del proyecto (código fuente, recursos desarrollados, componentes utilizados, modelos de base de datos y scripts, ...).
* **Entregables:** Contiene todos los entregables del proyecto (liberaciones compiladas del código fuente, paquetes, manuales, documentación, recursos, ...).
* **Mantenimiento:** Contiene todos los archivos del ciclo de mantenimiento del proyecto.
* **Plantillas:** Contiene todas las plantillas que se deben utilizar para generar la documentación requerida para el proyecto.
* **Precedentes:** Contiene todos los archivos obtenidos del cliente relacionados al proyecto (el formato de solicitud de proyecto, recursos, documentos, archivos, ...).
* **Referencias:** Contiene todos los materiales de referencia para el proyecto (enlaces, publicaciones, white papers, reportes técnicos, especificaciones, ...).
* **tmp:** Este es un directorio temporal para cualquier propósito.

Toda la estructura de directorio se explica en el archivo [STRUCTURE.md](STRUCTURE.md) a detalle, el cual contiene la explicación de todas las sub-carpetas.

**Nota:** Se puede extender la estructura de directorio con nuevas sub carpetas conforme sea requerido, siempre y cuando se sigan las convenciones de nombramiento explicadas posteriormente.

## Convenciones de Nombramiento

Las convenciones sugeridas para el nombramiento de archivos son las siguientes:

1. Los nombres de archivo deben seguir una forma predefinida explicada a continuación. Este patrón se debe definir por proyecto y se debe utilizar en todos los nombres de archivo dentro del mismo.

	Patrón:
	
		(<prefijo>_)<nombre>(_<sufijo>)(.<extension>)
	
	Explicación de etiquetas:
	
	* _(Opcional)_ `<prefijo>`: Es una cadena que antecede al nombre. Normalmente se establece como el código del proyecto. También se puede utilizar la fecha de creación del archivo.
	* _(Requerido)_ `<nombre>`: Esta parte del patrón es el nombre significativo y descriptivo del archivo que resume el contenido del mismo.
	* _(Opcional)_ `<sufijo>`: Es una cadena que sucede al nombre. Generalmente se establece como la versión del documento para tener un seguimiento de cambios (cuando no se utiliza ningún [SCV](http://es.wikipedia.org/wiki/Control_de_versiones)). También se puede utilizar la fecha de creación del archivo.
	* _(Opcional)_ `<extension>`: Es la extensión del archivo cuándo sea pertinente.
	
	**Importante:** El caracter `_` _(guión bajo)_ no debe ser utilizado en el interior de cualquiera de las etiquetas, simboliza una separación entre las partes del patrón y debe ser incluida solamente cuando el prefijo y/o sufijo estén presentes.

2. En general, el nombre de archivo debe utilizar la [Notación Pascal (o Notación Upper Camel Case)](http://es.wikipedia.org/wiki/CamelCase) que utiliza mayúsculas en la primera letra de cada palabra (incluyendo acrónimos de más de dos letras de longitud). Por palabras (o siglas) que consistan de dos o menos letras se debe usar la Notación de Mayúsculas (todas las letras en mayúsculas).

	Ejemplos:
	
		EvaluacionRoiDeProyecto
		Usabilidad
		ControlDeCalidad
		RequerimientosDeHW

3. No se deben utilizar caracteres especiales en los nombres. Todos los caracteres especiales deben ser cambiados por su caracter simple equivalente.

	Ejemplos:
	
		Evaluación ---> Evaluacion
		Tamaño ---> Tamano
	
	Conversión de caracteres especiales más comunes:
	
		[Á, Ä], [á, ä] ---> [A], [a]
		[É, Ë], [é, ë] ---> [E], [e]
		[Í, Ï], [í, ï] ---> [I], [i]
		[Ó, Ö], [ó, ö] ---> [O], [o]
		[Ú, Ü], [ú, ü] ---> [U], [u]
		[Ñ], [ñ] ---> [N], [n]

4. El esquema de versionamiento de archivos deberá seguir los conceptos detrás de las reglas enunciadas en la [Especificación de Versionamiento Semántico v2.0.0](http://semver.org/spec/v2.0.0.html).

## Plantillas

Las plantillas no están organizadas por directorio ya que esto facilita la búsqueda de una plantilla específica. En su lugar tienen un nombre auto-explicativo que incluye la ruta que debe ser utilizada para el documento generado. Cada directorio en el nombre de archivo está separado por un guión bajo `_` mientras que el último grupo es el nombre genérico del documento (su propósito también es auto-explicativo).

Un documento basado en la plantilla:

	Administracion_AnalisisNegocio_CasosNegocio_EvaluacionRoiDeProyecto.dotx

debe almacenarse en el directorio:

	Administracion/AnalisisNegocio/CasosNegocio/

con nombre de archivo:

	MIPROY_EvaluacionRoiDeProyecto_v1.0.docx

El `<prefijo>`, `<sufijo>` y `<extension>` utilizados en este ejemplo son `MIPROY`, `v1.0` y `docx` respectivamente.