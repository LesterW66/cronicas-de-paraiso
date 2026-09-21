# Estructura técnica y trazabilidad del acervo

Esta guía define una organización mínima para incorporar materiales sin alterar la fuente original ni sustituirla con copias, transcripciones, fichas o textos derivados.

## Principio de referencia principal

La fuente original o maestra conserva siempre su archivo, nombre, extensión y procedencia. Todo material derivado debe identificarla mediante el **ID del acervo** de su ficha o, si esa ficha aún no existe, indicar que el vínculo está pendiente de registrar. Un derivado no reemplaza ni corrige el original.

## Tipos de material

| Tipo | Función | Relación obligatoria cuando corresponda |
| --- | --- | --- |
| Fuente original o maestra | Archivo recibido, documento, imagen, audio, video u objeto de referencia. | Su ficha de catalogación. |
| Transcripción | Representación textual de una fuente oral o documental. | ID de la ficha de la fuente maestra. |
| Ficha o catalogación | Descripción técnica y de procedencia de una pieza. | Ruta o localizador de la fuente y IDs de derivados. |
| Investigación o análisis | Nota, síntesis o interpretación de trabajo. | IDs de las fuentes que la sustentan. |
| Borrador | Texto editorial o de monografía todavía en desarrollo. | IDs de las fuentes y notas utilizadas. |
| Versión preparada para publicación web | Contenido revisado para difusión digital. | ID de cada registro maestro y condiciones de uso aplicables. |

## Directorios técnicos

Los directorios técnicos solo se crean en áreas donde ayudan a separar materiales de naturaleza distinta. Sus README no son fichas ni registros históricos.

- `originales/`: conserva archivos maestros sin modificarlos.
- `transcripciones/`: contiene textos derivados de fuentes documentales u orales; cada archivo debe referir el ID de la fuente maestra.
- `fichas/`: contiene nuevas fichas de catalogación; las plantillas existentes se conservan en la raíz de cada área como modelos de uso.
- `investigacion/`: contiene notas o análisis sustentados por IDs de fuente.
- `borradores/`: contiene textos de trabajo que no deben presentarse como versión final.
- `versiones-publicables/`: contiene versiones revisadas para su posible difusión; no implica autorización ni publicación efectiva.

No cree un directorio para un tipo de material que el área no recibe. Antes de incorporar una pieza, revise si ya existe un registro con el mismo ID o si se trata de un derivado de un registro existente.

## Secuencia de incorporación

1. Conserve o localice la fuente original o maestra y no la altere.
2. Cree una ficha con el ID correspondiente al área y registre procedencia, ubicación, derechos y responsable solo cuando se conozcan.
3. Vincule cualquier transcripción, investigación, borrador o contenido web al ID de esa ficha en **Registros relacionados** o **Fuentes y procedencia**.
4. Registre los cambios técnicos en el historial de versiones del registro afectado.
5. Mantenga las restricciones de acceso, consentimiento y derechos indicadas por la ficha maestra en todos los derivados.

## Datos desconocidos

No complete campos por inferencia. Cuando un dato requerido no se conozca, déjelo vacío o use la indicación técnica `pendiente de verificar` únicamente cuando la plantilla o los criterios del área lo permitan.
