# Revisión funcional y pendientes del Mapa del Estado mexicano

**Fecha: 29 de septiembre de 2026. Versión preparada: v1.4.2. Base documental: v1.4.0.**

En primer lugar, la revisión distingue el funcionamiento de la aplicación de la cobertura de su contenido. La versión publicada observada fue la v1.4.1; la v1.4.2 descrita aquí está preparada y comprobada para su publicación. El examen de contenidos se realizó sobre las tablas de la aplicación y sus archivos de descarga (Busti, 2026).

Asimismo, el panorama recupera los puntos de las 22 dependencias centrales, Presidencia y Consejería Jurídica, las dos cámaras y la ASF, cuatro órganos principales del Judicial, cinco autónomos y cinco regímenes especiales. Incluye accesos destacados a PEMEX, CFE e IMSS y al padrón completo de paraestatales. No dibuja simultáneamente las 5.315 entradas: cada estructura se abre por niveles.

## 1. Resultado de las comprobaciones

En concreto, la batería ampliada en Chromium completó **204 comprobaciones**, sin fallos ni errores JavaScript de la aplicación. Se verificaron 18 vistas en siete anchos de pantalla: 1.833, 1.440, 1.280, 1.024, 768, 390 y 320 píxeles. Las etiquetas del panorama no se superponen y las páginas no desbordan horizontalmente; las tablas extensas se desplazan dentro de su contenedor.

| Función | Resultado y alcance comprobado |
|---|---|
| Panorama | Instituciones principales y accesos por bloques; puntos operables con clic y teclado. |
| Filtros del panorama | Ocultan bloques; mostrar cantidades afecta el mapa. El rótulo aclara el alcance de estos filtros. |
| Zoom | Acercar, alejar y restablecer cambian la escala del dibujo. |
| Estructuras | Selección de institución, apertura de niveles, regreso a la unidad superior, paginación del dibujo y ampliación de la lista de unidades. |
| Búsqueda principal | Resultados por nombre o titular; selección de ficha con el buscador y Enter. |
| Búsqueda avanzada | Texto, bloque, tipo, institución, sector coordinador, sector funcional, situación, calidad y nivel; estados sin resultados y carga de más coincidencias. |
| Paraestatales | Búsqueda sin distinción de acentos, sector coordinador y situación; 181 fichas del padrón y 12 registros de situaciones especiales. |
| Sectores funcionales | Abren resultados, limpian el filtro de institución anterior y conservan el sector al continuar buscando. |
| Comparación | Selectores, búsqueda, ejemplos, incorporación desde ficha, limpieza y descarga CSV de las instituciones seleccionadas. |
| Relaciones | Tipos de vínculo, uno o dos saltos, tabla completa y dibujo paginado de hasta 12 nodos; navegación a las fichas de origen y destino. |
| Indicadores | Cifras de la base y categorías de calidad que suman sus 5.315 registros. |
| Entidades federativas | 32 fichas seleccionables; búsqueda de México sin exigir acentos. Organización interna pendiente. |
| Fuentes | 133 referencias; búsqueda y filtro por tipo, con indicación de búsquedas sin resultados. La prueba de interfaz no certifica la vigencia de todos los documentos. |
| Actualizaciones | Ordenación de registros por fecha de revisión y apertura de fichas. La fecha de revisión no se presenta como fecha de un cambio institucional. |
| Histórico | Información cargada, aviso de eventos ausentes y cambios sin fecha expresados como s/f. El contenido histórico continúa incompleto. |
| Cobertura APF / federal | 22 fichas centrales y 229 fichas de cobertura federal, con filtros, fuentes y pendientes. Las 229 incluyen agrupaciones de órganos jurisdiccionales. |
| Modo docente | Explicación en lenguaje accesible y ocultación del nivel técnico de la ficha. |
| Herramientas de ficha | Enlace compartido, cita actualizada, JSON, CSV, comparación y relaciones. El enlace restaura institución, nivel abierto y modo docente. |
| Imprimir / guardar PDF | Se abre una ficha imprimible con el contenido y la cita correctos. El guardado final depende del diálogo del navegador. |
| Reportar corrección | Prepara un reporte con ficha, propuesta y fuente; no lo publica automáticamente. |
| Comentarios públicos | En la v1.4.1 publicada cargó giscus con 0 comentarios y acceso de GitHub para escribir. No se publicó un comentario de prueba ni se ensayó el envío autenticado. |
| Visitas | En el sitio publicado se observó el script de GoatCounter y su configuración. No se comprobó el incremento de un total en el panel privado; queda esa verificación operativa. |

