# Avatar AEC · web

Borrador v1 de la web de Avatar AEC, organizada por capas:

- `index.html` — Capa 0: home con selector de perfil («¿Quién eres?») y las cuatro líneas de servicio.
- `propietarios.html` — Capa 1: página de perfil (propietarios y operadores).
- `captura.html` — Capa 2: página de línea (captura de la realidad).
- `assets/` — logo de Avatar (`avatar-mark.png`, blanco sobre baldosa gris #333333), nubes de puntos de Analytical Reality (`.webp` con fondo transparente, recortadas de capturas de pantalla: sustituir por los originales cuando estén) e imágenes de casos del portfolio.

Sitio estático (HTML + CSS + JS sin dependencias ni build). Se despliega tal cual en Cloudflare Pages:
framework preset **None**, build command vacío, output directory `/`.
Las URLs `/propietarios` y `/captura` funcionan sin extensión en Cloudflare Pages.

Los textos entre [corchetes] son huecos pendientes de datos o imágenes reales.
