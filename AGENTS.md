# Agentes y Herramientas del Proyecto

## Descripción del proyecto

Guía práctica del taller "Herramientas de IA para la Productividad Científica" de la Universidad de Aysén. Publicada como libro Quarto en GitHub Pages.

**Fecha del taller:** 28 de enero 2026, 09:00-13:00
**Lugar:** Sala D6, Campus Lillo, Universidad de Aysén
**Audiencia:** Cuerpo académico
**Sitio web:** https://pituxcode.github.io/ia-investigacion/
**Repositorio:** https://github.com/pituxcode/ia-investigacion

## Herramientas utilizadas

- **Claude Code (Opus 4.5):** Asistente principal para desarrollo de contenidos
- **Quarto 1.8.27:** Sistema de publicación (libro HTML + PDF)
- **Git / GitHub:** Control de versiones y hosting (GitHub Pages)
- **GitHub CLI (`gh`):** Autenticación y gestión del repositorio
- **VS Code / Cursor:** Editor de texto
- **Python:** Cómputo científico integrado en Quarto, generación de QR

## Flujo de trabajo

1. Editar archivos `.qmd` en el editor
2. `quarto preview` para previsualizar localmente
3. Commitear cambios con Git
4. `quarto publish gh-pages` para publicar

## Convenciones

- Documentación en español chileno/latinoamericano
- Formato Quarto (`.qmd`) para todo el contenido del taller
- Archivos `.md` solo para documentación interna del proyecto
- Commits descriptivos en español
- Bloques de código siempre con indicador de lenguaje (`text`, `bash`, `markdown`)
- Pestañas Terminal asumen Gemini ejecutándose dentro del proyecto (no comandos bash de Gemini)
