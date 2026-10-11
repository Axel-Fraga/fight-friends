# Fight Friends: paquete para publicar

Esta carpeta es el juego completo como página web. Solo hay que subirla a un servicio de hosting gratuito y te dará un link propio.

## Qué contiene
- `index.html`: el juego completo (música y sonidos generados por código, no hay archivos de audio externos).
- `manifest.webmanifest`, `sw.js` y los íconos `.png`: permiten instalarlo en la pantalla de inicio y que funcione sin internet después de la primera visita.

## Opción A: Netlify (la más rápida, sin cuenta de GitHub)
1. Entra a https://app.netlify.com/drop (puede pedirte crear una cuenta gratis).
2. Arrastra **la carpeta completa** `fight-friends-web` a la página.
3. En unos segundos te da un link tipo `https://algo.netlify.app`. Puedes cambiar el nombre en *Site settings → Change site name*.

## Opción B: GitHub Pages
1. Crea un repositorio nuevo en https://github.com y sube todos los archivos de esta carpeta.
2. En *Settings → Pages*, elige la rama `main` y la carpeta `/ (root)`.
3. Tu link será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Opción C: Cloudflare Pages
1. Entra a https://pages.cloudflare.com, crea un proyecto y elige *Direct Upload*.
2. Sube la carpeta y listo.

## Cómo instalarlo en el celular
- **iPhone (Safari):** abre el link, toca *Compartir* y luego *Añadir a pantalla de inicio*.
- **Android (Chrome):** abre el link, toca el menú de tres puntos y luego *Instalar app* o *Añadir a pantalla de inicio*.
Juega siempre con el teléfono en horizontal.

## Cómo actualizar el juego
Sube el nuevo `index.html` al mismo sitio. Para que los teléfonos descarguen la versión nueva, cambia el número de `VERSION` en `sw.js` (por ejemplo `fight-friends-v2`).

## Siguiente paso opcional: APK para Android
Una vez que tengas tu link con HTTPS, puedes convertirlo en un APK con herramientas como PWABuilder (https://www.pwabuilder.com). Revisa su guía actual, porque los pasos cambian.
