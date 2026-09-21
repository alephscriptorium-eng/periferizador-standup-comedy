# FORMATO DE SALIDA — ficha de etapa

Toda salida de un prompt de esta skill es una **ficha** markdown con estas secciones fijas y en este orden. Lo que no quepa en ellas no entra. Castellano de España; citas literales del libro entre comillas y con `[NN p.PP]`.

```
# E{N} · {nombre de la etapa} — {tema} / {aspecto}

Rol: {Investigador | Crítico | Redactor} · Prompt: {NN-slug} · Fecha: {dd-mmm-aaaa}
Entrada previa: {ficha anterior o "ninguna"}

## Entradas recibidas
{tema, aspecto, cuestión, audiencia, formato, recursos… tal como llegaron; lo que falte se marca "no dado"}

## Resultado
{las secciones propias que pide el prompt, en su orden}

## Trazabilidad
| Movimiento metodológico | Corpus | Etiqueta |
|---|---|---|
| {p. ej. "3 criterios de la cuestión: relevancia, claridad, tractabilidad"} | [06 p.30] | [V] |
| … | … | … |

## Fuera del corpus [H]
{todo movimiento, criterio o afirmación de método que el libro no respalda; "ninguno" si procede. Obligatoria aunque esté vacía.}

— turno del Crítico —

## Puerta G{N} — veredicto del Crítico
Veredicto: PASA / NO PASA / CONDICIONADO
Clave (afecta al veredicto): …
Secundario (no afecta): …
Para el autor: …

## Siguiente paso
{prompt NN o "cerrar"; qué entrega esta ficha a la siguiente}
```

## Reglas de forma

- **Regla:** una cita `[NN p.PP]` por movimiento, en la misma línea. Rango: `[14 p.101-103]`. Varias fuentes: `[06 p.30; 12 p.86]`.
- **Regla:** las listas numeradas del libro se reproducen completas (mismo número de ítems, misma numeración) y se citan una vez en la cabecera de la lista.
- **Regla:** las etiquetas van pegadas a la fila de trazabilidad: [V] verbatim o paráfrasis fiel · [A] anunciado sin desarrollo (o solo en el índice) · [P] extrapolación razonable del método · [H] aportación propia.
- **Regla:** contenido filosófico sobre el tema (hipótesis, ejemplos, contraejemplos propios) va con contexto de probabilidad ("plausible", "discutible", "el libro no lo respalda") y nunca con etiqueta [V]: [V] es solo para el método. Ese contenido NO se lista en "Fuera del corpus": esa sección es solo para **método** que el libro no respalda (pasos, criterios, reglas de decisión).
- **Regla:** la ficha no se cierra sin el bloque de puerta; si el mismo agente hace de Crítico, lo hace en un turno separado y lo dice.
- Longitud orientativa: 1-3 páginas por ficha; el argumento central puede ser más largo si el prompt lo exige.

## Ejemplo mínimo de fila de trazabilidad bien hecha

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Cuestión reformulada como "¿Cuál (de los x)…?" con opciones explícitas | [12 p.85-86] | [V] |
| Subopciones de relación epistemológica enumeradas por el agente | [12 p.87] | [H] (el libro calla) |
