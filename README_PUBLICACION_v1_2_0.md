# Mapa del Estado mexicano · v1.2.0

Fecha de corte: 28 de septiembre de 2026.

## Publicación

Sube **todo el contenido** de este paquete a la raíz del repositorio de GitHub Pages y conserva los nombres de archivo. El sitio abre en `index.html`; los enlaces de descarga apuntan a los CSV y al Excel del mismo paquete. Si se sube sólo `index.html`, la navegación funciona, pero las descargas de archivos faltantes no.

La página incorpora la base de datos en el propio HTML para que búsqueda, filtros, comparación y relaciones funcionen sin servidor de datos.

## Alcance de esta versión

- 1,598 registros institucionales y 1,770 relaciones explícitas; 78 fuentes catalogadas.
- Se ampliaron Energía, Agricultura, Infraestructura/Comunicaciones/Transportes, Anticorrupción y Buen Gobierno, Educación Pública, Salud, Desarrollo Agrario/Territorial/Urbano y Turismo conforme a sus reglamentos, acuerdos de adscripción o manuales oficiales.
- Se cargó estructura interna de seis entidades paraestatales: Petróleos Mexicanos (328 descendientes), CFE (68), IMSS-BIENESTAR (52), IMSS (17), ISSSTE (14) y ATTRAPI (12). Las 175 paraestatales activas restantes conservan su ficha institucional y su estructura interna está pendiente de carga.
- La antigua Agencia Reguladora del Transporte Ferroviario aparece como antecedente histórico de ATTRAPI desde el 13 de enero de 2026.
- Los otros dos poderes y las estructuras subnacionales quedan para las siguientes etapas. En las 22 dependencias federales existen fichas, con profundidad dispar; esta edición amplía ocho de ellas y no equivale a estructura completa del sector público.

`cobertura_paraestatales_v1_2_0.csv` identifica entidad por entidad qué estructura interna está cargada. En el comparador, «Sin estructura interna cargada» significa que la base no contiene ese desglose, no que la entidad carezca de dependencias.

## Archivos principales

- `index.html`: sitio estático listo para GitHub Pages.
- `base_maestra_v1_2_0.xlsx`: libro de unidades, relaciones, fuentes, cobertura y comparador base.
- `datos_base_v1_2_0.csv`, `relaciones_institucionales_v1_2_0.csv`, `fuentes_v1_2_0.csv`: tablas reutilizables.
- `cobertura_dependencias_v1_2_0.csv`, `cobertura_paraestatales_v1_2_0.csv`: alcance de la carga.

Cada alta conserva la fuente oficial y la fecha de verificación en su fila. Las URLs están además en `fuentes_v1_2_0.csv`.
