# Juli & Dani ❤️

Una página para guardar fotos y momentos de nuestra historia. Está publicada en [amor.danielalbertorosso.com.ar](https://amor.danielalbertorosso.com.ar/).

## Ver la página

Abrí `index.html` en un navegador. No requiere instalación ni conexión a internet.

## Estructura

- `index.html`: diseño, textos, contadores de tiempo y galería.
- `imagenes/`: las 11 fotos en formato JPG que usa la galería.

Para agregar o cambiar una foto, guardala en `imagenes/` y actualizá su ruta, descripción y texto en la sección **GALERÍA** de `index.html`. Las fechas de los contadores están en `metDate` y `datingDate`, al comienzo del bloque `<script>`.

## Vales de amor

Al canjear un vale, aparece una animación de corazones y el vale queda marcado como **Visto ✓**. El estado se guarda en el navegador donde se canjeó; si se abre la página en otro navegador o dispositivo, los vales empiezan sin canjear.

## Música

Al final de la página hay un reproductor compacto de Spotify con «Entra en Mi Vida» de Sin Bandera. Se intenta iniciar al quinto toque del corazón; los toques anteriores no lo reinician. Al terminar, la página intenta repetirla. Spotify puede limitar la reproducción a una muestra para quienes no inicien sesión y su reproductor incrustado no ofrece mute.

Si subís la página a otro servidor, conservá `index.html` y la carpeta `imagenes/` juntos.

## Compartir por WhatsApp

Copiá el contenido de `mensaje-whatsapp.txt` y pegalo en el chat. El enlace tiene una portada configurada mediante metadatos Open Graph: `portada-whatsapp.jpg`. El archivo `portada-whatsapp.svg` es la versión editable de esa portada.
