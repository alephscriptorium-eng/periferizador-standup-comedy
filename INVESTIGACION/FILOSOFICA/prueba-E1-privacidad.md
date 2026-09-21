# E1 · Elegir la cuestión — privacidad / privacidad frente a agentes de IA que negocian en nombre de las personas

Rol: Investigador (puerta G1: Crítico, turno aparte) · Prompt: 01-elegir-cuestion · Fecha: 21-sep-2026
Entrada previa: ninguna (E0 no ejecutada; el dosier de `TEMAS/privacidad/info.md` hace de sustituto parcial, ver Fuera del corpus)

— turno del Investigador —

## Entradas recibidas
- Tema: «privacidad».
- Aspecto: «privacidad frente a agentes de IA que negocian en nombre de las personas».
- Experiencia que motiva: hilo de X de @gakonst (19-sep-2026, 20:45) "how dead privacy is from here on forward"; réplica de Vitalik Buterin (~21:20) "It's only dead if you give up"; réplica de Lukas Helminger "ser privacy maxi ya no tendrá efecto sobre tu propia privacidad"; cierre de TheHackerStyle ep. 10 "esto se juega en lo colectivo". Contexto de la semana en `info.md`: Muse (agente de Meta que pide Gmail, banco y báscula, nº 1 del App Store), primer ataque de un agente registrado por la AEPD, tres investigadores dentro del repositorio de OpenAI con Claude Opus 5 por <3.000 $ en 72 h.
- Formato: pieza breve para un programa de radio/streaming sobre IA (no está entre los formatos que lista el prompt: curso / artículo / tesis / proyecto).
- Medio: "sin normas académicas". Las normas que sí rigen son las de la casa (`ROL.md`, fact-check, etiquetas [V]/[H]).
- Recursos: una tarde, una persona, sin acceso a bibliotecas.
- Ficha E0: no dada.

## Resultado

### 1. Cadena tema → aspecto → cuestión
- **Tema** (sustantivo, tema cotidiano con dimensión filosófica [06 p.27]): privacidad. Explanandum: la privacidad como fenómeno que hay que explicar; "agente", "conector", "presupuesto de ataque" son explanans, conceptos de la explicación [06 p.28].
- **Aspecto** (cualificación del sustantivo [06 p.28-29]): la privacidad *cuando alguien —un agente de IA— decide o negocia por ti* con acceso a tus datos. No el aspecto técnico (cifrado) ni el jurídico (RGPD) sino el de la delegación.
- **Por qué quiero estudiarlo, en una línea** [06 p.29]: me molesta que dos personas que comparten el diagnóstico (el agente útil necesita todos tus datos) saquen sentencias opuestas —"muerta" / "solo si te rindes"— y quiero saber qué es lo que realmente disputan.
- **Del caso particular a la pregunta** [06 p.32-33], comparando variantes del caso (tuit + Muse):
  - Muse *recoge* datos vs. Muse *negocia* con ellos por ti → ¿cambia algo que el agente actúe, no solo que sepa?
  - El mismo agente ejecutado en local bajo control del usuario vs. en la nube de un tercero → ¿la privacidad depende de quién ejecuta?
  - Delegar en un agente de IA vs. delegar en un gestor o abogado humano que también lo sabe todo → ¿por qué no decimos que la privacidad murió con el abogado?
  - Esfuerzo individual ("privacy maxi") vs. decisión colectiva (Helminger, THS) → ¿de quién depende la privacidad de uno?
  - Conceptos abstraídos: **privacidad** y **delegación** (decidir en nombre de otro). Relación buscada: qué relación hay entre delegar decisiones en un agente de IA y conservar la privacidad.
- Paso sustantivo → adjetivo [10 p.60-62]: "privacidad" → "privado": ¿qué tipo de cosas pueden ser privadas cuando un agente decide por ti: los datos, las decisiones, las dos? Deja preparadas tesis "sólo / todas" [10 p.62-63] para E2, p. ej. "sólo las decisiones que nadie toma por ti pueden ser privadas". Determinables [10 p.67-68]: aterrizar "privacidad" en casos concretos (tu báscula, tu Gmail, la negociación de un precio).

### 2. Cuestión final (forma "¿Cuál (de los x)…?" [12 p.85-86])
La pregunta de partida "¿ha muerto la privacidad?" es de tipo sí/no [07 p.47; 12 p.85]; reformulada:

