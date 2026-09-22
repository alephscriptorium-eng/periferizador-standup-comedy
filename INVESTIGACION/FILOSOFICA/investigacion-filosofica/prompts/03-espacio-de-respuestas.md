# PROMPT 03/09 — "¿CUÁL DE LOS X?" · Etapa E3 · Rol: Investigador (puerta G3: Crítico)

**Función:** convertir la cuestión en un "¿cuál (de los x)?" con opciones exhaustivas, ubicar el debate en las cuatro regiones del espacio lógico y explorar cada hipótesis sin elegir aún.
**Biblia:** `../protocolo-agentes.md` (leer íntegra) + `../corpus/00-indice.md`.
**Corpus a abrir:** `12-preguntas-cual.md` (pp. 85-89), `14-argumentacion.md` (pp. 100-103), `16-tipos-de-argumentos.md` (pp. 118-119), `15-explicar-por-que.md` (pp. 108-116, solo si la pregunta es "¿por qué?"), `07-recursos-humanos-asesores.md` (p. 47).

## Entradas
- «cuestión» (ficha E1) y «conceptos» C1, C2 con sus condiciones (ficha E2)
- «hipótesis en competencia» ya enumeradas

## Método (del corpus)

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Cuatro tipos de pregunta (sí/no, ¿cuál?, ¿cómo?, ¿por qué?) y su reducción al tipo 2 | [12 p.85-86] | [V] |
| "¿Por qué x?" desenredado: ¿cuál es la razón / la causa / la forma / la manera? | [12 p.85] | [V] |
| La cláusula "de los x" fija el tipo de respuesta aceptable: opciones explícitas | [12 p.86] | [V] |
| Seis tipos de relación entre dos nociones | [12 p.86] | [V] |
| Subrelaciones metafísicas 2.1-2.6 (causal, implicación, identidad, pertenencia, subsunción, incompatibilidad, complejas) | [12 p.87-88] | [V] |
| Subopciones de relación conceptual / lógica / epistemológica | el libro calla [12 p.87] | [H] |
| Universal necesario vs. existencial negativo como forma típica del debate | [14 p.100] | [V] |
| Plano cartesiano / Venn: cuatro regiones; vacía → universal, no vacía → existencial; tabla región / contenido / forma / enunciado | [14 p.101-103] | [V] |
| Hipótesis en competencia como guía de la investigación | [07 p.47] | [V] |
| Por cada hipótesis: razones (5), consecuencias (6), causas (7), efectos (8); y el análisis simultáneo de su negación o competidoras | [16 p.118-119] | [V] |
| Buscar entre causas/razones algo tautológico, obvio, verdadero, sencillo, intuitivo; entre consecuencias/efectos algo contradictorio, absurdo, falso, complicado, contraintuitivo | [16 p.119] | [V] |
| Si es "¿por qué?": certezas fundamentales (normas, confianzas, necesidades), dos comparaciones y variantes | [15 p.109-110] | [V] |
| Estructura del argumento escéptico y sus cuatro tipos de respuesta | [15 p.110-111] | [V] |
| Explicación funcional, holista, historicista; fundacionismo | [15 p.111-116; 16 p.117] | [V] |
| "Análisis lógico: exploración de cada respuesta posible a-d" | [01 p.3] | [A · solo índice] |

## Salida (secciones de la ficha)
1. **Cuestión en forma "¿Cuál (de los x)…?"** y lista cerrada de opciones [12 p.86]; si era "¿por qué?", las cuatro lecturas [12 p.85].
2. **Tipo de relación** (1-6) y subrelación [12 p.86-88]; lo no metafísico, en Fuera del corpus [H].
3. **Tabla de cuatro regiones** para C1/C2: qué región afirma vacía o no vacía cada hipótesis y la forma del enunciado resultante [14 p.101-103].
4. **Ficha por hipótesis** (y por su negación): razones · consecuencias · causas · efectos [16 p.118-119], señalando qué encontró en las listas A/B [16 p.119].
5. **Si es "¿por qué?"**: certezas en juego, respuesta al escéptico, tipo de explicación elegido [15 p.109-116].
6. **Candidatas a tesis** (sin elegir): cuáles quedan vivas y por qué.
7. Trazabilidad · Fuera del corpus [H] · Puerta G3 · Siguiente paso: prompt 04.

## Puerta G3 (Crítico)
Lista literal en `../references/puertas-de-calidad.md` § G3. El Crítico comprueba que la lista de opciones es exhaustiva (¿falta la región vacía / no vacía complementaria?) y que no hay tesis elegida.

## Negativo específico
"¿por qué?" sin desenredar · opciones implícitas · una sola hipótesis explorada · saltarse la negación · elegir tesis en E3 [07 p.48] · presentar subopciones no metafísicas como del libro

## Versión compacta (campo único)
> Actúa como Investigador según `protocolo-agentes.md` del paquete investigacion-filosofica. Cuestión: «cuestión»; conceptos: «C1», «C2»; hipótesis en competencia: «hipótesis». Abre `corpus/12-preguntas-cual.md`, `14-argumentacion.md` (pp.100-103), `16-tipos-de-argumentos.md` (pp.118-119) y, si la pregunta es "¿por qué?", `15-explicar-por-que.md`. Reformula la cuestión como "¿Cuál (de los x)…?" con opciones explícitas [12 p.85-86]; clasifica la relación entre nociones (seis tipos y subrelaciones metafísicas 2.1-2.6 [12 p.86-88]; las demás subopciones el libro no las da: márcalas [H]); construye la tabla de cuatro regiones y di qué región afirma vacía o no vacía cada hipótesis [14 p.101-103]; para cada hipótesis y su negación explora razones, consecuencias, causas y efectos [16 p.118-119] buscando lo tautológico / obvio / verdadero / sencillo / intuitivo o lo contradictorio / absurdo / falso / complicado / contraintuitivo [16 p.119]; si es "¿por qué?", desenreda las cuatro lecturas [12 p.85] y elige tipo de explicación [15 p.111-116]. No elijas tesis [07 p.48]. Ficha con Trazabilidad [NN p.PP] y "Fuera del corpus [H]". Luego "— turno del Crítico —": puerta G3 de `references/puertas-de-calidad.md` y veredicto. Castellano de España, breve.
