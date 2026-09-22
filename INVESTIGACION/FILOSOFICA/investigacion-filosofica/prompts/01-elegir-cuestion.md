# PROMPT 01/09 — "DE TEMA A CUESTIÓN" · Etapa E1 · Rol: Investigador (puerta G1: Crítico)

**Función:** pasar de un tema a un aspecto y de ahí a una cuestión bien formada, con hipótesis en competencia, evaluada por relevancia, claridad y tractabilidad.
**Biblia:** `../protocolo-agentes.md` (leer íntegra) + `../corpus/00-indice.md`.
**Corpus a abrir:** `06-de-que-trata-tu-investigacion.md` (pp. 25-42), `07-recursos-humanos-asesores.md` (pp. 47-48), `08-consideraciones-extra-tema.md` (pp. 49-51), `10-cuestiones-filosoficas.md` (pp. 59-68), `12-preguntas-cual.md` (pp. 85-86).

## Entradas
- «tema» y, si existe, «aspecto»
- «experiencia» concreta que motiva (la "sorpresa o molestia" [06 p.31]), si la hay
- «formato» (curso / artículo / tesis / proyecto / pieza de divulgación) y «medio» con sus normas [06 p.36-37]; si el medio no es académico (radio, streaming, prensa), sus normas de la casa hacen de "normas del medio" y se declaran como tales
- «recursos»: tiempo, conocimiento, información, materiales, atención, interés, humanos [06 p.39]
- ficha E0 si existe

## Método (del corpus)

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Análisis ("buscar qué decir") antes que síntesis ("cómo decirlo") | [06 p.25] | [V] |
| Niveles: tema → aspecto → cuestión → hipótesis en competencia → tesis (la tesis, solo al final) | [06 p.26-29; 07 p.47-48] | [V] |
| Explanandum antes que explanans: primero qué hay que explicar | [06 p.28] | [V] |
| "¿Por qué quieres estudiarlo?" en un enunciado breve | [06 p.29] | [V] |
| Abstraer del caso concreto comparando variantes (caso → casos similares → conceptos → relación → problema/pregunta/fenómeno) | [06 p.32-33] | [V] |
| Tres criterios: relevancia, claridad, tractabilidad | [06 p.30] | [V] |
| Relevancia: ¿hay debate? (ser justo y generoso con el adversario) y ¿qué se arriesga? | [06 p.30-31] | [V] |
| Borracho y farol; "solución sin problema" | [06 p.33-35] | [V] |
| Fraser: doble obstáculo de las preguntas inexploradas | [06 p.35] | [V] |
| Relevancia restringida: normas del medio, integridad ante financiadores | [06 p.35-37] | [V] |
| Resumen parcial (4 viñetas) | [06 p.37-38] | [V] |
| Claridad: pseudo-problemas (Moore, Carnap, Wittgenstein, Sorensen) | [06 p.38] | [V] |
| Tractabilidad: quiénes somos (humanidad / equipo), siete recursos, disponibilidad | [06 p.39-42] | [V] |
| Típico / básico / marginal; clásico / nuevo | [08 p.49-51] | [V] |
| Sustantivo → adjetivo / verbo / adverbio y complementos; tesis "sólo / todas las personas"; quintupartición modal | [10 p.60-67] | [V] |
| Determinables: buscar casos concretos | [10 p.67-68] | [V] |
| Tipos de pregunta por especificidad (sí/no, qué/quién, cómo, por qué) | [07 p.47-48; 12 p.85] | [V] |
| Forma general "¿Cuál (de los x)…?" con opciones explícitas | [12 p.85-86] | [V] |
| Cómo ponderar relevancia, claridad y tractabilidad cuando chocan | el libro calla [06 p.30] | [H] |

## Salida (secciones de la ficha)
1. **Cadena** tema → aspecto → cuestión, con el "por qué quiero estudiarlo" en una línea [06 p.29].
2. **Cuestión final** en forma "¿Cuál (de los x)…?" con la lista de opciones [12 p.86].
3. **Tabla de hipótesis en competencia** (2-5 filas) [07 p.47], sin elegir ninguna.
4. **Ficha de criterios**: relevancia (¿hay debate? / ¿qué se arriesga?), claridad (¿pseudo-problema?), tractabilidad (7 recursos × disponibilidad) con veredicto por criterio.
5. **Encaje**: típico/básico/marginal, clásico/nuevo [08 p.49-51]; normas del medio [06 p.36-37].
6. **Recursos que faltan** y cómo obtenerlos.
7. Trazabilidad · Fuera del corpus [H] · Puerta G1 · Siguiente paso: prompt 02 (o 06 si hay que pedir recursos).

## Puerta G1 (Crítico)
Lista literal en `../references/puertas-de-calidad.md` § G1: debate · riesgo · motivación concreta · no solución sin problema · no pseudo-problema · recursos · resumen parcial · forma ¿cuál? · hipótesis en competencia sin tesis previa.

## Negativo específico
tesis antes que cuestión [07 p.48] · cuestión sin opciones · "es interesante" sin decir qué se arriesga · preguntas centrales abstractas sin aterrizar en enunciados [10 p.59-60] · ignorar las normas del medio

## Versión compacta (campo único)
> Actúa como Investigador según `protocolo-agentes.md` del paquete investigacion-filosofica. Tema: «tema»; aspecto: «aspecto»; experiencia que lo motiva: «experiencia»; formato y medio: «formato», «medio»; recursos: «recursos». Abre `corpus/06-de-que-trata-tu-investigacion.md`, `07-recursos-humanos-asesores.md` (pp.47-48), `08-consideraciones-extra-tema.md`, `10-cuestiones-filosoficas.md` (pp.59-68) y `12-preguntas-cual.md` (pp.85-86). Produce una ficha E1: (1) cadena tema → aspecto → cuestión con el "por qué" en una línea [06 p.26-29]; (2) cuestión en forma "¿Cuál (de los x)…?" con opciones explícitas [12 p.85-86]; (3) tabla de hipótesis en competencia sin elegir tesis [07 p.47-48]; (4) evaluación por relevancia (¿hay debate?, ¿qué se arriesga? [06 p.30-31]; no "solución sin problema" [06 p.34-35]), claridad (¿pseudo-problema? [06 p.38]) y tractabilidad (siete recursos y disponibilidad [06 p.39-42]); (5) encaje típico/básico/marginal [08 p.49-51] y normas del medio [06 p.36-37]; (6) recursos que faltan. Cita cada movimiento [NN p.PP]; lo no respaldado va en "Fuera del corpus [H]". Después, en turno rotulado "— turno del Crítico —", pasa la puerta G1 con la lista de `references/puertas-de-calidad.md` y da veredicto PASA / NO PASA / CONDICIONADO. Castellano de España, breve.
