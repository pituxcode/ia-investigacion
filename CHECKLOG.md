# Registro de Cambios (CHECKLOG)

## 2026-01-26 | Sesión 1: Inicialización del proyecto

### Contexto
- Taller programado para el 28 de enero 2026
- Dos jornadas de preparación disponibles (26-27 enero)

### Acciones realizadas
- [x] Inicialización del repositorio Git
- [x] Creación de AGENTS.md con estructura del proyecto
- [x] Creación de CHECKLOG.md para seguimiento
- [x] Revisión de documentos base (descripcion.md, programa-taller.pdf)
- [x] Eliminado programa-inicial.md (reemplazado por PDF oficial)

### Plan de trabajo propuesto

#### Jornada 1 (Hoy - 26 enero): Documentación base
- [ ] Crear estructura de carpetas
- [ ] Documentar Módulo 1: Marco ético y escritura aumentada
  - [ ] Contenido sobre políticas institucionales de IA
  - [ ] Guía de prompt engineering académico
  - [ ] Estructura IMRyD con IA
- [ ] Definir prompts para Actividad práctica 1 (lista de verificación ética)
- [ ] Definir prompts para Actividad práctica 2 (estructura IMRyD)

#### Jornada 2 (Mañana - 27 enero): Completar documentación y presentación
- [ ] Documentar Módulo 2: Pulido, Inglés y Envío
  - [ ] Comparativa de herramientas de traducción
  - [ ] Secuencia de revisión con IA
- [ ] Definir prompts para Actividades 3, 4 y 5
- [ ] Extraer presentación desde documentación
- [ ] Preparar materiales de apoyo para participantes

### Estado actual
**Pausado**: Proyecto inicializado, estructura lista, plan validado

### Próxima acción (post-almuerzo)
Comenzar documentación del Módulo 1: Marco ético y escritura aumentada

### Resumen del programa oficial (programa-taller.pdf)

**Módulo 1 (09:00-11:00)**: Marco ético y escritura aumentada
- Política y ética (política institucional, copyright, propiedad intelectual)
- Prompt engineering académico (estructura IMRyD)
- Uso responsable de IA en publicaciones indexadas
- Herramientas de búsqueda bibliográfica con IA (Elicit, Scispace)
- Demostración de flujo de trabajo

**Módulo 2 (11:15-13:00)**: Pulido, Inglés y Envío
- IA para inglés académico (DeepL Write, Grammarly, Gemini)
- Lenguajes de marcado (Markdown, LaTeX, Typst)
- Revisión final para envío de manuscrito

---

## 2026-01-27 | Sesión 2: Revisión y mejora de fundamentos

### Contexto
- Taller programado para mañana (28 enero)
- Cuadernillo (Fase 1) ya completado en sesión anterior
- Esta sesión se dedicó a revisar y enriquecer el capítulo de fundamentos

### Acciones realizadas

#### Sección "Un LLM predice la siguiente palabra"
- [x] Nueva subsección "IA generativa: más que texto" con tabla de tipos de modelos (lenguaje, imagen, audio, video, multimodal)
- [x] Callout sobre Gemini como caso multimodal y mención de Nano Banana (modelos de imagen de Google)
- [x] Nueva subsección "Dos formas de usar un modelo" con tabla comparativa asistente web vs CLI/editor
- [x] Nueva subsección "La arquitectura transformer" con explicación del mecanismo de atención
- [x] Ejemplo de desambiguación con la palabra "banco"
- [x] Imagen del Transformer Explainer descargada (`assets/fundamentos/transformer-explainer.png`) y referenciada con callout de demostración en vivo
- [x] Subsección "De la arquitectura a la predicción" conectando transformer con predicción de palabras
- [x] Columna "Genera" simplificada a "Texto y código" en tabla de modelos de lenguaje

#### Sección "Por eso alucina"
- [x] Nueva subsección "Por qué las alucinaciones son inevitables" basada en artículo de OpenAI (Kalai et al., 2025)
- [x] Tres puntos clave: patrones vs verdades, hechos sin patrón, evaluaciones que premian adivinar
- [x] Gráfico de asíntota generado con matplotlib (`assets/fundamentos/asintota-alucinaciones.png`)
- [x] "Autoritativas" reemplazado por "Están bien redactadas y usan un tono formal que inspira confianza"
- [x] Punto adicional en callout: "El modelo no sabe que no sabe"
- [x] Imagen del paper de OpenAI descartada (confusa para la audiencia)
- [x] Referencia BibTeX agregada para Kalai et al. (2025)

#### Numeración y estructura
- [x] Eliminada numeración de títulos en las tres ideas fuerza (se usan solo jerarquías de encabezados)

#### Glosario
- [x] Nuevos términos: "Transformer", "Atención"
- [x] Definición de LLM actualizada para mencionar arquitectura transformer

#### Configuración
- [x] `toc-depth` aumentado de 2 a 4 en `_quarto.yml`
- [x] `toc-expand` probado y revertido (se mantiene comportamiento colapsable)

### Pendiente para próxima sesión

#### Inmediato (fundamentos)
- [ ] **Buscar e insertar imagen de Gemini web** (interfaz de chat en gemini.google.com) — la imagen del CLI ya está lista (`assets/fundamentos/gemini-cli.png`)
- [ ] Insertar ambas imágenes en la subsección "Dos formas de usar un modelo"
- [ ] Completar placeholder de contacto en `modulo-2.qmd`: "[Información de contacto del facilitador o unidad organizadora]"

#### Revisión de otros capítulos
- [ ] Revisar `modulo-1.qmd` con el mismo nivel de detalle
- [ ] Revisar `modulo-2.qmd` con el mismo nivel de detalle
- [ ] Revisar `recursos.qmd`

#### Producción final
- [ ] Render final del PDF con `quarto render`
- [ ] Commit de todos los cambios

### Estado actual
**En progreso**: Fundamentos mejorado sustancialmente. Falta una imagen (Gemini web) y revisión del resto de capítulos.

---
