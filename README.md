# SpotItFly – Mini sitio para App Store
Generado el 2025-11-03. Contiene:
- `privacy.html` — Política de privacidad (ES/EN).
- `support.html` — Página de soporte con email.
- `community.html` — Normas de la comunidad.
- `index.html` — Portada simple.

## Publicar rápido con GitHub Pages (gratis)
1. Crea un repo: `spotitfly-site` en GitHub.
2. Sube estos archivos a la rama `main` (carpeta raíz).
3. En **Settings → Pages**: Source = *Deploy from a branch* → Branch = `main` (root).
4. La URL quedará como `https://<tu-usuario>.github.io/spotitfly-site/`  
   - Privacidad: `.../privacy.html`  
   - Soporte: `.../support.html`

## Opción Firebase Hosting (gratis)
1. `npm i -g firebase-tools` → `firebase login`
2. `firebase init hosting` (elige sitio) y coloca estos archivos en `public/`.
3. `firebase deploy` → usa las URLs HTTPS generadas.