> **¿Cuál (de estas cuatro) es la relación entre delegar decisiones en un agente de IA que conoce tus datos y conservar la privacidad?**
> (a) Incompatibilidad necesaria: toda delegación de ese tipo elimina la privacidad.
> (b) Compatibilidad condicionada a la arquitectura técnica: se conserva si el agente corre bajo control del usuario (local, cifrado, sin exfiltración).
> (c) Compatibilidad condicionada a la estructura colectiva: la privacidad de uno depende de lo que hagan los demás y el regulador, no de su propia configuración.
> (d) Pérdida gradual: la privacidad no se pierde ni se conserva sino que baja de precio; lo que cambia es el coste de decidir sobre alguien.

Opciones explícitas, como exige el libro [12 p.86]. Que sean exhaustivas o excluyentes entre sí es tarea de E3 (seis tipos de relación [12 p.86]); aquí solo se dejan claras.

### 3. Hipótesis en competencia (sin elegir) [07 p.47]
Contenido filosófico del agente, no del libro: todas [H], plausibles y discutibles.

| # | Hipótesis | Quién la encarna en la experiencia | Forma lógica (anticipo de E3) |
|---|---|---|---|
| H1 | Toda delegación en un agente que conoce tus datos elimina la privacidad ("muerta de aquí en adelante") | gakonst (lectura fuerte del tuit; el disparador es [H] según el dosier) | universal necesaria |
| H2 | Hay delegaciones que conservan la privacidad si la herramienta la protege ("solo muere si te rindes", tres capas: herramienta, protocolo, micrófono) | Vitalik | existencial negativa frente a H1 |
| H3 | La privacidad individual es función de la conducta colectiva y de la norma; el esfuerzo individual no la conserva | Helminger, THS ep. 10 | universal sobre el sujeto de la privacidad |
| H4 | La privacidad se degrada por grados según el coste de decidir sobre alguien (3.000 $, 20 $, minutos) | posición de la casa en `info.md` | gradual (anticipa E5, no se abre aquí) |

Ninguna se elige: "No puedes empezar con una tesis y luego buscar la manera de defenderla" [07 p.48]. Aviso: H4 es ya la "posición de la casa" en el dosier; en esta ficha se degrada a hipótesis en pie de igualdad.

### 4. Ficha de criterios [06 p.30]
**Relevancia**
- ¿Hay debate? [06 p.30-31] Sí, y con tres bandos documentados en la misma noche: muerta (gakonst), solo si te rindes (Vitalik), no depende de ti (Helminger/THS). Ser justo con el adversario [06 p.31]: la razón de gakonst es real —un agente que negocia por ti solo es útil si sabe lo que sabes tú, y Muse lo demuestra en el nº 1 del App Store—; Vitalik no niega eso, niega la inevitabilidad. Veredicto: **cumple**.
- ¿Qué se arriesga? [06 p.31] Si vale H1, el consejo "no instales esta app" es inútil y el consentimiento individual es ficción; si vale H2, la carga recae en la herramienta del usuario; si vale H3, en la ley y en la conducta ajena. Equivocarse en H1 es profecía autocumplida (rendirse); equivocarse en H2 es falso consuelo. Para el programa: decide si se dice "protégete" o "esto se juega en lo colectivo". Veredicto: **cumple**.
- Motivación concreta [06 p.31]: la molestia nace de un tuit, una réplica y una app concreta, no en abstracto. **Cumple**.
- No es "solución sin problema" ni borracho bajo el farol [06 p.33-35]: se parte de la molestia, no de una herramienta favorita. Riesgo señalado: el dosier ya trae "posición de la casa" (presupuesto ajeno, divulgación obligatoria, regla de 2 de la AEPD); si la pieza sale de ahí, sería solución antes que problema. **Cumple con aviso**.
- Fraser, doble obstáculo [06 p.35]: la pregunta es nueva en su caso (agentes negociadores), así que hay que persuadir primero de que merece tono filosófico y no solo técnico. Pendiente para la pieza.
- Relevancia restringida al medio [06 p.35-37]: programa sobre IA, la pregunta encaja en su restricción temática.

**Claridad** [06 p.38]
- ¿Pseudo-problema? "La privacidad ha muerto" es una metáfora que, formulada con claridad, puede tener respuesta más simple de lo que parece [06 p.38]: depende de si "privado" se dice de datos o de decisiones. No es pseudo-problema una vez reformulada como relación entre dos conceptos, pero la claridad **queda condicionada a E2** (análisis de "privado").

**Tractabilidad** [06 p.39-42]
- ¿Quiénes somos? Solo los autores: una persona [06 p.39].

