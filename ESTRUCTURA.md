# Estructura del cuadernillo

## Sitio web

- **URL:** https://pituxcode.github.io/ia-investigacion/
- **Repo:** https://github.com/pituxcode/ia-investigacion
- **Deploy:** `quarto publish gh-pages` (ver `gh-pages.md` para detalles)

## Árbol de archivos

```
ia-investigacion/
│
├── _quarto.yml          ← Configuración del libro
├── styles.css           ← Estilos personalizados
├── copy-button.html     ← Script para copiar bloques de código
├── references.bib       ← Bibliografía en formato BibTeX
│
├── conectar.qmd         ← Página de conexión (URL + QR)
├── index.qmd            ← Bienvenida (portada)
├── fundamentos.qmd      ← Fundamentos (3 ideas fuerza)
├── modulo-1.qmd         ← Módulo 1 (09:00-11:00)
├── modulo-2.qmd         ← Módulo 2 (11:15-13:00)
├── recursos.qmd         ← Recursos (políticas, checklists)
├── references.qmd       ← Referencias bibliográficas
│
├── gh-pages.md          ← Documentación del flujo de deploy
│
└── assets/
    ├── fundamentos/     ← Imágenes: transformer, asíntota, Gemini web/CLI
    ├── modulo-2/        ← Imagen: pipeline de Quarto
    └── qr-code.png      ← Código QR para página de conexión
```

## Orden de lectura

1. **conectar.qmd** — Conexión (URL grande + QR para proyectar)
2. **index.qmd** — Bienvenida, objetivos, programa, convenciones
3. **fundamentos.qmd** — 3 ideas fuerza + profundización teórica
4. **modulo-1.qmd** — Preguntas de investigación, búsqueda bibliográfica, fichas
5. **modulo-2.qmd** — Markdown, texto plano, Quarto, LaTeX, Python, redacción, traducción, revisión
6. **recursos.qmd** — Políticas editoriales, checklists, herramientas
7. **references.qmd** — Bibliografía generada automáticamente

---

## Detalle por archivo

### conectar.qmd (Conexión)
- URL del sitio en texto grande
- Código QR escaneable
- Diseñada para proyectar al inicio del taller

### index.qmd (Bienvenida)
- Información del taller (fecha, lugar, audiencia)
- Estructura de los dos módulos con programa detallado
- Explicación de Camino A (web) vs Camino B (terminal/editor)
- Convenciones usadas (callouts, bloques de código)
- Requisitos previos y herramienta recomendada (Gemini)

### fundamentos.qmd (Fundamentos)
- Idea 1: Un LLM predice la siguiente palabra (IA generativa, interfaces, transformer)
- Idea 2: Por eso alucina (paper OpenAI, asíntota, verificación)
- Idea 3: Dos técnicas — iterative prompting y meta prompting
- Profundización: entrenamiento, tipos de alucinaciones, limitaciones, ética
- Glosario de términos

### modulo-1.qmd (Módulo 1: 09:00-11:00)
- Preguntas de investigación con IA (30 min) — iterative + meta prompting con ejemplo concreto
- Búsqueda bibliográfica (40 min) — Elicit, SciSpace, Perplexity
- Fichas de trabajo (35 min) — Organizar hallazgos y sintetizar patrones

### modulo-2.qmd (Módulo 2: 11:15-13:00)
- Estructurar documento con Markdown (25 min) — texto plano, Quarto, LaTeX, ecuaciones, cómputo Python, referencias .bib
- Redacción en español con IA (30 min) — borradores, mejora, consistencia
- Traducción al inglés académico (30 min) — prompts especializados, glosario
- Revisión final y lista de verificación (20 min) — checklist, declaración de uso de IA

### recursos.qmd (Recursos)
- Políticas de IA: Taylor & Francis, Elsevier, Springer Nature
- Lista de verificación de uso de IA
- Checklist de envío a revista
- Herramientas recomendadas (búsqueda, escritura, gestores, editores)
- Enlaces de referencia
