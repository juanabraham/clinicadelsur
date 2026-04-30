# clinicadelsur

Espejo estático de [clinicadelsur.cl](https://clinicadelsur.cl/) publicado en GitHub Pages.

- Páginas HTML: 70
- Assets: ~550 (imágenes, CSS, JS, fuentes)
- Formularios: convertidos a `mailto:` (envían a `juanantonio.abraham@gmail.com`)
- URLs reescritas a rutas relativas para funcionar bajo `/clinicadelsur/`

## Regenerar el espejo

```bash
node _work/mirror.js   # descarga páginas y assets
node _work/rewrite.js  # reescribe URLs absolutas y formularios
```
