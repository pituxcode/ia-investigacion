# Estructura del cuadernillo

## Árbol de archivos

```
capacitacion-ia-investigacion/
│
├── _quarto.yml          ← Configuración del libro
├── styles.css           ← Estilos personalizados
├── copy-button.html     ← Script para copiar bloques de código
│
├── index.qmd            ← Bienvenida (portada)
├── fundamentos.qmd      ← Fundamentos (3 ideas fuerza)
├── modulo-1.qmd         ← Módulo 1 (09:00-11:00)
├── modulo-2.qmd         ← Módulo 2 (11:15-13:00)
├── recursos.qmd         ← Recursos (políticas, checklists)
├── references.qmd       ← Referencias bibliográficas
│
├── references.bib       ← Bibliografía en formato BibTeX
│
└── assets/              ← Recursos multimedia
    ├── fundamentos/     ← Imágenes y recursos del capítulo
    ├── modulo-1/        ← Imágenes y recursos del capítulo
    └── modulo-2/        ← Imágenes y recursos del capítulo
```

## Orden de lectura

1. **index.qmd** — Bienvenida
   - Portada, objetivos, estructura del taller, convenciones

2. **fundamentos.qmd** — Fundamentos
   - 3 ideas fuerza + teoría de profundización

3. **modulo-1.qmd** — Módulo 1
   - Preguntas de investigación, búsqueda bibliográfica, fichas
   - Prompts integrados en cada actividad

4. **modulo-2.qmd** — Módulo 2
   - Markdown, redacción español, traducción inglés, revisión
   - Prompts integrados en cada actividad

5. **recursos.qmd** — Recursos
   - Políticas editoriales, checklists, herramientas

6. **references.qmd** — Referencias
   - Lista de referencias citadas

---

## Detalle por archivo

### index.qmd (Bienvenida)
- Información del taller (fecha, lugar, audiencia)
- Estructura de los dos módulos
- Explicación de Camino A vs Camino B
- Convenciones usadas (callouts)
- Requisitos previos

### fundamentos.qmd (Fundamentos)
- Idea 1: Un LLM predice la siguiente palabra
- Idea 2: Por eso alucina
- Idea 3: Meta prompting
- Sección de profundización teórica (lectura posterior)
- Glosario de términos

### modulo-1.qmd (Módulo 1: 09:00-11:00)
- Preguntas de investigación (30 min) — Meta prompting
- Búsqueda bibliográfica (40 min) — Elicit, SciSpace, Perplexity
- Fichas de trabajo (35 min) — Organizar hallazgos

### modulo-2.qmd (Módulo 2: 11:15-13:00)
- Estructurar documento (25 min) — Markdown
- Redacción en español (30 min) — Borradores con IA
- Traducción al inglés (30 min) — Inglés académico
- Revisión final (20 min) — Checklist

### recursos.qmd (Recursos)
- Políticas de IA: Taylor & Francis, Elsevier, Springer Nature
- Lista de verificación de uso de IA
- Checklist de envío a revista
- Herramientas recomendadas
- Enlaces de referencia

---

## Cómo dejar comentarios para revisión

En cualquier archivo `.qmd`, usa comentarios HTML:

```
<!-- TODO: mejorar este ejemplo -->
<!-- REVISAR: no queda claro el flujo -->
<!-- AGREGAR: ejemplo práctico de uso -->
```

Estos comentarios no aparecen en el documento final.
