# Mapa del Estado mexicano · v1.5 (interfaz de investigación)

Versión construida sobre `index.html` v1.4.2 **sin sustituir** ninguna de las 5.315 unidades ni las 6.418 relaciones de la base v1.4.0. Fecha de estructuración de la base: 29/09/2026.

## Cambios realizados

1. Recuperación/refuerzo del **diseño blanco y claro** del mapa mexicano.
2. Conservación de las 18 pestañas de la aplicación original, reordenadas en cuatro familias visibles: Explorar, Analizar, Documentación, Proyecto.
3. Revisión de legibilidad, navegación con teclado, panel de ficha y diseño adaptable a escritorio/tableta/móvil.
4. Nueva pestaña **Laboratorio**: cruces por texto, bloque, tipo, nivel y condición documental; página de resultados, indicadores dependientes del filtro, descarga CSV de la selección.
5. Cinco registros piloto de **síntesis de competencias generales** contrastables en LOAPF vigente, artículos 27, 28, 31, 37 y 42 Bis. No implican carga de las funciones de toda la APF ni del organigrama de cada unidad.
6. Se conserva íntegro el HTML/JS de panorama, búsqueda, sectores, comparación, redes, indicadores, fuentes, cobertura, historia, comentarios y metadatos anteriores.

## Instalación en GitHub Pages

El archivo `index.html` es autónomo en cuanto al mapa y mantiene incrustadas las matrices originales. Para actualizar un sitio que ya tiene v1.4.x, reemplaza **solo `index.html`** en la raíz del repositorio, sin tocar los archivos CSV y Excel que ya están publicados. Subir además `atribuciones_piloto_v1_5.csv` habilita su descarga independiente. No sobrescribas `base_maestra_v1_4_0.xlsx` (es una copia de apoyo, sin cambios en sus hojas).

Antes de subir, revisar localmente y conservar copia de la v1.4.2 por si hace falta reversión. No se ha modificado el repositorio remoto automáticamente.

## Alcance y cautelas

- La cifra de registros **no equivale** a instituciones individuales o puestos ocupados.
- Ausencia de nombre de titular **no equivale** a vacante.
- Funciones generales piloto **no equivalen** a todas las atribuciones de unidades administrativas.
- El histórico sigue incompleto. **No** se simulan cambios temporales a partir de fechas de verificación.
- La pestaña Laboratorio permite detectar registros cuyo texto habla de adscripción pendiente; la identificación automática es exploratoria y **no sustituye** las 462 adscripciones por precisar del informe de auditoría anterior.

## Fuentes normativas de la ampliación piloto

Cámara de Diputados del H. Congreso de la Unión. (2026). *Ley Orgánica de la Administración Pública Federal* (última reforma DOF 07-05-2026). https://www.diputados.gob.mx/LeyesBiblio/pdf/LOAPF.pdf

Busti, F. (2026). *Mapa del Estado mexicano* [Aplicación y base de datos, v1.4.0]. https://bustiflavia-prog.github.io/mapa-estado-mexicano/
