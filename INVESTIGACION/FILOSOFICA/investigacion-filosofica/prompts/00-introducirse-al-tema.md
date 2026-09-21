# PROMPT 00/09 — "ENTRAR EN LA DISCUSIÓN" · Etapa E0 · Rol: Investigador

**Función:** entrar en una discusión filosófica ya empezada y dominar el aspecto del tema antes de plantear nada. Precondición de E1.
**Biblia:** `../protocolo-agentes.md` (leer íntegra) + `../corpus/00-indice.md`.
**Corpus a abrir:** `09-introduccion-y-dominio.md` (pp. 52-58), `10-cuestiones-filosoficas.md` (p. 59, consejos 8-11 de Young), `05-temas-centrales.md` (pp. 19-25), `03-conocimiento-e-investigacion.md` (pp. 13-18).

## Entradas
- «tema» (sustantivo: justicia, conocimiento, privacidad…)
- «rama» si se conoce (ética, epistemología, metafísica, filosofía política…) [05 p.20-24]
- «tiempo» disponible y «formato» final (trabajo de curso, artículo, tesis, ponencia)
- «fuentes» ya leídas, si las hay

## Método (del corpus)

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Integrarse a una discusión existente, no abrir una nueva: "es preferible – especialmente durante el período formativo – tratar de integrarse y contribuir a una discusión ya existente" | [09 p.53] | [V] |
| Enterarse de qué se discute: cuál es el tema · qué problemas / preguntas · cómo están conectados · qué opciones de respuesta se han ofrecido (cuáles descartadas y por qué, cuáles activas y cómo se han desarrollado) · qué problemas ya se han respondido y con qué respuesta | [09 p.53] | [V] |
| Tipos de fuente de entrada: curso o plática introductoria, libro de texto, survey, enciclopedia (SEP, IEP, SEFA); sus diferencias | [09 p.53-54] | [V] |
| Eventos: congresos, coloquios, talleres, seminarios, grupos de lectura; qué se obtiene de cada uno | [09 p.54-57] | [V] |
| Once consejos de Young para dominar un área (1-7 en p.58, 8-11 en p.59): reproducir completos | [09 p.58; 10 p.59] | [V] |
| Situar el tema en ramas / corrientes / doctrinas; ramas prácticas y teóricas, pura y aplicada | [05 p.20-24] | [V] |
| "no todo lo que hay que saber es filosofía": otras disciplinas implicadas | [03 p.17-18] | [V] |
| Leer, escribir, hablar y escuchar como habilidades del ciclo | [03 p.13-15] | [V] |

## Salida (secciones de la ficha)
1. **Mapa de la discusión**: tema · problemas y preguntas · conexiones · opciones vivas / descartadas (con por qué) / respondidas — siguiendo el orden del checklist [09 p.53].
2. **Posiciones principales en palabras propias**, cada una con un ejemplo propio y con "cómo sería vivir en un mundo donde fuera verdadera" (Young 4-6).
3. **Argumentos principales** de cada posición, "escribiendo como si creyeras que tuviera razón" (Young 8).
4. **Lista de lectura** ordenada: introductorio → survey → enciclopedia → artículos clave; y eventos donde se discute.
5. **Otras disciplinas** que hay que conocer [03 p.17-18].
6. Trazabilidad · Fuera del corpus [H] · Siguiente paso: prompt 01.

## Puerta
E0 no tiene puerta propia; el Crítico solo comprueba que los 11 consejos de Young están completos y que el mapa sigue el checklist de [09 p.53].

## Negativo específico
resumir la ortodoxia sin posiciones vivas y descartadas · "se considera" [20 p.209] · listas de lectura sin orden de entrada · inventar consejos que no están en Young

## Versión compacta (campo único)
> Actúa como Investigador según `protocolo-agentes.md` del paquete investigacion-filosofica. Tema: «tema»; rama: «rama»; formato: «formato»; tiempo: «tiempo». Abre `corpus/09-introduccion-y-dominio.md`, `corpus/10-cuestiones-filosoficas.md` (p.59) y `corpus/05-temas-centrales.md`. Produce una ficha E0 con: (1) mapa de la discusión siguiendo el checklist de [09 p.53] (tema, problemas, conexiones, opciones vivas/descartadas/respondidas); (2) posiciones en tus propias palabras con un ejemplo propio y "cómo sería vivir en ese mundo" [09 p.58]; (3) argumentos principales presentados como si fueran correctos [10 p.59]; (4) lista de lectura ordenada por tipo de fuente [09 p.53-54] y eventos [09 p.54-57]; (5) otras disciplinas implicadas [03 p.17-18]. Reproduce completos los 11 consejos de Young [09 p.58; 10 p.59]. Cita cada movimiento como [NN p.PP]; lo que el libro no respalde va en "Fuera del corpus [H]". Castellano de España, breve. Termina con "Siguiente paso: prompt 01".
