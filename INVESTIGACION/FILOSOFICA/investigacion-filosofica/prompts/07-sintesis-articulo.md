# PROMPT 07/09 — "ESCRIBIR EL ARTÍCULO" · Etapa E6 · Rol: Redactor (puerta G6: Crítico)

**Función:** convertir cuestión, tesis y argumento (fichas E4/E5) en un texto de investigación claro, estructurado y relevante: esqueleto, título, primer párrafo, términos, marco teórico, final.
**Biblia:** `../protocolo-agentes.md` (leer íntegra) + `../corpus/00-indice.md`.
**Corpus a abrir:** `18-sintesis-claridad-definiciones.md` (pp. 148-181), `19-intermezzos-b-c.md` (pp. 182-184), `20-estructura-del-articulo.md` (pp. 184-212), `21-relevancia-y-resumen.md` (pp. 213-214).

## Entradas
- ficha E4 (y E5 si hubo empate): cuestión, tesis, argumento central, contraargumentos y respuestas, debilidades
- «audiencia» ("¿A quién le serviría saber lo que has descubierto?" [18 p.150])
- «formato» (artículo / tesis / ensayo), «extensión», «medio» y sus normas

## Método (del corpus)

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Antes de escribir: pregunta, respuesta, argumento definidos | [18 p.149] | [V] |
| Tres criterios: claridad, estructura, relevancia | [18 p.149] | [V] |
| Audiencia: quién puede sacar provecho; investigadores de temas cercanos | [18 p.150, 157] | [V] |
| Efecto de justificación del esfuerzo: la oscuridad no es profundidad | [18 p.150] | [V] |
| Gramática: enunciados completos, correctos, simples | [18 p.152-153] | [V] |
| Clarificación de términos ("clarificar es menos que definir"); neologismos; metáforas | [18 p.153-157] | [V] |
| Oscuridad vs. dificultad; vértigo de la simplicidad | [18 p.158-159] | [V] |
| Definiciones: explícita, implícita / ostensiva, real / nominal, descriptiva / estipulativa / explicativa; cuándo definir | [18 p.159-173] | [V] |
| Otros consejos a-n (un mensaje por párrafo, ilustrar, no confrontar…) | [18 p.175-178] | [V] |
| Ejemplos y estudios de caso; marco teórico solo con herramientas que se usan | [18 p.178-179] | [V] |
| Evitar comparaciones "X en Fulano y Mengano" que solo narran el descubrimiento | [18 p.148] | [V] |
| Hurtado: claridad no es parquedad; Orwell: escribir mal | [19 p.182-184] | [V] |
| Seis reglas de orden | [20 p.184-185] | [V] |
| Esqueleto i-xv (introducción / cuerpo / final) | [20 p.185-188] | [V] |
| Checklist de ocho puntos | [20 p.188-189] | [V] |
| Cómo empezar: cinco ejemplos comentados (Salles, Danón, Rudy-Hiller, García Aguilar) | [20 p.189-196] | [V] |
| Título: informativo y atractivo; sin "estudios sobre"; frase mejor que lista; dice el método; sin subtítulo; heurística de interés | [20 p.197-200] | [V] |
| Croquis: entender 3 / aceptar 3; puntos de referencia; citas; supuestos compartidos; mini-intro y mini-conclusión; obviar lo obvio | [20 p.200-205] | [V] |
| Bautizar la tesis | [20 p.205-206] | [V] |
| Marco teórico: lo que se sabe, no lo que se dice; sin sociología ni "ad bacculum" | [20 p.208-209] | [V] |
| Cuerpo para la mejor explicación | [20 p.210-212] | [V] |
| Buen final (Maddy, Priest, Sorensen) | [20 p.212; 21 p.213] | [V] |
| Relevancia: "DI EXACTAMENTE TODO LO QUE DEBES DE DECIR, Y NADA MÁS"; tres objetivos; checklist 3×3 | [21 p.213-214; 22 p.215] | [V] |

## Salida (secciones de la ficha)
1. **Esqueleto i-xv rellenado** con una o dos líneas por elemento [20 p.185-188]; marca los que faltan.
2. **Título** elegido + dos alternativas, evaluados con la heurística de [20 p.197-200].
3. **Primer párrafo** redactado según el patrón de Salles [20 p.189-190]: debate, qué está en juego, pregunta, plan.
4. **Tabla de términos**: término · ¿clarificar o definir? · tipo de definición [18 p.153-173].
5. **Marco teórico**: solo argumentos precedentes que sirven de punto de partida [20 p.208-209].
6. **Final**: resultados, limitaciones negativas y positivas, futuro [20 p.186-188, 212; 21 p.213].
7. **Checklist de 8** [20 p.188-189] y **3×3** [21 p.214; 22 p.215] marcados.
8. Trazabilidad · Fuera del corpus [H] · Puerta G6 · Siguiente paso: prompt 08.

## Puerta G6 (Crítico)
Lista literal en `../references/puertas-de-calidad.md` § G6.

## Negativo específico
cambiar la tesis o añadir argumentos nuevos (eso es E4) · título con "estudios sobre" o subtítulo [20 p.197-199] · "se considera", "los más importantes" [20 p.209] · enunciados chorizo [18 p.153] · texto que narra cómo se descubrió en vez de argumentar [18 p.148] · confrontación [18 p.177] · divagar [21 p.214]

## Versión compacta (campo único)
> Actúa como Redactor según `protocolo-agentes.md` del paquete investigacion-filosofica. Ficha E4/E5: «ficha»; audiencia: «audiencia»; formato, extensión y medio: «formato», «extensión», «medio». Abre `corpus/18-sintesis-claridad-definiciones.md`, `19-intermezzos-b-c.md`, `20-estructura-del-articulo.md` y `21-relevancia-y-resumen.md`. Parte de pregunta, respuesta y argumento ya definidos [18 p.149] y evalúa todo con claridad, estructura y relevancia [18 p.149]. Rellena el esqueleto i-xv [20 p.185-188]; propone título y dos alternativas según [20 p.197-200]; redacta el primer párrafo con el patrón de Salles [20 p.189-190]; tabla de términos a clarificar o definir con tipo de definición [18 p.153-173]; marco teórico solo con lo que se sabe y sirve al argumento [20 p.208-209]; final con resultados, limitaciones negativas y positivas y futuro [20 p.186-188, 212; 21 p.213]; enunciados completos, correctos y simples [18 p.152-153]; sin confrontación [18 p.177]. Marca el checklist de ocho [20 p.188-189] y el 3×3 [21 p.214; 22 p.215]. No cambies la tesis ni añadas argumentos. Ficha con Trazabilidad [NN p.PP] y "Fuera del corpus [H]". Luego "— turno del Crítico —": puerta G6 de `references/puertas-de-calidad.md` y veredicto. Castellano de España, breve.
