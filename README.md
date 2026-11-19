# Portafolio Sebastián Sovier

## Publicación inmediata (sin instalar Angular)
1. Crea un repositorio público llamado `sebastiansovier.github.io` en tu cuenta de GitHub (si ya existe, revisa su contenido antes de reemplazarlo).
2. Sube los archivos de esta carpeta al repositorio, incluidos `docs/index.html` y `docs/.nojekyll`.
3. En Settings > Pages > Build and deployment, elige Deploy from a branch, main y /docs. Guarda.
4. Cuando GitHub confirme el despliegue, visita https://sebastiansovier.github.io/ y copia la URL a Get on Board.

## Proyecto Angular 19
Requiere Node.js compatible con Angular 19 (por ejemplo 22 LTS).
```bash
npm install
npm start
```
Abre http://localhost:4200. Para producción: `npm run build`. Los archivos generados estarán en `dist/portfolio/browser/`. Para servir esta versión con GitHub Pages en el repositorio de usuario, copia el contenido de esa carpeta a `docs/` y conserva `.nojekyll`.

El HTML estático y el proyecto Angular tienen el mismo diseño; si editas uno, replica los cambios en el otro o reemplaza docs con la compilación de Angular. La versión estática no necesita dependencias.

## Antes de publicar
- Confirma fechas, nombres de empleadores y clientes, datos de contacto y que los proyectos de salud puedan presentarse públicamente.
- Las ilustraciones son conceptuales. No son capturas de aplicaciones reales.
- Agrega enlaces a demos o repositorios propios cuando estén disponibles. No publiques código ni datos privados de clientes.
- El sitio no incluye PDF de CV: añade una versión pública sin datos personales que no desees difundir si lo necesitas.
