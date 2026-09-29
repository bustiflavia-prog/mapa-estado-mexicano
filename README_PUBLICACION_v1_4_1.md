# Mapa del Estado mexicano · sitio v1.4.1

Corrección de la interfaz del 29 de septiembre de 2026. La base documental permanece en v1.4.0: 5.315 registros, 6.418 relaciones y 133 fuentes. Esta edición modifica la presentación y la navegación.

## Actualización rápida desde v1.4.0

1. Descomprimí `mapa_estado_mexicano_web_v1_4_1.zip`.
2. Entrá a https://github.com/bustiflavia-prog/mapa-estado-mexicano . En **Code → Add file → Upload files**, subí **index.html**, reemplazando el archivo existente en la raíz.
3. Pulsá **Commit changes**, esperá a que el despliegue de **Actions** termine y abrí https://bustiflavia-prog.github.io/mapa-estado-mexicano/ .
4. Recargá con **Ctrl + Shift + R**. Debe aparecer **v1.4.1 · publicación** y **5315 registros**.

El paquete también incluye los archivos de datos y el Excel de v1.4.0. Si todavía no los habías subido, subí todos los archivos descomprimidos a la raíz. Los nombres de los CSV y del Excel mantienen v1.4.0 porque su contenido documental es el mismo.

## Qué se corrigió

- Encabezado con búsqueda y descargas distribuidos dentro del ancho disponible.
- Panorama con seis bloques navegables; las instituciones aparecen en tarjetas al abrir cada bloque.
- Estructuras recorridas por un nivel inmediato; el dibujo muestra hasta 12 nodos por página. La lista permite filtrar los nombres y abrir el siguiente nivel.
- Adaptación a teléfonos: bloques en tarjetas y estructuras en listas legibles.
- Selector de institución sin una selección engañosa durante el panorama; leyenda ajustada al bloque abierto y fechas de titularidad descritas correctamente.

## Cómo navegar

En **Panorama**, pulsá un bloque. En las tarjetas, **Ficha** abre los datos y las fuentes; **Abrir estructura** muestra su primer nivel. Para continuar, usá **Abrir nivel** en la lista o el botón **Abrir estructura** de la ficha seleccionada. **Anterior** y **Siguiente** recorren el dibujo de niveles numerosos; **Mostrar más** amplía la lista. Los 229 registros de cobertura institucional permanecen disponibles en el selector y en **Cobertura federal**.

## Validación

Se revisó la interfaz en Chromium a anchos de 1.833, 1.440, 1.280, 1.024, 768, 390 y 320 píxeles. Pasaron 28 verificaciones en navegador y 39 comprobaciones de interacción del DOM. Se verificó que los cinco conjuntos de datos incrustados coincidan exactamente con v1.4.0 y que los archivos de datos, Excel, visitas y comentarios conserven sus bytes.

Las cinco etapas federales continúan parciales; esta corrección visual no amplía su cobertura. El alcance documental se detalla en `AVANCE_Y_PENDIENTES_FEDERALES_v1_4_0.md`.
