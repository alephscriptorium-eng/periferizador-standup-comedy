MATERIAL ORIGINAL: `MetodosdeInvestigación2026.pdf` (Axel Arturo Barceló Aspeitia, *Introducción a la Investigación Filosófica*, borrador de septiembre 2026, 228 pp., ~65.000 palabras, castellano de México; no versionado en git, `*.pdf` en `.gitignore`)
REF: Barceló, A. A. (2026). *Introducción a la Investigación Filosófica* [borrador, comentarios bienvenidos]. arturobarceloa@filos.unam.mx
---

COMENTARIO DE PARTIDA (sesión 21-sep-2026):

# EL MÉTODO ANTES QUE LA OCURRENCIA

Barceló defiende que investigar en filosofía no es don de superdotados sino hábito adquirible: elegir una cuestión relevante, clara y tratable; analizar los conceptos hasta sus condiciones necesarias y suficientes; enumerar todas las respuestas posibles; argumentar y buscar contraejemplos; escribir claro, estructurado y sin sobrar una palabra; dictaminar con generosidad. El libro se ha transcrito literalmente (erratas incluidas, marcas `[p.N]` en cada página, figuras extraídas y descritas) y sobre él se ha montado un paquete de agentes que **no inventan método**: cada movimiento cita fichero y página, y lo que el libro calla se declara aparte. El paquete es una skill de Claude Code autocontenida.

# ÍNDICE DE LA CARPETA

- `MetodosdeInvestigación2026.pdf` — fuente. Extracción con `pdftotext` (poppler) por páginas; figuras con `pdfimages` y recortes de `pdftoppm`.
- `investigacion-filosofica/` — **paquete final = skill de Claude Code**. Para activarla, copiar o enlazar esta carpeta en `.claude/skills/` (del proyecto o del usuario).
  - `SKILL.md` — punto de entrada: cuándo usarla, flujo E0-E8, roles, etiquetas, atajos.
  - `protocolo-agentes.md` — la "biblia": adhesión al corpus, reglas, etiquetas `[V]/[A]/[P]/[H]`, etapas, roles, puertas G1-G7, negativo y prohibido.
  - `corpus/00-indice.md` — mapa del libro: tabla de capítulos con páginas y métodos, índice de conceptos → `[NN p.PP]`, lagunas y erratas, convención de cita.
  - `corpus/01…23-*.md` — transcripción literal en 23 ficheros (portada e índice; introducción; conocimiento e investigación; intermezzo A; temas centrales; de qué trata tu investigación; asesores; consideraciones extra; introducción y dominio; cuestiones filosóficas; análisis de conceptos; preguntas ¿cuál?; proyectos; argumentación; explicar por qué; tipos de argumentos; resolver paradojas; síntesis y claridad; intermezzos B y C; estructura del artículo; relevancia y resumen; exposición oral y dictamen; bibliografía).
  - `corpus/img/` — 16 figuras PNG (espiral comunicativa, habilidades comunicativas, ciclo de la investigación, origen de los temas, del caso a la investigación, hechos y enunciados, pelotas, plano cartesiano, Venn ×2, concepto puente, tipos de argumentos, túnel de viento, modelo ×2, formulaciones de Salles), cada una con descripción textual en el corpus.
  - `prompts/00…09-*.md` — diez plantillas que despliegan los métodos sobre un tema: entrar en la discusión, elegir cuestión, análisis conceptual, espacio de respuestas, argumentar, tercera opción, proyecto, síntesis/artículo, dictaminar, exposición oral. Cada una con tabla método → página, salida fija y versión compacta de campo único.
  - `references/` — `flujo-de-trabajo.md` (etapas y entregas), `puertas-de-calidad.md` (listas literales del libro para el Crítico), `formato-de-salida.md` (ficha), `erratas-y-lagunas.md` (E1-E9 y silencios del libro).
- `prueba-E1-privacidad.md` — prueba de humo de la skill: ficha E1 (prompt 01) sobre «privacidad frente a agentes de IA que negocian por ti», puerta G1 CONDICIONADO. 33 citas verificadas.
- `prueba-E7-dictamen-privacidad.md` — dictamen (prompt 08) de esa ficha: recomendación CONDICIONAR, G7 PASA. Sus observaciones ya están aplicadas a prompts 01/08, protocolo, plantilla y SKILL.md.

Verificación hecha (21-sep-2026): marcas `[p.1]`…`[p.228]` presentes una vez cada una (páginas compartidas 19, 25, 139, 182, 184 con `· cont.`); comparación de bolsas de palabras PDF completo vs. markdown: 240 tokens de 64.955 sin correspondencia (0,37 %), todos etiquetas de diagramas sustituidas por figura + descripción y ligaduras "fi" restauradas; todas las imágenes referenciadas existen.

Pendiente: (1) cotejar a ojo contra el PDF la anidación de las listas de pp. 53 y 58 (viñetas sin sangría en la extracción); (2) el libro es un borrador: si el autor publica una versión nueva, repetir la extracción y actualizar páginas en `00-indice.md`, `protocolo-agentes.md`, `prompts/` y `references/`; (3) llevar la ficha E1 de privacidad por E2-E7 hasta una pieza emitible; (4) si se quiere usar la skill desde Claude Code, enlazarla: `ln -s ../../INVESTIGACION/FILOSOFICA/investigacion-filosofica .claude/skills/investigacion-filosofica`.
