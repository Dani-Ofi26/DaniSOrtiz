# Web Dani Ortiz — despliegue

Contenido de esta carpeta:
- index.html — el sitio completo en un solo archivo (fuentes, imágenes y scripts incluidos).
- assets/og.jpg — imagen para la previsualización al compartir el link.
- _headers — cache para Cloudflare Pages.

## GitHub
1. Crear un repo nuevo (por ejemplo daniortiz-web).
2. Subir el contenido de esta carpeta a la raíz del repo.

## Cloudflare Pages
1. Cloudflare → Workers & Pages → Create → Pages → Connect to Git.
2. Elegir el repo. Framework preset: None. Build command: vacío. Output directory: /
3. Deploy.

## Antes de publicar
En index.html reemplazar TU-DOMINIO (2 veces) por el dominio final, por ejemplo:
https://daniortiz.pages.dev/assets/og.jpg
Eso hace que WhatsApp muestre título, descripción e imagen.
La imagen ideal es horizontal de 1200x630 px; hoy assets/og.jpg es la tapa vertical.
