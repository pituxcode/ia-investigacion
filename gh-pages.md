# Deploy con GitHub Pages

## Cómo funciona

El proyecto tiene dos ramas en GitHub:

- **`main`**: el código fuente (archivos `.qmd`, configuración, assets).
- **`gh-pages`**: el sitio web generado (HTML, CSS, JS). Esta rama la gestiona Quarto automáticamente; no la editas a mano.

Cuando ejecutas `quarto publish gh-pages`, Quarto:

1. Renderea todos los `.qmd` a HTML (y PDF si está configurado).
2. Copia el resultado a la rama `gh-pages`.
3. Hace push a GitHub.
4. GitHub Pages sirve el contenido de esa rama.

## URL del sitio

https://pituxcode.github.io/ia-investigacion/

## Actualizar el sitio

Desde el directorio del proyecto:

```bash
quarto publish gh-pages
```

Eso es todo. Los cambios se reflejan en la URL tras unos segundos.

## Requisitos

- Quarto instalado (`quarto --version` para verificar).
- GitHub CLI autenticado (`gh auth status` para verificar).
- Estar en la rama `main` al momento de publicar.

## Notas

- No necesitas editar ni tocar la rama `gh-pages` directamente.
- La carpeta `_book/` está en `.gitignore` y no se sube a `main`; solo va a `gh-pages`.
- Si el sitio muestra una versión anterior después de publicar, haz hard refresh en el navegador (Cmd+Shift+R).
