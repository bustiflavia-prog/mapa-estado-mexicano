MAPA DEL ESTADO MEXICANO · MVP 0.2
Corte de verificación: 25 de septiembre de 2026

CONTENIDO
- index.html: aplicación interactiva autónoma. Abrir directamente en Chrome, Edge o Firefox.
- datos_base_0_2.csv: base maestra de unidades y relaciones jerárquicas.
- base_maestra_0_2.xlsx: versión de trabajo con hojas README, Unidades, Fuentes, Cobertura_APF y Resumen.
- fuentes_0_2.csv: catálogo de fuentes oficiales.
- cobertura_dependencias_0_2.csv: estado de avance de las 22 dependencias del artículo 26 de la LOAPF.

ALCANCE DE ESTA VERSIÓN
La base contiene 135 registros. Conserva el panorama general construido en la versión 0.1 y agrega:
1. Tribunal de Disciplina Judicial y Órgano de Administración Judicial en la estructura del Poder Judicial.
2. Secretaría de las Mujeres: estructura jerárquica básica según Reglamento Interior 2025 y Manual de Organización General publicado el 16/04/2026.
3. Secretaría de Energía: estructura parcial avanzada, incluyendo nivel superior y las ramas de Planeación y Transición Energética y Electricidad.
4. Secretaría de Salud: nivel superior previsto en el artículo 2, apartado A, de su Reglamento Interior.
5. ATDT: estructura administrativa del Reglamento Interior de 24/01/2025 y actualización con la Comisión Reguladora de Telecomunicaciones, adscrita a la Agencia por normativa posterior de 2025.
6. Titulares actuales verificados para las cuatro dependencias piloto.

IMPORTANTE
- “Básica completa” no significa que se hayan cargado todos los puestos, direcciones, subdirecciones o jefaturas existentes. Significa que se reconstruyó la jerarquía básica expresamente identificable en las fuentes usadas para esta fase.
- Una unidad ausente en la aplicación puede estar pendiente de carga; no debe interpretarse como inexistente.
- Las estructuras administrativas cambian. Por ello cada fila conserva fuente y fecha de verificación.
- La estructura de ATDT es especialmente evolutiva: su Reglamento Interior inicial de enero de 2025 debe leerse junto con la normativa de telecomunicaciones posterior.
- El HTML incorpora una copia de los datos para que funcione sin servidor. Modificar el CSV no modifica automáticamente el HTML.

CAMPOS CLAVE
id: identificador estable interno.
id_padre: identificador de la unidad inmediatamente superior.
nivel: profundidad relativa dentro de la base.
fuente_url: fuente oficial que sustenta la estructura.
cobertura: grado de desagregación alcanzado en esta versión.
titular / titular_fuente_url: titular actual sólo cuando fue verificado explícitamente.

FUENTES PRINCIPALES
Constitución Política de los Estados Unidos Mexicanos:
https://www.diputados.gob.mx/LeyesBiblio/pdf/CPEUM.pdf

Ley Orgánica de la Administración Pública Federal:
https://www.diputados.gob.mx/LeyesBiblio/pdf/LOAPF.pdf

Reglamento Interior de la Secretaría de las Mujeres (10/01/2025):
https://www.dof.gob.mx/nota_detalle.php?codigo=5746949&fecha=10/01/2025

Manual de Organización General de la Secretaría de las Mujeres (16/04/2026):
https://www.dof.gob.mx/nota_detalle.php?codigo=5785056&fecha=16/04/2026

Reglamento Interior de la Secretaría de Energía (17/04/2025):
https://www.dof.gob.mx/nota_detalle.php?codigo=5755222&fecha=17/04/2025

Manual de Organización General de la Secretaría de Energía (27/04/2026):
https://www.dof.gob.mx/abrirPDF.php?anio=2026&archivo=27042026-MAT.pdf&repo=

Reglamento Interior de la Secretaría de Salud (27/02/2025):
https://www.dof.gob.mx/nota_detalle.php?codigo=5750389&fecha=27/02/2025

Reglamento Interior de la ATDT (24/01/2025):
https://www.dof.gob.mx/nota_detalle.php?codigo=5747756&fecha=24/01/2025

Normativa que acredita a la Comisión Reguladora de Telecomunicaciones como OAD de ATDT:
https://www.dof.gob.mx/nota_detalle_popup.php?codigo=5783210

SIGUIENTE FASE PROPUESTA · 0.3
Completar las estructuras de las 18 dependencias que permanecen sólo en nivel raíz, comenzando por SEGOB, SHCP, Anticorrupción y Buen Gobierno, SEP, SICT y SEMARNAT; después incorporar fechas de inicio/fin de unidades y titulares para habilitar la comparación histórica.