| Recurso [06 p.42] | Necesario | Disponible | Veredicto |
|---|---|---|---|
| i. Conocimiento | canon filosófico de privacidad + funcionamiento de agentes | medio: dosier de la casa, sin canon | parcial |
| ii. Información | hilo, réplica de Vitalik, ensayo "Galaxy brain resistance", THS ep. 10 | sí, en `TEMAS/privacidad/` | sí |
| iii. Materiales | ordenador, carpeta | sí | sí |
| iv. Tiempo | una tarde | suficiente para E1-E3 breves; no para E4 completo | parcial |
| v. Atención | una sesión sin interrupción | sí | sí |
| vi. Interés | del autor y del programa | alto | sí |
| vii. Humanos | mesa del programa como "asesores" | disponibles en emisión, no antes | parcial |

- Veredicto: **tratable como pieza breve** (contribuir a la respuesta, no cerrarla [06 p.39]); no tratable como artículo.

### 5. Encaje [08 p.49-51]
- Tema clásico (privacidad tiene tradición: "hipótesis y teorías más avanzadas", preguntas abiertas más difíciles [08 p.51]); el caso —agente que negocia— es atípico. ¿Básico o marginal? Plausiblemente **atípico básico**: si la delegación es compatible con la privacidad toca el concepto mismo, no un rincón. Ventaja: se entra "en blanco", sin intuiciones ancladas [08 p.51]; desventaja: sin canon a mano.
- Normas del medio [06 p.36-37]: no hay normas académicas; las de la casa (mecanismo verificable, fact-check, etiqueta antes del micro) hacen de reglamento. "Entérate y sigue las normas" [06 p.38].

### 6. Recursos que faltan y cómo obtenerlos [06 p.40-41]
- Conocimiento: E0 no hecha; sin bibliotecas, sustituir por enciclopedia en línea y un survey [09 p.53-54, no abierto aquí, solo señalado]. Una hora de la tarde.
- Información: aclaración de gakonst sobre su tuit (pendiente en el dosier); comprobar antes de emitir.
- Tiempo: recortar la ambición a E1-E3 y una cuña; dejar E4 para otra sesión o para la mesa.
- Humanos: usar la mesa del programa como asesores, llegando con respuestas propias, no con problemas [07 p.46].

## Trazabilidad
| Movimiento metodológico | Corpus | Etiqueta |
|---|---|---|
| Análisis ("buscar qué decir") antes que síntesis | [06 p.25] | [V] |
| Niveles tema → aspecto → cuestión → hipótesis → tesis | [06 p.26-29; 07 p.47-48] | [V] |
| Tema cotidiano con dimensión filosófica; explanandum antes que explanans | [06 p.27-28] | [V] |
| "¿Por qué quieres estudiarlo?" en un enunciado breve | [06 p.29] | [V] |
| Del caso particular a la pregunta: comparar variantes, abstraer conceptos, relacionar | [06 p.32-33] | [V] |
| Tres criterios: relevancia, claridad, tractabilidad | [06 p.30] | [V] |
| ¿Hay debate? (justo y generoso con el adversario) y ¿qué se arriesga? | [06 p.30-31] | [V] |
| Motivación concreta: sorpresa o molestia en situaciones concretas | [06 p.31] | [V] |
| Borracho y farol; "solución sin problema" | [06 p.33-35] | [V] |
| Fraser: doble obstáculo de las preguntas inexploradas | [06 p.35] | [V] |
| Relevancia restringida: normas del medio | [06 p.35-37] | [V] |
| Resumen parcial (4 viñetas) | [06 p.37-38] | [V] |
| Claridad: pseudo-problema | [06 p.38] | [V] |
| Tractabilidad: quiénes somos, siete recursos, disponibilidad | [06 p.39-42] | [V] |
| Recursos que faltan: conseguirlos y saber cómo | [06 p.40-41] | [V] |
| Clásico / nuevo; típico / atípico básico / marginal | [08 p.49-51] | [V] |
| Sustantivo → adjetivo; tesis "sólo / todas"; determinables | [10 p.60-63, 67-68] | [V] |
| Tipos de pregunta por especificidad (sí/no → ¿cuál?) | [07 p.47-48; 12 p.85] | [V] |
| Forma "¿Cuál (de los x)…?" con opciones explícitas | [12 p.85-86] | [V] |
| Hipótesis en competencia enumeradas, tesis no decidida | [07 p.47-48] | [V] |
| Llegar a los asesores con respuestas propias | [07 p.46] | [V] |
| Aplicar los criterios a un formato (radio/streaming) que el libro no lista | [06 p.36] | [P] |
| Anticipar la forma lógica de cada hipótesis (universal / existencial) | [14 p.100] | [P] (es material de E3, solo anunciado) |

