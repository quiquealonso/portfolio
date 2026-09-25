# Portfolio de Quique Alonso

Proyecto de práctica para la primera clase de GitHub. Este sitio sirve como un portfolio estático básico para probar el flujo de publicación con GitHub Pages.

## Producción

URL pública del entorno de producción: https://quiquealonso.github.io/portfolio/

## Despliegue

La arquitectura de despliegue se basa en un evento `push` a la rama `main`, que dispara el workflow de GitHub Actions. El servicio ejecutor es `GitHub Actions`, que toma el contenido estático del repositorio y lo publica en GitHub Pages.

## Workflow

La definición del workflow está en `.github/workflows/static.yml`.