# Fyra — landing page

Página estática (HTML + CSS puro, sin JS, sin build) lista para GitHub Pages.

## Archivos
- `index.html` — la página
- `styles.css` — todos los estilos
- `hero.jpg` — imagen de portada/novela (placeholder generado con IA; cámbiala cuando tengas tu propio arte o el ícono de la app)

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub (público), por ejemplo `fyra-landing`.
2. Sube estos 3 archivos a la raíz del repo (arrástralos en la web de GitHub, o por `git add . && git commit -m "landing inicial" && git push`).
3. Entra a **Settings → Pages** del repo.
4. En "Source" elige la rama `main` y la carpeta `/ (root)`, luego **Save**.
5. En 1-2 minutos tu sitio queda publicado en `https://<tu-usuario>.github.io/fyra-landing/`. Esa es la URL que pones en el campo "Sitio web" de la Página de Facebook.

## Antes de publicar, reemplaza
- Los 3 enlaces `href="https://facebook.com/"` por la URL real de tu Página de Facebook una vez que la tengas (el botón "Síguenos en Facebook" y "Síguenos para el estreno" la usan dos veces, y el ícono circular del pie de página la tercera).
- El botón "Muy pronto en Google Play": cuando tu app ya esté pública, cámbialo por un enlace `<a>` real a la ficha de Play Store.
- `hero.jpg` por tu propio arte de portada cuando lo tengas.

## Dominio propio (opcional, más adelante)
GitHub Pages admite un dominio propio gratis (solo pagas el dominio, ~$10-15/año): agregas un archivo `CNAME` con tu dominio y apuntas un registro DNS tipo CNAME a `<tu-usuario>.github.io`. Si quieres, te ayudo con eso cuando llegues a ese punto.