Además, las siete descargas públicas de CSV/Excel respondieron HTTP 200 con contenido reconocible. La configuración pública también respondió correctamente. Se comprobaron las descargas individuales JSON/CSV y la comparación CSV en la versión preparada.

Por otra parte, giscus permite leer comentarios públicamente y requiere autorizar el acceso de GitHub para escribir; las intervenciones se almacenan en GitHub Discussions (giscus, s. f.). La revisión comprobó la carga del componente, sin enviar mensajes.

## 2. Correcciones incorporadas en v1.4.2

1. Recuperación del mapa inicial con puntos institucionales, abreviaturas legibles, nombres completos en cada ficha y accesos a paraestatales.
2. Restauración de la ficha y del nivel de estructura al abrir un enlace compartido o recargar.
3. Actualización de la cita: sitio v1.4.2 y base federal v1.4.0 con corte 29/09/2026.
4. Corrección de indicadores de calidad que omitían categorías paraestatales y territoriales.
5. Filtro funcional persistente y limpieza del filtro institucional previo al navegar desde Sectores.
6. Carga de más resultados en la búsqueda avanzada, en lugar de un límite definitivo de 150 entradas.
7. Red de relaciones paginada y controles que ajustan su ancho en pantallas pequeñas; la tabla conserva todas las relaciones encontradas.
8. Indicación explícita de titular no cargado; cobertura parcial en las fichas federales correspondientes.
9. Textos del padrón paraestatal y metodología coherentes con 40 fichas con algún desglose y 141 sin organización interna.
10. Eliminación de la fecha de verificación como sustituto de la fecha de un cambio histórico no documentado.

## 3. Cobertura real de la información

En términos de contenido, la base conserva **5,315 registros, 6,418 relaciones y 133 fuentes**. Estas cantidades describen la base del proyecto; incluyen agrupaciones, unidades y puestos tipo. No son un censo de instituciones, una plantilla de plazas ni un número de personas empleadas.

| Dimensión | Contenido cargado | Pendiente principal |
|---|---|---|
| Ejecutivo central | 22 dependencias, Presidencia y Consejería; 1.108 registros en la etapa 1. | Manuales con profundidad desigual; completar direcciones de área, subdirecciones, departamentos, desconcentrados y oficinas territoriales. |
| Paraestatales | 181 fichas del padrón; 40 con algún desglose. De esas 40, 14 sólo tienen gobierno institucional. | 141 fichas sin organización interna; profundizar las otras 40 y verificar cambios, sectorización y sedes. |
| Situación paraestatal | 163 fichas marcadas Activa y 18 con cambios posteriores por cotejar; 12 situaciones especiales por separado. | Actualizar la evidencia normativa de las 18 fichas señaladas. El padrón no se afirma como censo exhaustivo vigente. |
| Legislativo | 440 registros, con Diputados, Senado y ASF. | Manual administrativo 2024 del Senado, comisiones e integración; adscripciones y manuales específicos. |
| Judicial | 1.065 registros; estructura parcial y 930 entradas del directorio de órganos jurisdiccionales. | Cotejar operación, creación, fusión y extinción; completar administración de SCJN, TEPJF, OAJ y TDJ. |
| Autónomos y especiales | 1.110 registros en la etapa 5; INE, INEGI, Banco de México, CNDH y FGR; TFJA, agrarios, TFCA, UNAM y Chapingo. | Manuales, unidades territoriales, titulares y ampliación del universo especial, incluido el estudio de UAM y otros entes. |
| Titulares | **25 nombres, todos de la etapa 1 del Ejecutivo**, con cargo, URL de fuente y fecha de verificación 28/09/2026. | Responsables de unidades internas y titulares de paraestatales, Legislativo, Judicial, autónomos y especiales. No se añadieron nuevos nombres en esta corrección de interfaz. |
| Funciones / atribuciones | **0 registros con el campo funciones estructurado**. Las fichas enlazan documentos que pueden contener las atribuciones. | Extraer y resumir funciones por unidad con artículo, apartado, fuente y vigencia. No confundir esto con las funciones operativas de la aplicación. |
| Sedes y códigos | 970 registros con sede y 1.488 con código orgánico de fuente. | Completar directorios físicos y correspondencia entre código, unidad y responsable. |
| Adscripción inmediata | **462 unidades marcadas por precisar**: 320 Legislativo, 70 paraestatales, 43 etapa 5 y 29 Judicial. | Resolver jefatura inmediata en manuales y organigramas; la pertenencia a una institución no demuestra subordinación directa a su titular. |
| Historia | 0 fechas de inicio, 1 de fin y 2 tipos de cambio cargados; sin predecesoras documentadas. | Construir series de creaciones, fusiones, extinciones y cambios de adscripción, con fechas sustentadas. |

