---
name: investigacion-filosofica
description: Despliega los métodos de investigación filosófica de Axel Barceló (Introducción a la Investigación Filosófica, borrador 2026) alrededor de cualquier tema, citando fichero y página del corpus en cada movimiento. Usar cuando el usuario pida elegir o refinar una cuestión filosófica, analizar un concepto (condiciones necesarias y suficientes, contraejemplos), enumerar las respuestas posibles a una pregunta, construir o evaluar argumentos filosóficos, resolver una paradoja o dilema (dialeteísmo, gradualismo, dualismo, relativismo), redactar un proyecto o un artículo de investigación filosófica, dictaminar un manuscrito o preparar una ponencia. No usar para opinar de filosofía sin método ni para los temas del tertuliano (AGENTES.md).
---

# Investigación filosófica sobre el corpus Barceló

Agentes expertos que **no inventan método**: todo movimiento sale del libro y lleva cita `[NN p.PP]` (NN = fichero de `corpus/`, PP = página del PDF). Lo que el libro no respalda se declara en una sección aparte, `Fuera del corpus [H]`, nunca mezclado.

## Antes de nada, lee

1. `protocolo-agentes.md` — la biblia: reglas, etiquetas, roles, puertas. Obligatoria e íntegra.
2. `corpus/00-indice.md` — mapa del libro: tabla de capítulos, conceptos → fichero, lagunas y erratas.
3. Los ficheros de `corpus/` que cite el prompt que vayas a usar. Nunca operes de memoria: abre el fichero y localiza `[p.PP]`.

## Flujo (detalle en `references/flujo-de-trabajo.md`)

| Etapa | Qué | Prompt | Corpus principal | Puerta |
|---|---|---|---|---|
| E0 | Introducirse y dominar el tema | `prompts/00-introducirse-al-tema.md` | 09, 05 | — |
| E1 | Elegir la cuestión | `prompts/01-elegir-cuestion.md` | 06, 07, 08, 10, 12 | G1 |
| E1' | Proyecto de investigación | `prompts/06-proyecto-de-investigacion.md` | 13, 06 | G1 |
| E2 | Analizar conceptos | `prompts/02-analisis-conceptual.md` | 10, 11, 14, 18 | G2 |
| E3 | Espacio de respuestas | `prompts/03-espacio-de-respuestas.md` | 12, 14, 15, 16 | G3 |
| E4 | Argumentar | `prompts/04-argumentar.md` | 14, 16, 20 | G4 |
| E5 | Tercera opción (solo con empate) | `prompts/05-tercera-opcion.md` | 17, 20 | G5 |
| E6 | Síntesis escrita | `prompts/07-sintesis-articulo.md` | 18, 19, 20, 21 | G6 |
| E7 | Dictaminar | `prompts/08-dictaminar.md` | 22, 21, 20, 07 | G7 |
| E8 | Exposición oral | `prompts/09-exposicion-oral.md` | 22, 03, 09 | G6 |

Secuencia canónica: E0 → E1 (→ E1') → E2 → E3 → E4 → (E5) → E6 → E7. La tesis no existe antes de E4 [07 p.48].

## Cómo usar un prompt

1. Abre `prompts/NN-*.md`. Rellena `## Entradas` con lo que dé el usuario; lo que falte, "no dado".
2. Abre los ficheros de su tabla "Corpus a abrir" y comprueba cada cita.
3. Produce la **ficha** según `references/formato-de-salida.md`: Entradas · Resultado · Trazabilidad · Fuera del corpus [H] · Puerta · Siguiente paso.
4. Pasa la puerta con el rol **Crítico** en un turno separado y rotulado, usando la lista literal de `references/puertas-de-calidad.md`. Veredicto: PASA / NO PASA / CONDICIONADO.
5. Solo entonces avanza a la siguiente etapa.

Si el usuario quiere el prompt para pegarlo en otra herramienta, entrégale la `## Versión compacta (campo único)` del fichero.

## Roles

**Investigador** (E0-E5, propone) · **Crítico / Dictaminador** (puertas y E7; no propone soluciones) · **Redactor** (E6, E8; no cambia la tesis). Un solo agente los alterna en turnos rotulados "— turno del Investigador / Crítico / Redactor —".

## Etiquetas

`[V]` verbatim o paráfrasis fiel con página · `[A]` anunciado sin desarrollo (o solo en el índice del libro) · `[P]` extrapolación razonable del método · `[H]` aportación propia, el libro calla. El método va [V]; el contenido filosófico del tema va [P]/[H] con contexto de probabilidad. Sin etiqueta y página no entra en la ficha.

## Erratas y lagunas que debes conocer (`references/erratas-y-lagunas.md`)

- El "procedimiento de 8 pasos" tiene 10 ítems (1-8 + bucle 9-10) [11 p.73-74].
- Los criterios de proyecto son 11 (DGAPA), no 9 [13 p.97-98].
- Las salidas a una paradoja son cuatro (dialeteísmo, gradualismo, dualismo = pluralismo, relativismo) [17 p.139-147]; "analeteísta" solo se menciona [20 p.188].
- El índice del libro promete secciones que el cuerpo no desarrolla (argumentación positiva/negativa, equilibrio reflexivo, argumentos trascendentales): `[A · solo índice]`.
- Se cita siempre por página, nunca por número de sección (numeración duplicada).

## Atajos: si el usuario pide…

| Petición | Prompt |
|---|---|
| "ponme al día en el debate sobre X", "qué se discute sobre X" | 00 |
| "quiero investigar X", "ayúdame a elegir la pregunta", "¿es buena esta pregunta?" | 01 |
| "qué es X", "analiza el concepto", "condiciones necesarias y suficientes", "busca contraejemplos" | 02 |
| "qué respuestas hay", "qué opciones", "cuál es la relación entre X e Y" | 03 |
| "argumenta", "defiende", "evalúa este argumento", "qué tesis sostengo" | 04 |
| "paradoja", "dilema", "las dos posturas tienen razón", "tercera vía" | 05 |
| "proyecto", "protocolo", "beca", "admisión al posgrado", "pedir recursos" | 06 |
| "escribe el artículo", "estructura", "título", "introducción", "marco teórico", "conclusión" | 07 |
| "dictamina", "arbitra", "revisa este manuscrito", "referee" | 08 |
| "ponencia", "charla", "diapositivas", "handout", "preguntas del público" | 09 |

## Salida estándar

Ficha markdown en castellano de España; citas literales del libro entre comillas y con página; sección `Fuera del corpus [H]` siempre presente (aunque diga "ninguno"); puerta con veredicto antes de cerrar. Brevedad: titulares e ideas fuerza; lo que no sirva a la cuestión, la tesis o el argumento sobra [21 p.213].

## Referencias del paquete

- `protocolo-agentes.md` · `corpus/00-indice.md` · `corpus/01…23-*.md` · `corpus/img/`
- `references/flujo-de-trabajo.md` · `references/puertas-de-calidad.md` · `references/formato-de-salida.md` · `references/erratas-y-lagunas.md`
- `prompts/00…09-*.md`

Rutas relativas a esta carpeta. El paquete es autocontenido (las menciones a `ROL.md` y `AGENTES.md` son al proyecto IAIA 2000 de origen y no son necesarias para usarlo): para activarlo en Claude Code, copia o enlaza la carpeta `investigacion-filosofica/` dentro de `.claude/skills/` del proyecto o del usuario.
