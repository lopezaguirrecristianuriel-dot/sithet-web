# SITHET — sitio web

Página estática (HTML + CSS puro, sin dependencias de build). Lista para GitHub Pages.

## Estructura
```
index.html
assets/
  logo.jpg
```

## Pasos para subirla a GitHub (gratis)

1. Descomprime este zip en una carpeta, por ejemplo `sithet-web`.
2. Ábrela en Visual Studio Code: `File > Open Folder...`.
3. Crea un repositorio nuevo en GitHub (por ejemplo `sithet-web`), público.
4. En la terminal de VS Code (`Terminal > New Terminal`), dentro de la carpeta del proyecto:
   ```bash
   git init
   git add .
   git commit -m "Primer deploy de SITHET"
   git branch -M main
   git remote add origin https://github.com/TU_USUARIO/sithet-web.git
   git push -u origin main
   ```
5. En GitHub, entra al repo → **Settings → Pages**.
6. En "Build and deployment" → Source, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
7. Espera 1-2 minutos y tu sitio queda publicado en:
   `https://TU_USUARIO.github.io/sithet-web/`

## Dominio propio (opcional)

Si luego quieres algo como `sithet.com` en vez de la URL de github.io:

1. Compra el dominio en un registrador (Namecheap, GoDaddy, etc. — unos $10-15 USD al año).
2. En GitHub Pages → Settings → Pages → "Custom domain", escribe tu dominio.
3. En el panel de tu registrador, agrega los registros DNS que GitHub te indique (normalmente un registro `A` apuntando a las IPs de GitHub Pages, o un `CNAME`).

## Antes de publicar

Busca `TU_CORREO@sithet.com` y `[TU NÚMERO]` dentro de `index.html` y reemplázalos por tu correo y WhatsApp reales.
