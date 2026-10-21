# Mapa del Estado mexicano — actualización documental v1.6

Fecha de compilación: 2026-10-21. Corte estructural base: 2026-09-29.

## Resultados comprobados de esta ronda

- **5.315** registros de unidades e instituciones conservados sin eliminar ni añadir entidades ficticias.
- **6.418** relaciones conservadas: solo 2 fueron reclasificadas de provisionales a adscripciones inmediatas documentadas.
- **33** síntesis funcionales: **22 dependencias** con competencias generales basadas en la LOAPF y **11 unidades** con objetivos/funciones de manuales.
- **16** titulares superiores nuevos con fuente oficial; sumados a 25 previos: **41**.
- **460** relaciones conservadas como pertenencia institucional con adscripción inmediata **por precisar**.

**Importante:** los campos `fecha_consulta` y `titular_fecha_verificacion` indican la comprobación de la información, NO la fecha de nombramiento ni de entrada en vigor. Las síntesis normativas NO sustituyen el texto del artículo, ni agotan el conjunto de facultades. La matriz conserva los 5.315 registros y no modifica las 6.418 relaciones en número.

## Instalación

Descomprime `mapa_estado_mexicano_web_v1_6.zip`; sube a la raíz de GitHub los archivos interiores, no el archivo ZIP. Sustituye `index.html`, sin borrar los demás ficheros publicados. Se incluyen los CSV de auditoría y codificación para descarga separada. Conserva copia de la versión anterior antes de sobrescribir.

## Prioridades siguientes

1. Completar atribuciones específicas de las 5.282 unidades sin síntesis funcional; requieren manual/reglamento aplicable a cada unidad.
2. Titulares intermedios: directorios institucionales/Plataforma Nacional de Transparencia con vigencia efectiva.
3. Cotejar las 460 relaciones provisionales contra organigramas y manuales actualizados antes de cambiar `id_padre`.
4. Modelar vigencia (inicio/fin), nombramientos y sucesiones como **eventos**, no como fechas de consulta.

## Fuentes principales (APA 7)

Cámara de Diputados del H. Congreso de la Unión. (2026). *Ley Orgánica de la Administración Pública Federal* (última reforma, 7 de mayo de 2026). https://www.diputados.gob.mx/LeyesBiblio/pdf/LOAPF.pdf

Cámara de Diputados. (2023). *Manual general de organización de la Cámara de Diputados* (actualización del 18 de julio de 2023). https://www.diputados.gob.mx/LeyesBiblio/marjur/marco/MGOCD.pdf

Secretaría Ejecutiva del Sistema Nacional Anticorrupción. (2025). *Manual de organización general de la Secretaría Ejecutiva del Sistema Nacional Anticorrupción*. https://sidof.segob.gob.mx/notas/docFuente/5773842

Los 16 enlaces de evidencia nominal constan en `titulares_nuevos_v1_6.csv`.