## Fuera del corpus [H]
- Ponderación entre criterios cuando chocan (aquí la tractabilidad recorta la relevancia): el libro calla [06 p.30]. Decisión propia: recortar alcance, no pregunta.
- El formato "pieza para radio/streaming" y las normas de la casa como "normas del medio": el libro solo habla de cursos, coloquios, volúmenes, tesis y financiadores [06 p.36-37]; la extrapolación es mía.
- Tomar un hilo de X como evidencia de "debate": el libro remite a tendencias del área, enciclopedias y *Philosophical Compass* [06 p.35]; el libro calla sobre redes sociales.
- Las cuatro opciones (a)-(d) y las hipótesis H1-H4 son contenido filosófico mío: plausibles, discutibles, ninguna respaldada por el libro.
- H4 ("coste de decidir") viene del dosier de la casa; señalar que es tesis previa encubierta es aportación propia, el libro solo da la regla general [07 p.48].
- Sustituir E0 por el dosier de `info.md` es decisión mía; el libro exige dominar el tema antes [09 p.52-58, no abierto en esta etapa].

— turno del Crítico —

## Puerta G1 — veredicto del Crítico
Lista literal de `references/puertas-de-calidad.md` § G1, ítem a ítem:

1. ¿Hay debate? [06 p.30] — Sí: tres posiciones fechadas y atribuidas; generoso con gakonst. **Pasa.**
2. ¿Qué se arriesga? [06 p.31] — Ganar / perder enunciados para cada hipótesis y para el programa. **Pasa.**
3. Motivación concreta [06 p.31] — tuit, réplica, app concreta. **Pasa.**
4. No "solución sin problema" [06 p.33-35] — La cuestión nace del problema, pero el dosier trae ya una "posición de la casa" hecha. La ficha la degrada a H4; no basta con decirlo, hay que sostenerlo en E3-E4. **Pasa con aviso.**
5. Claridad, no pseudo-problema [06 p.38] — "Muerta" es metáfora; la ficha lo reconoce y remite a E2. Hasta que "privado" (datos vs. decisiones) esté analizado, la cuestión puede ser dos cuestiones. **Condicionado.**
6. Tractabilidad [06 p.39-42] — Siete recursos con disponibilidad real; conocimiento y tiempo parciales, declarados. **Pasa.**
7. Resumen parcial [06 p.37-38] — Pregunta definida, relevante para el medio, respeta restricción temática, normas del medio identificadas (las de la casa). **Pasa.**
8. Forma "¿Cuál (de los x)…?" con opciones [12 p.86] — Sí, cuatro opciones. Las opciones (b) y (c) no son excluyentes y (d) es de otro tipo (grado, no relación); el libro solo exige que las opciones estén claras [12 p.86], la exhaustividad es de E3. **Pasa.**
9. Hipótesis en competencia sin tesis previa [07 p.47-48] — Cuatro enumeradas, ninguna elegida. Riesgo real de tesis previa (H4 = posición de la casa ya publicada en el dosier). **Condicionado.**
10. Solo E1' — no aplica.

**Veredicto: CONDICIONADO.**
Clave (afecta al veredicto): (i) el Investigador no puede tratar H4 como hipótesis en pie de igualdad mientras el dosier de la casa la sostenga como posición; en E3-E4 debe evaluarse contra H1-H3 con los mismos pros y contras [07 p.48]. (ii) La claridad de la cuestión depende de que E2 fije si "privado" se predica de datos, de decisiones o de ambos [06 p.38]; hasta entonces la cuestión es provisional.
Secundario (no afecta): E0 no ejecutada; evidencia de debate tomada de X y no de un canon [06 p.35]; el ítem "Fraser" queda como tarea, no como comprobación.
Para el autor: la cadena tema → aspecto → cuestión está limpia y el "por qué" en una línea es el mejor activo de la ficha; conserva la comparación de variantes del caso (agente que sabe vs. agente que actúa; abogado humano) para E2.

## Siguiente paso
Prompt 02 (análisis conceptual) sobre "privado" con enunciado ejemplar del caso Muse, heredando las dos condiciones anteriores en "Entradas recibidas". No procede prompt 06: no hay que pedir recursos.
