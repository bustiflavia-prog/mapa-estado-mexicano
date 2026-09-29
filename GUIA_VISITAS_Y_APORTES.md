# Publicar y comprobar visitas y aportes

Las conexiones ya están configuradas para `bustiflavia.goatcounter.com` y para la categoría **General** de GitHub Discussions del repositorio `bustiflavia-prog/mapa-estado-mexicano`. No necesitas editar código ni repetir el registro de las cuentas.

## Publicar el sitio

1. Descarga `mapa_estado_mexicano_web_v1_3_0.zip` y **extrae** sus archivos en tu computadora. No subas el ZIP directamente al repositorio.
2. Abre `https://github.com/bustiflavia-prog/mapa-estado-mexicano` en GitHub, en la raíz del repositorio. Haz clic en **Add file → Upload files**.
3. Abre la carpeta que acabas de extraer, selecciona **los archivos de su interior** y arrástralos al recuadro de carga de GitHub. Deben aparecer en la raíz del repositorio, no dentro de una subcarpeta. Comprueba que se incluyen `index.html` y `config_publicacion.js`.
4. Escribe, por ejemplo, `Publicar v1.3.0: visitas y aportes` en el mensaje del cambio y confirma. Deja que GitHub Pages publique la nueva versión. La URL pública es `https://bustiflavia-prog.github.io/mapa-estado-mexicano/`.

## Comprobar el resultado

- **Versión:** abre la web pública y recárgala con `Ctrl + Shift + R`. La insignia superior debe decir `v1.3.0` y la pestaña **Aportes** debe estar visible.
- **Visitas:** abre la página pública una vez y luego entra a `https://bustiflavia.goatcounter.com/` con tu cuenta. Debería comenzar a aparecer actividad; si sigue en cero, espera unos segundos y prueba sin bloqueador de anuncios. Solo se cuentan visitas posteriores a la publicación de la configuración. El número de visitantes es una estimación, no una identificación individual.
- **Comentarios:** entra en **Aportes** dentro de la web. Debe aparecer el cuadro de giscus; inicia sesión con GitHub y deja un comentario de prueba. Luego comprueba que aparece también en la pestaña **Discussions** del repositorio. Cualquiera puede leer; para escribir se necesita una cuenta de GitHub.
- **Correcciones:** el botón de corrección abre un reporte público en GitHub Issues. Los aportes no cambian automáticamente los datos del mapa.

Si el cuadro de comentarios no aparece, comprueba que el repositorio sigue siendo público, que **Discussions** permanece activado y que la aplicación giscus está instalada para este repositorio. Si la versión visible sigue siendo anterior, verifica que los archivos se subieron a la raíz y que `index.html` fue reemplazado.
