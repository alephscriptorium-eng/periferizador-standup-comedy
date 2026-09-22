# PROMPT 04/09 — "EL ARGUMENTO CENTRAL" · Etapa E4 · Rol: Investigador (puerta G4: Crítico)

**Función:** seleccionar la respuesta por evaluación comparativa y construir el argumento central, los contraargumentos y las respuestas, declarando el tipo de argumento.
**Biblia:** `../protocolo-agentes.md` (leer íntegra) + `../corpus/00-indice.md`.
**Corpus a abrir:** `16-tipos-de-argumentos.md` (pp. 117-138), `14-argumentacion.md` (pp. 100-107), `20-estructura-del-articulo.md` (pp. 186-188, 210-212), `11-analisis-de-conceptos.md` (pp. 78-79).

## Entradas
- «espacio de respuestas» (ficha E3) y «análisis» (ficha E2)
- «tesis candidata(s)» que siguen vivas
- «audiencia» (para calibrar qué premisas son compartidas)

## Método (del corpus)

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Tesis negativa → contraejemplo o reducción al absurdo; tesis positiva → por análisis, por analogía, modelos, plausibilidad empírica, mejor explicación | [16 p.117] | [V] |
| Argumento analítico: explorar razones / consecuencias / causas / efectos de la hipótesis y de sus competidoras; listas A (a favor) y B (en contra); "entre mas alta en la lista… mas fuerte es el argumento" | [16 p.118-119] | [V] |
| Reducción al absurdo | [16 p.120-121] | [V] |
| "¡Un mal argumento es un mal argumento y punto!": un mal argumento a favor no es argumento en contra (Maná) | [16 p.121] | [V] |
| Analogía: caso A, ejemplo claro de B y de C lo más parecidos; buscar la diferencia o similitud que decida; no basta el mayor parecido | [16 p.121-123] | [V] |
| Modelos filosóficos: similar pero manejable; formalización como modelado; cómo saber si se formalizó bien | [16 p.123-137] | [V] |
| Plausibilidad empírica (genera hipótesis, no demuestra); mejor explicación (comparativa) | [16 p.137-138] | [V] |
| Argumentos trascendentales (una línea) | [16 p.138] | [A] |
| Cuerpo para un argumento a la mejor explicación: fenómeno neutral → posición establecida (ventajas / límites) → propuesta → comparación explícita | [20 p.210-212] | [V] |
| Contraejemplo: a-b-c; descomposición en cinco partes d-h; refutación simétrica | [14 p.104-105] | [V] |
| Anclaje psicológico: desanclar | [14 p.103] | [V] |
| Concepto puente: condición necesaria de X y suficiente de Y (ejemplo Hegel); premisas más claras y menos controvertidas que la conclusión | [14 p.106-107] | [V] |
| Refinar la hipótesis tras cada contraejemplo | [11 p.78-79; 14 p.107; 15 p.108] | [V] |
| Argumento central · contraargumentos contra la tesis y contra el argumento · respuestas | [20 p.186] | [V] |
| Evaluación comparativa pros / contras → conclusión conciliadora (empate) o no (vencedora) | [20 p.188] | [V] |
| Limitaciones negativas: objeciones no consideradas, presupuestos no justificados | [20 p.187] | [V] |
| "Selección del argumento más fuerte", "previsión de contra-argumentos", "reconocimiento de debilidades" | [01 p.3-4] | [A · solo índice] |

## Salida (secciones de la ficha)
1. **Evaluación comparativa** de las candidatas: pros / contras por hipótesis [20 p.188] y tesis elegida (o empate declarado).
2. **Argumento central**: tipo declarado [16 p.117]; premisas numeradas; para el analítico, qué ítem de la lista A alcanzó [16 p.119]; para la analogía, casos claros y diferencia decisiva [16 p.122]; para la mejor explicación, la secuencia de [20 p.210-212]; concepto puente si procede [14 p.106-107].
3. **Tabla de contraargumentos**: contra la tesis / contra el argumento [20 p.186], cada uno con respuesta; contraejemplos verificados a-b-c [14 p.104].
4. **Debilidades reconocidas** [20 p.187].
5. **Veredicto**: vencedora → prompt 07; empate → prompt 05.
6. Trazabilidad · Fuera del corpus [H] · Puerta G4.

## Puerta G4 (Crítico)
Lista literal en `../references/puertas-de-calidad.md` § G4. El Crítico ataca el argumento con las tres vías del libro: razones falsas / irrelevantes / insuficientes o crítica del contraejemplo [16 p.120, figura].

## Negativo específico
argumento sin tipo declarado · rechazar una tesis porque su defensor argumentó mal [16 p.121] · analogía por "se parece más" [16 p.122] · premisas más controvertidas que la conclusión [14 p.107] · contraargumentos sin respuesta · declarar "vencedora" con empate real

## Versión compacta (campo único)
> Actúa como Investigador según `protocolo-agentes.md` del paquete investigacion-filosofica. Espacio de respuestas: «espacio»; análisis: «análisis»; tesis candidatas: «candidatas»; audiencia: «audiencia». Abre `corpus/16-tipos-de-argumentos.md`, `14-argumentacion.md` (pp.100-107) y `20-estructura-del-articulo.md` (pp.186-188, 210-212). Evalúa comparativamente las candidatas (pros/contras) y di si hay vencedora o empate [20 p.188]. Construye el argumento central declarando su tipo [16 p.117]: analítico (listas A/B [16 p.118-119]), reductio [16 p.120-121], analogía con casos claros y diferencia decisiva [16 p.121-123], modelo [16 p.123-137], plausibilidad empírica o mejor explicación [16 p.137-138; 20 p.210-212]; identifica el concepto puente si es por análisis [14 p.106-107] y mantén premisas más claras que la conclusión [14 p.107]. Enumera contraargumentos contra la tesis y contra el argumento y respóndelos [20 p.186]; verifica todo contraejemplo con a-b-c [14 p.104]; recuerda que un mal argumento a favor no es argumento en contra [16 p.121]. Reconoce debilidades [20 p.187]. Ficha con Trazabilidad [NN p.PP] y "Fuera del corpus [H]". Luego "— turno del Crítico —": puerta G4 de `references/puertas-de-calidad.md` y veredicto; si hay empate, siguiente paso prompt 05, si no, prompt 07. Castellano de España, breve.
