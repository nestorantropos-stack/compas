# Sitio web — Compas SpA

Sitio estático de una página para Compas · Estudios e Inteligencia Institucional, preparado para GitHub Pages.

## Contenido

- `index.html` — el sitio completo (estilos y script incluidos)
- `favicon.svg` — ícono de pestaña
- `.nojekyll` — indica a GitHub Pages que sirva los archivos tal cual

## Publicar en GitHub Pages

1. Entra a https://github.com/new y crea un repositorio público llamado `compas` (o `TU-USUARIO.github.io` si quieres que el sitio quede en la raíz de tu dominio de GitHub).
2. En el repositorio nuevo, elige **Add file → Upload files** y arrastra `index.html`, `favicon.svg`, `README.md` y `.nojekyll`. Confirma con **Commit changes**.
3. Ve a **Settings → Pages**. En **Build and deployment**, selecciona *Source: Deploy from a branch*, rama `main`, carpeta `/ (root)`, y guarda.
4. En uno o dos minutos el sitio queda disponible en `https://TU-USUARIO.github.io/compas/`.

## Dominio propio (opcional)

Si registras un dominio (por ejemplo `compas-estudios.cl` en NIC Chile):

1. En **Settings → Pages → Custom domain**, escribe el dominio y guarda (GitHub crea un archivo `CNAME`).
2. En NIC Chile, apunta el dominio a GitHub Pages con registros A hacia `185.199.108.153`, `185.199.109.153`, `185.199.110.153` y `185.199.111.153`, o un CNAME de `www` hacia `TU-USUARIO.github.io`.
3. Activa **Enforce HTTPS** cuando aparezca disponible.

## Editar textos

Todo el contenido está en `index.html`, organizado por secciones comentadas (`<!-- SERVICIOS -->`, `<!-- CONTACTO -->`, etc.). Se puede editar directamente desde GitHub con el ícono del lápiz.
