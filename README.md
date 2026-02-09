Preparación para GitHub Pages

Este repositorio contiene un sitio estático mínimo.

Despliegue automático:
- El workflow `.github/workflows/gh-pages.yml` publica el contenido del repositorio a la rama `gh-pages` cada vez que se hace `push` a `main`.
- La acción utilizada es `JamesIves/github-pages-deploy-action@v4` y utiliza `GITHUB_TOKEN` para hacer el push.
