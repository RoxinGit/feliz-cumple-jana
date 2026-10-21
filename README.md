# Feliz Cumpleaños Jana

Página web de cumpleaños para Jana: una sola página estática (`index.html`), sin dependencias locales ni build.

## Estructura

```
feliz-cumple-jana/
├── index.html   # toda la página: HTML, CSS y JavaScript
├── assets/      # fotos, audios o imágenes que quieras añadir después
└── README.md
```

## Cosas que puedes cambiar

- **Fecha de inicio del contador**: en `index.html`, busca `const INICIO = new Date(2026, 3, 21);` y pon la fecha de su primer día juntos (año, mes con 0 = enero, día).
- **Canciones de Spotify**: en `index.html`, dentro de la sección `#musica`, hay un bloque `<div class="spotify">` por canción. Para añadir una, copia ese bloque y cambia el ID de la URL `embed/track/...` por el de la canción (la parte del enlace después de `/track/`, sin `?si=...`).
- **Textos de capítulos, vales y carta**: están escritos directamente en el HTML.

## Probarla en local

Abre `index.html` con doble clic en el navegador. No necesita servidor.

## Desplegar

- **Netlify (arrastrar carpeta)**: entra en app.netlify.com/drop y arrastra la carpeta del proyecto.
- **Vercel**: importa el repositorio de GitHub desde vercel.com; no hace falta configurar nada (es HTML estático).
- **GitHub Pages**: en el repositorio, Settings → Pages → Deploy from a branch → `main` / `(root)`. En repositorios privados Pages requiere plan de pago; para un repo público es gratis, pero entonces la página es visible para cualquiera con el enlace y el código.