Asimismo, la Secretaría de las Mujeres ilustra un avance real de desagregación: su ficha contiene **221 registros descendientes**, entre ellos 31 direcciones, 72 subdirecciones y 90 jefaturas de departamento, además de otros niveles. Estos son registros de estructura documental, no nombres de quienes ocupan cada puesto. El manual oficial incluye estructura, organigramas, objetivos y funciones (Secretaría de las Mujeres, 2026).

## 4. Orden de trabajo recomendado

1. **Titulares y trazabilidad:** incorporar primero responsables superiores de todas las ramas federales; después subsecretarías, unidades, UAF y direcciones generales. Cada ocupación debe tener cargo, fuente oficial, fecha de actualización del directorio y fecha de cotejo; un manual de organización no confirma quién ocupa actualmente un cargo.
2. **Jerarquía y profundidad:** resolver las 462 adscripciones por precisar y profundizar el Ejecutivo con manuales vigentes; registrar por separado lo normativo y lo observado en directorios de transparencia.
3. **Paraestatales por sector:** cargar la estructura de las 141 fichas sin desglose, completar las 14 con sólo gobierno institucional y revisar los cambios pendientes en 18 fichas del padrón.
4. **Funciones organizacionales:** extraer atribuciones de fuentes oficiales y vincularlas con cada unidad; mantener el fundamento preciso y evitar inferencias por similitud de nombres.
5. **Ramas federales restantes:** manual del Senado, comisiones, administración judicial, operación de tribunales, redes territoriales autónomas y entes de régimen especial ausentes.
6. **Mantenimiento:** diferenciar fecha del documento, periodo informado, vigencia normativa y fecha de consulta. Agregar historial de cambios y continuar después con las etapas estatales y municipales.

## 5. Límites de esta revisión

Finalmente, se revisó el funcionamiento y la integridad de la versión preparada, y se contrastaron controles e integraciones con el sitio publicado. No se certificó la vigencia jurídica de las 133 fuentes ni la operación actual de cada entrada judicial o paraestatal. Tampoco se verificó una sesión autenticada de comentarios ni el total privado de visitas. Esas comprobaciones no se sustituyen por una prueba visual del componente.

En cuanto a integridad, no se encontraron IDs de registros repetidos, padres inexistentes, ciclos jerárquicos, relaciones con extremos inexistentes, IDs de relación duplicados ni registros sin URL de fuente. Las cinco tablas embebidas y los archivos de datos conservan el contenido anterior; esta entrega modifica interfaz y navegación.

## Referencias

Busti, F. (2026). *Mapa del Estado mexicano* [Base de datos y aplicación web; base federal v1.4.0]. https://bustiflavia-prog.github.io/mapa-estado-mexicano/

giscus. (s. f.). *giscus: Sistema de comentarios basado en GitHub Discussions*. https://giscus.app/es

Secretaría de las Mujeres. (2026, marzo). *Manual de Organización General*. https://dof.gob.mx/2026/MUJERES/ManualdeOrganizacionGeneral.pdf
