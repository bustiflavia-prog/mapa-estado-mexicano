MAPA DEL ESTADO MEXICANO · MVP 0.3
Corte de verificación: 25 de septiembre de 2026

CONTENIDO WEB
- index.html: aplicación interactiva autónoma.
- datos_base.csv: base estructural abierta.
- base_maestra.xlsx: libro de trabajo con unidades, fuentes, cobertura, resumen e histórico_schema.
- fuentes.csv: catálogo de fuentes oficiales.
- cobertura_dependencias.csv: estado de avance de las 22 dependencias del artículo 26 de la LOAPF.
- .nojekyll: publicación directa en GitHub Pages.

CAMBIOS DE DISEÑO · v0.3
1. Las 32 entidades federativas dejan de dibujarse como 32 etiquetas dentro de una cuña estrecha del panorama radial.
2. El panorama muestra un único nodo agregado territorial.
3. Se añade la vista específica “Entidades federativas”, con buscador y 32 tarjetas seleccionables.
4. En jerarquías muy densas, sólo se rotulan por defecto los niveles inmediatos; los nodos profundos conservan título emergente y ficha lateral.
5. Se mantiene la distinción entre panorama, exploración APF y cobertura.

AMPLIACIÓN DE DATOS · v0.3
La base pasa de 135 a 286 registros.
Se amplía la estructura de:
- Secretaría de Gobernación.
- Secretaría de Hacienda y Crédito Público.
- Secretaría de Medio Ambiente y Recursos Naturales.
- Secretaría de Infraestructura, Comunicaciones y Transportes.
- Secretaría Anticorrupción y Buen Gobierno.
- Secretaría de Educación Pública.

También se reservan los campos:
fecha_inicio, fecha_fin, tipo_cambio e id_predecesora,
para la futura dimensión histórica.

CRITERIO
La cobertura es incremental. Una unidad ausente significa “aún no cargada” y no debe interpretarse automáticamente como inexistente.
Las relaciones cargadas se sustentan en fuentes oficiales; cuando una relación se reconstruye de una disposición indirecta (por ejemplo, régimen de suplencias), se explicita en las notas metodológicas.
