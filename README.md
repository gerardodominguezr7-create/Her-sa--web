# HER-SA · Comapro Servind — Sitio web

Catálogo de servicios convertido en sitio web estático (HTML/CSS/JS puro, sin frameworks ni build tools).

## Estructura

```
hersa-site/
├── index.html          → Estructura y contenido del sitio
├── css/
│   └── styles.css      → Todos los estilos (tokens de color, tipografía, layout, responsive)
├── js/
│   └── script.js       → Menú móvil + animaciones de aparición al hacer scroll
├── images/              → Fotografías extraídas del catálogo original (optimizadas)
└── README.md
```

## Cómo usarlo

1. Descomprime el ZIP conservando la estructura de carpetas (index.html, css/, js/ e images/ deben quedar en el mismo nivel).
2. Abre `index.html` directamente en el navegador, o súbelo tal cual a cualquier hosting estático (Netlify, Vercel, GitHub Pages, un servidor propio, etc.). No requiere servidor ni instalación de dependencias.
3. Las tipografías (Anton, Oswald, Work Sans, JetBrains Mono) se cargan desde Google Fonts — se necesita conexión a internet para verlas correctamente; si no hay conexión, el navegador usará las fuentes de reemplazo (sans-serif).

## Personalización rápida

- **Colores de marca:** editar las variables al inicio de `css/styles.css` (bloque `:root`), por ejemplo `--green`, `--orange`, `--asphalt`.
- **Textos:** todos los textos están directamente en `index.html`.
- **Imágenes:** reemplaza los archivos en `images/` conservando el mismo nombre, o cambia la ruta en el `src` correspondiente dentro de `index.html`.
- **Enlaces de contacto:** el correo y los teléfonos están en la sección `#contacto` y en el `<footer>`.

## Secciones incluidas

- Portada (hero) con llamado a cotizar
- Los 5 pilares de servicio (Obra civil, Industria, Mantenimiento, Comercializadora, Casa-habitación)
- Proyectos destacados por línea de servicio, con año y ubicación
- Galería fotográfica
- Bloque de cotización y footer con datos de contacto
