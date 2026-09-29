# Mapa del Estado mexicano · v1.4.0

Edición del 29 de septiembre de 2026. La base pasa de 1.598 a **5.315 registros**, con **6.418 relaciones** y **133 fuentes catalogadas**. Las cinco etapas federales tienen ampliaciones y cobertura parcial.

## Cómo subir esta versión a tu web

1. Descargá `mapa_estado_mexicano_web_v1_4_0.zip` y descomprimilo. No subas el ZIP cerrado.
2. Entrá a [tu repositorio en GitHub](https://github.com/bustiflavia-prog/mapa-estado-mexicano). En **Code**, elegí **Add file → Upload files**.
3. Arrastrá **todos los archivos que están dentro de la carpeta descomprimida**. Deben quedar en la raíz del repositorio, junto al `index.html` existente. Es esencial reemplazar **index.html**: los datos que usa la web están incorporados en ese archivo. Subir sólo los CSV no actualiza los buscadores.
4. Abajo, pulsá **Commit changes**. Esperá a que el despliegue en **Actions** termine correctamente. Abrí [la web](https://bustiflavia-prog.github.io/mapa-estado-mexicano/) y recargá con **Ctrl + Shift + R** o **Cmd + Shift + R**.

La web debe mostrar **v1.4.0** y **5315 registros**. Si todavía aparece una versión anterior, revisá que hayas reemplazado `index.html`, que los archivos estén en la raíz y que el despliegue haya terminado.

## Qué revisar después de subirla

- En **Buscar**, escribí “Banco de México”: hay resultados al escribir, un botón de búsqueda y respuesta a Enter. El filtro de institución incluye las fichas de las cinco etapas.
- En **Comparar**, los cuatro desplegables contienen opciones. Elegí dos instituciones o usá la búsqueda de comparación.
- En **Relaciones**, elegí una institución. Los filtros distinguen jerarquía, agrupación, sectorización, pertenencia, territorio y sucesión.
- En **Explorar estructuras**, elegí una institución federal. Debajo del mapa aparecen los nodos inmediatos; podés filtrar nombres y abrir el siguiente nivel.
- En **Cobertura federal**, filtrá por etapa e institución para leer qué se cargó y qué falta. No se presenta ninguna etapa como terminada.
- Probá la descarga de **Excel**, **CSV**, **Relaciones** y **Cobertura federal**.

## Visitas y aportes

El paquete conserva `config_publicacion.js`, tu contador GoatCounter y el foro Giscus configurados para tu repositorio. No hay que repetir la configuración.

El contador se activa en el dominio público de tu web. Para ver visitas, entrá a [tu panel GoatCounter](https://bustiflavia.goatcounter.com/). Los aportes de la pestaña **Aportes** se guardan en GitHub Discussions. Comentar no da permiso para modificar ni borrar los datos: la edición de los archivos depende de los permisos del repositorio.

## Archivos del paquete

- `index.html`: web con buscadores, mapas, comparación, relaciones y cobertura.
- `base_maestra_v1_4_0.xlsx`: libro maestro con 10 hojas, filtros y cobertura federal.
- `datos_base_v1_4_0.csv`: los 5.315 registros con fuente, fechas, vínculo y notas.
- `relaciones_institucionales_v1_4_0.csv`: relaciones y su evidencia.
- `fuentes_v1_4_0.csv`: catálogo de 133 fuentes.
- `cobertura_federal_v1_4_0.csv`: 229 fichas de cobertura institucional o de tipos de órganos.
- `cobertura_dependencias_v1_4_0.csv` y `cobertura_paraestatales_v1_4_0.csv`: detalle de estos ámbitos.
- `titulares_v1_4_0.csv`: 25 titulares conservados, con sus fechas originales; no se actualizaron en esta edición.
- `AVANCE_Y_PENDIENTES_FEDERALES_v1_4_0.md`: alcance y próxima carga por etapas.
- `reporte_cobertura_v1_4_0.json`: cifras de esta edición.
- `sector_paraestatal_2026.csv`, `config_publicacion.js`, `GUIA_VISITAS_Y_APORTES.md` y `robots.txt`: padrón y configuración conservados.

Los registros incluyen instituciones, órganos, unidades, agrupaciones y puestos tipo. **No cuentan personas ni plazas**, y la cantidad cargada no permite medir el tamaño real de una institución. La fecha de consulta no acredita que todas las estructuras sigan vigentes; cada ficha identifica su edición documental y el cotejo pendiente.
