# Proceso Unificado

Esta estructura de directorio está basada en el marco de trabajo de desarrollo de software del [Proceso Unificado](http://es.wikipedia.org/wiki/Proceso_Unificado) que define al desarrollo como un proceso orientado a casos de uso, centrado en la arquitectura utilizando un ciclo de vida iterativo e incremental.

## Ciclo de vida de Proyecto

El Proceso Unificado divide el proyecto en cuatro fases:

* Concepción
* Elaboración
* Construcción
* Transición

Cada una de ellas puede tener una o múltiples iteraciones a través del proceso, aunque [el esfuerzo relativo y el énfasis cambiará en el transcurso del proyecto](http://es.wikipedia.org/wiki/Archivo:RUP_disciplines_greyscale_20060121.svg).

### Fase de Concepción

La Concepción es la fase más pequeña del proyecto e idealmente debería ser muy corta. Si la Fase de Concepción es larga entonces puede ser una indicación de una excesiva especificación de primera instancia, lo cual es contrario al espíritu del Proceso Unificado.

Las siguientes son metas típicas para la fase de Concepción.

* Establecer una justificación o caso de negocio para el proyecto
* Establecer los alcances del proyecto y las condiciones limitantes
* Delinear los casos de uso y los requerimientos clave que impulsarán el equilibrio del diseño
* Delinear una o más posibles arquitecturas
* Identificar los riesgos
* Preparar un calendario de proyecto preliminar y estimación de costos

El Hito Objetivo del Ciclo de Vida marca el final de la fase de Concepción.

Desarrollar una visión aproximada del sistema, generar el caso de negocio, definir los alcances y producir un estimado aproximado de los costos y calendarización.

### Fase de Elaboración

Durante la fase de Elaboración se espera que el equipo del proyecto capture la mayoría de los requerimientos del sistema. No obstante, las metas principales de la Elaboración son abordar los factores de riesgo conocidos y establecer y validar la arquitectura del sistema. Los procesos comunes llevados a cabo en esta etapa incluyen la creación de diagramas de casos de uso, diagramas conceptuales (diagramas de clase solamente con notación básica) y diagramas de paquete (diagramas de arquitectura).

La arquitectura es validada principalmente a través de la implementación de una Línea de Base de Arquitectura Ejecutable. Esta es una implementación parcial del sistema que incluye los componentes de arquitectura nucleares y más significativos. Se construye a lo largo de una serie de pequeñas iteraciones de tiempo definido. Para el final de la fase de Elaboración, la arquitectura del sistema deberá haberse estabilizado y la línea de base de arquitectura ejecutable debe demostrar que la arquitectura soportará la funcionalidad principal del sistema y exhibir el comportamiento correcto en términos de desempeño, escalabilidad y costo.

El entregable final de la fase de Elaboración es un plan (incluyendo estimados de costo y calendarización) para la fase de Cosntrucción. En este punto, el plan debe ser preciso y creíble dado que debe estar basado en la experiencia obtenida en la fase de Elaboración y los factores de riesgo significativos debieron haber sido abordados durante la fase de Elaboración.

### Fase de Construcción

La Construcción es la fase más larga en el proyecto. En esta fase se construye el resto del sistema basado en los cimientos construidos en la Elaboración. Las características del sistema son implementadas en una serie de iteraciones cortas de tiempo definido. Cada iteración resulta en una liberación ejecutable del software. Se acostumbra escribir descripciones textuales de casos de uso durante la fase de construcción y cada una se convierte en el comienzo de una nueva iteración. Algunos diagramas comunes de UML (Lenguaje de Modelo Unificado) utilizados durante esta fase son: de Actividad, de Secuencia, de Colaboración, de Estado (de Transición) y de Interacción General.

### Fase de Transición

La fase final del proyecto es la de Transición. En esta fase el sistema es desplegado hacia los usuarios finales. La retroalimentación recibida de una liberación inicial (o liberaciones iniciales) puede resultar en mejoras que serán incorporadas a lo largo de varias iteraciones de la fase de Transición. La fase de Transición también incluye la conversión de sistemas y la capacitación de usuarios.

## Más Información

Para más información por favor visita [Proceso Unificado](http://es.wikipedia.org/wiki/Proceso_Unificado). Existen también muchos refinamientos del Proceso Unificado que pueden ser encontrados [aquí](http://en.wikipedia.org/wiki/Unified_Process#Refinements_and_Variations).