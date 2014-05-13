# Contenido y Uso

El contenido de este paquete se explican aquí. Esta estructura de proyecto es compatible con los estándares [CMMI Nivel de Madurez 2 v1.3](CMMI.md) o [Guía PMBOK Quinta Edición](PMBOK.md) sobre la base de la [Proceso Unificado](UP.md) para el Desarrollo de Software.

## Estructura de Directorio

La estructura de directorio está dividida y organizada por contenido y no por etapas del proyecto. Hay 9 directorios de Primer Nivel que contienen todos los productos de trabajo o archivos relacionados al proyecto. Su contenido se explica a continuación (ordenados por nombre):

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

## Plantillas

Las plantillas no están organizadas por directorio ya que esto facilita la búsqueda de una plantilla específica. En su lugar tienen un nombre auto-explicativo que incluye la ruta que debe ser utilizada para el documento generado. Cada directorio en el nombre de archivo está separado por un guión bajo \_ mientras que el último grupo es el nombre genérico del documento (su propósito también es auto-explicativo).

Ejemplo:

	Nombre de archivo: Administracion_AnalisisNegocio_CasosNegocio_Evaluacion ROI de Proyecto.dotx
	
	Directorio: Administracion/AnalisisNegocio/CasosNegocio/
	Nombre de archivo: <prefijo> - Evaluacion ROI de Proyecto - <sufijo>.docx

## Convenciones de Nombramiento

Las convenciones sugeridas para el nombramiento de archivos son las siguientes: