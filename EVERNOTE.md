# Capacitación IA para Investigación Académica

## Resumen del proyecto

Taller de media jornada para el cuerpo académico de la Universidad de Aysén, enfocado en la integración de inteligencia artificial en procesos de investigación y publicación científica.

**Estado:** Finalizado

---

## Información del taller

- **Fecha:** 28 de enero 2026, 09:00-13:00
- **Lugar:** Sala D6, Campus Lillo, Universidad de Aysén
- **Audiencia:** Cuerpo académico
- **Facilitador:** José Cifuentes R.

---

## Entregables

### Sitio web (cuadernillo interactivo)
- **URL:** https://pituxcode.github.io/ia-investigacion/
- **Repositorio:** https://github.com/pituxcode/ia-investigacion
- **Tecnología:** Quarto Book publicado en GitHub Pages

### Contenido del cuadernillo
1. **Conectar** — Página con URL y QR para proyectar al inicio
2. **Bienvenida** — Objetivos, programa, convenciones, requisitos
3. **Fundamentos** — 3 ideas fuerza: predicción de palabras, alucinaciones, técnicas de prompting
4. **Módulo 1 (09:00-11:00)** — Preguntas de investigación, búsqueda bibliográfica (Elicit, SciSpace), fichas de trabajo
5. **Módulo 2 (11:15-13:00)** — Markdown, Quarto, LaTeX, redacción con IA, traducción al inglés, revisión final
6. **Recursos** — Políticas editoriales, checklists, herramientas recomendadas
7. **Referencias** — Bibliografía automática desde BibTeX

### PDF
- Archivo: `_book/IA-para-Investigación-Académica.pdf` (3.4 MB)
- Generado automáticamente con `quarto render`

---

## Objetivos de aprendizaje

Los participantes pueden:

1. Reconocer las consideraciones de revistas científicas sobre uso de IA en manuscritos
2. Identificar el potencial y limitaciones de la IA en diferentes etapas del proceso de investigación
3. Aplicar flujos de trabajo responsables con IA, respetando estándares éticos y editoriales
4. Utilizar herramientas de IA para traducción y corrección de textos académicos en inglés

---

## Estructura del proyecto

```
ia-investigacion/
├── _quarto.yml          # Configuración del libro
├── styles.css           # Estilos personalizados
├── copy-button.html     # Script para copiar código
├── references.bib       # Bibliografía BibTeX
│
├── conectar.qmd         # Página de conexión (URL + QR)
├── index.qmd            # Bienvenida
├── fundamentos.qmd      # Fundamentos teóricos
├── modulo-1.qmd         # Módulo 1
├── modulo-2.qmd         # Módulo 2
├── recursos.qmd         # Recursos y herramientas
├── references.qmd       # Referencias bibliográficas
│
├── assets/
│   ├── fundamentos/     # Imágenes: transformer, asíntota, Gemini
│   ├── modulo-2/        # Pipeline de Quarto
│   └── qr-code.png      # Código QR
│
├── _book/               # Salida generada (HTML + PDF)
│
└── Documentación interna:
    ├── AGENTS.md        # Herramientas y convenciones
    ├── ESTRUCTURA.md    # Detalle de archivos
    ├── CHECKLOG.md      # Registro de sesiones de trabajo
    ├── descripcion.md   # Descripción original del proyecto
    ├── gh-pages.md      # Documentación del deploy
    └── EVERNOTE.md      # Esta nota
```

---

## Herramientas utilizadas

- **Claude Code (Opus 4.5):** Asistente principal para desarrollo de contenidos
- **Quarto 1.8.27:** Sistema de publicación (HTML + PDF)
- **Git / GitHub:** Control de versiones y hosting
- **GitHub CLI:** Autenticación y gestión del repositorio
- **VS Code / Cursor:** Editor de texto
- **Python:** Cómputo científico integrado, generación de QR

---

## Flujo de deploy

```bash
# Previsualizar localmente
quarto preview

# Publicar a GitHub Pages
quarto publish gh-pages
```

El sitio se actualiza automáticamente en https://pituxcode.github.io/ia-investigacion/

---

## Historial de desarrollo

- **26 ene 2026 (Sesión 1):** Inicialización del proyecto, estructura base
- **27 ene 2026 (Sesión 2):** Mejora de fundamentos, imágenes, referencias
- **27 ene 2026 (Sesión 3):** Contenido nuevo en módulo 2, deploy a GitHub Pages
- **28 ene 2026:** Taller realizado

---

## Commits principales

```
b796cd3 Agrega licencia CC BY-NC-SA 4.0 al footer
82e3313 Actualiza documentación interna del proyecto
e9c9fe9 Agrega página de conexión con URL y código QR
c15ab2b Agrega texto plano, LaTeX, cómputo Python y revisión general
8ec1057 Corrige referencia rota y unifica formato de títulos
43259bc Reescribe módulo 1 y mejora fundamentos con iterative prompting
b7dbf82 Reorganiza estructura e integra prompts en módulos
2881ddb Mejoras de estructura y usabilidad del cuadernillo
3b70d34 Fase 1 completada: cuadernillo del taller de IA para investigación
```

---

## Licencia

Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)

---

## Notas de archivo

- **Última verificación:** 3 de febrero 2026
- **Estado de git:** Limpio, sincronizado con origin/main
- **Tareas pendientes:** Ninguna
- **Sitio web:** Activo en GitHub Pages

El proyecto se considera completo. El repositorio permanece público en GitHub para referencia futura.
