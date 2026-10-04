# MC Salón Multieventos

Sitio estático (HTML + CSS + JS en `index.html`, fotos en `images/`). No requiere build.

## Publicar en Vercel
1. En vercel.com: Add New > Project > importar este repositorio.
2. Framework Preset: Other. Sin comando de build ni directorio de salida.
3. Deploy. Cada push a `main` vuelve a publicar.

## Al pasar al dominio definitivo
- Quitar `<meta name="robots" content="noindex">` de `index.html`.
- Cambiar `og:image` a la URL completa del dominio.
