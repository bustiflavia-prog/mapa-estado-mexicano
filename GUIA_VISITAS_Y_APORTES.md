# Activar visitas y aportes públicos

Esta edición deja listas las dos integraciones. Para que empiecen a registrar visitas y publicar comentarios hace falta conectar tus cuentas. Los valores de `config_publicacion.js` son identificadores públicos, no contraseñas.

## 1. Medición de visitas

1. Crea un sitio para `https://bustiflavia-prog.github.io/mapa-estado-mexicano/` en [GoatCounter](https://www.goatcounter.com/). El servicio te dará un código de sitio, por ejemplo `mimapa`.
2. Abre `config_publicacion.js` y sustituye la cadena vacía de `goatcounterEndpoint` por `"https://mimapa.goatcounter.com/count"`, usando tu propio código.
3. Sube el archivo actualizado junto con `index.html`. Visita la página pública y comprueba las estadísticas en `https://mimapa.goatcounter.com/`.

Las estadísticas comienzan con la activación; no recuperan visitas pasadas. El panel permite revisar vistas y estimaciones de visitantes. Algunas visitas pueden no registrarse por bloqueadores o restricciones del navegador. Solo se ejecuta el contador en el dominio público indicado, no al abrir el archivo en tu computadora.

## 2. Comentarios que todos puedan leer

1. Abre [el repositorio](https://github.com/bustiflavia-prog/mapa-estado-mexicano), entra en **Settings → Features** y activa **Discussions**. Mantén el repositorio público y elige una categoría para la conversación, por ejemplo **General**.
2. Instala la [aplicación giscus](https://github.com/apps/giscus) para ese repositorio. En [giscus en español](https://giscus.app/es) introduce `bustiflavia-prog/mapa-estado-mexicano`, selecciona la categoría y comprueba que el sitio te muestra que el repositorio cumple los requisitos.
3. Copia del código de configuración que giscus genera el `data-repo-id` y el `data-category-id`. Pon sus valores en `repoId` y `categoryId` de `config_publicacion.js`; pon en `category` el nombre exacto de la categoría elegida. Deja `repo` como está. No copies contraseñas ni tokens a ese archivo.
4. Sube `config_publicacion.js` actualizado al mismo lugar que `index.html`. Abre la pestaña **Aportes** de la web pública e inicia la conversación. giscus creará una discusión única titulada alrededor de “Mapa del Estado mexicano: aportes” cuando llegue el primer mensaje o reacción. Los comentarios también se podrán moderar en la sección **Discussions** del repositorio.

Cualquiera puede leer las conversaciones públicas. Para escribir se requiere iniciar sesión con GitHub y autorizar giscus. Si el navegador bloquea el recuadro, se puede consultar la conversación directamente en GitHub Discussions. El botón para proponer correcciones documentadas sigue llevando a GitHub Issues; necesita que **Issues** esté habilitado.

## 3. Comprobar publicación

- La insignia superior muestra **v1.3.0**.
- Búsqueda, comparación, relaciones y descargas conservan los datos de la edición v1.2.0.
- La pestaña **Aportes** muestra el cuadro de comentarios después de completar los identificadores y activar Discussions/giscus.
- Tras visitar la página pública, GoatCounter muestra nuevas vistas en su panel. La cifra de personas es estimada y no equivale a una identificación individual.

Si compartes conmigo solo la dirección pública de GoatCounter y los valores `repoId`, `category` y `categoryId`, puedo dejar `config_publicacion.js` completo. No envíes claves de acceso ni contraseñas.
