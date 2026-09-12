# DOSIER: SINGULARIDAD / NAVIER-STOKES / OPENAI (septiembre 2026)

> Uso: corpus-caché del tema para intervenciones del tertuliano. No copiar verbatim: condicionar la ventana de contexto y remezclar. Cada dato lleva nivel de evidencia: **[V]** verificado con fuente primaria o dos medios independientes; **[A]** afirmación de parte (OpenAI, Buckmaster) no verificada independientemente; **[P]** probable, visto solo en prensa o en la transcripción de base.md; **[H]** hipótesis nuestra, siempre con contexto de probabilidad. Regla de la casa: lo que no lleve etiqueta no sale por el micro.

> **Aviso de rigor (antes del fulgor):** estado a 10-sep-2026, dos días después del anuncio. Clay no se ha pronunciado sobre el fondo. Nadie ajeno a OpenAI ha revisado las ~165 páginas. El Lean compila, pero comprobar no es entender. Todo lo de OpenAI es [A] hasta que un tercero lo lea. Validen ustedes.

## 1. EL ENUNCIADO: doble visión

**Mito (servilleta de bar):** las ecuaciones de Navier-Stokes (Navier 1822, Stokes 1845) describen agua, aire y sangre. Funcionan tan bien que con ellas se diseñan aviones. Pero nadie sabe si, en tres dimensiones, un fluido que empieza liso puede "romperse": velocidad infinita en un tiempo finito. Un millón de dólares (Clay, 2000) a quien lo diga. [V]

**Logos (papel y lápiz):** Fefferman, enunciado oficial de Clay. Condiciones: dato inicial u° suave, libre de divergencia, con decaimiento (4); fuerza f suave con decaimiento en espacio y tiempo (5); solución físicamente razonable = suave (6) y de energía acotada (7). "Para dar margen razonable a quien lo resuelva sin perder el corazón del problema", se pide demostrar **una** de cuatro salidas: [V, PDF de Clay]

| | Sin fuerza (f ≡ 0) | Con fuerza suave (condición 5) |
|---|---|---|
| **Espacio entero R³** | **(A)** siempre existe solución suave | **(C)** existen u° y f suaves sin solución suave global de energía acotada |
| **Toro R³/Z³** | **(B)** siempre existe solución suave | **(D)** existen u° y f periódicos suaves sin solución suave global |

- **Estanque quieto** = (A)/(B). ¿Se rompe solo? **Abierto.** [V]
- **Estanque removido** = (C)/(D). Existe un empujón suave que lo rompe. **Reclamado por OpenAI.** [A]
- **(C) no niega (A).** Pueden ser verdad las dos: que con cierto empujón suave se rompa y que sin empujón nunca se rompa. Fefferman lo dejó así a propósito ("leeway"). [V]
- La comunidad "se imagina la pregunta dura sin el empujón" (implicator.ai); Fefferman: sin frontera y sin empujón "es el fluido el que hace las locuras". [V/P]

**Idea fuerza:** el titular dice "resuelto"; el plano dice "salida C". El empujón estaba permitido desde el año 2000, en la cláusula (5). Nadie la leyó. La leyó Luis.

## 2. CRONOLOGÍA

- 1822/1845: Navier, Stokes. [V]
- 1934: Leray, soluciones débiles; nace el problema de regularidad. De ahí los "90 años". [V]
- 2000: Clay, siete problemas. 2003-2010: Poincaré resuelto (Perelman, rechaza el premio). **Seis abiertos, no uno.** [V]
- 2021: tesis de Luis Martínez-Zoroa (dir. Diego Córdoba), técnicas analíticas "que no dependen de ordenadores". [V, Quanta]
- sep-2023: arXiv:2309.08495, Córdoba–Martínez-Zoroa: blow-up para Euler 3D con fuerza C^{1,1/2-ε}∩L². Solución en C^{3,1/2}; ∫|∇u| → ∞ en T. Fuerza **no** suave del todo. [V]
- jul-2024: arXiv:2407.06776, Navier-Stokes hipodisipativo con fuerza en L¹ₜC^{1,ε}. [V]
- oct-2024: arXiv:2410.22920, IPM 2D con **fuente suave**: primera vez que la fuerza sale suave. [V]
- may-2025: arXiv:2505.20988, Boussinesq 2D "vía péndulos degenerados multicapa". [V]
- sep-2025: arXiv:2509.14185, DeepMind + Gómez-Serrano, Buckmaster et al.: singularidades **inestables** halladas con redes neuronales (PINNs). Línea distinta: hallazgo numérico, no demostración; sin fuerza. [V]
- ago-2025 → ago-2026: Alpöge y Buckmaster, un año con modelos de lenguaje comerciales sobre la técnica de C–MZ; "progreso lento la mayor parte del año". [V, Quanta]
- 15-ago-2026: Alpöge–Buckmaster, blow-up con fuerza suave para Euler 3D. 22-ago: verificado en Lean. [V, Quanta/implicator]
- 28-ago: OpenAI entrena un modelo interno nuevo. [A]
- 1-sep: OpenAI lanza ~10.000 agentes sobre Navier-Stokes (antes, ~100 agentes ~50 h sobre variantes de Euler). [A]
- 3-sep: Buckmaster escribe a OpenAI aclarando que su trabajo es colaboración personal. [V, unite.ai]
- 5-sep: OpenAI obtiene la demostración (88 h). +17 h de formalización en Lean con GPT-6 Astra. [A]
- 6-sep: dos llamadas Buckmaster ↔ OpenAI (un matemático interno y Sébastien Bubeck). Le dicen: "unas 100 páginas", "muy poca intervención humana". [A, versión de Buckmaster]
- 7-sep: Alpöge–Buckmaster publican tres preprints (IPM, Boussinesq, Euler 3D) con fuerza suave y Lean público. Tao lo explica en su blog. [V]
- 8-sep: OpenAI anuncia. Repo github.com/openai/NavierStokesAndEuler. Quanta: "AI has solved one of math's $1 million Millennium Prize Problems". Primera versión sin citar a C–MZ; a las 16:40 ET ya los cita; Alpöge sigue sin aparecer. [V, varias fuentes]
- 9-10 sep: EFE, El País, El Confidencial, La 7 (Murcia): "dos matemáticos españoles, claves". Clay (Bridson): evaluación "deliberadamente sin prisa" y "absolutamente rigurosa"; Navier-Stokes sigue en la lista de abiertos. [V]

## 3. QUIÉN ES QUIÉN

- **Diego Córdoba**, ICMAT-CSIC. "Hace diez años nadie creía que hubiera una singularidad para Navier-Stokes." "Yo no uso IA: tengo a Luis." [V, Quanta] "Lo que nosotros hacemos a mano, la IA lo hace mucho más rápido; sin nuestro trabajo, sin nuestro método, no habrían podido demostrarlo." [V, La 7/EFE] "Sin nuestra idea, la IA no lo habría resuelto"; la IA sirve para "ganar tiempo, no tener ideas nuevas". [P, El País vía transcripción]
- **Luis Martínez-Zoroa**, 32 años, murciano, CUNEF Universidad. "Me alegro mucho por Tristan... Habría estado bien hacerlo nosotros." [V, Quanta] Fefferman: "los héroes de la historia son Córdoba y Martínez-Zoroa". Buckmaster: "merece una Medalla Fields". [V]
- **Tristan Buckmaster**, NYU. **Levent Alpöge**, matemático, empleado de Anthropic. [V, SciAm] Un año con LLMs; tres resultados con Lean público el 7-sep. Buckmaster sobre la primera demostración generada: "la más horrenda que he leído"; sobre su propio borrador: "AI slop, lo siento". Preguntó si el modelo accedió a sus sesiones de Codex: le dijeron que no; sobre datos de entrenamiento: "no obtuve respuesta". [V/A]
- **OpenAI**: modelo interno "significativamente más capaz que GPT-6 Astra"; ~10.000 agentes; 88 h; 2,7 M mensajes (Quanta dice ~5 M); ~130.000 M tokens; coste "varios millones" (Bubeck), 2-15 M$ (estimaciones). Concede prioridad en Euler a Alpöge–Buckmaster, reclama Navier-Stokes. Niega acceso directo al trabajo privado; "no puede descartar" haberse beneficiado de datos desidentificados del uso de sus productos. **Dice que no reclamará el premio.** [A/V]
- **Clay / Martin Bridson**: "sin prisa", "riguroso"; lista intacta. [V]
- **Terence Tao**: "un desacoplamiento muy extraño y sin precedentes entre obtener respuestas y obtener comprensión". [V] **Luis Silvestre**: "todos en la comunidad estamos discutiendo las implicaciones". [V]

## 4. EL MECANISMO EN LLANO (la cascada de capas)

Fuente: Tao, 7-sep-2026, sobre Alpöge–Buckmaster y C–MZ. [V]

1. **Con fuerza cualquiera, romper es trivial.** Coges un u que explota y defines f := lo que la ecuación no cuadra. El teorema no es "hay blow-up con fuerza"; es "hay blow-up con fuerza **suave hasta T incluido** y de energía finita". Toda la dificultad está en que el cajón donde se mete lo que sobra siga siendo suave con infinitas capas.
2. **Capa 1:** una solución corriente, de baja frecuencia, sostenida por un empujón suave: N(u_lo) = f_lo.
3. **Capa 2:** encima, una ondulación fina de alta frecuencia, u_hi, tan pequeña que no se nota. La ecuación linealizada alrededor de u_lo es **inestable**: la ondulación nace exponencialmente pequeña y crece exponencialmente. Péndulo invertido.
4. **El truco:** "amplitud grande de la corrección de la solución, amplitud minúscula de la corrección de la fuerza". Se cronometra para que la ondulación sea grande justo antes de T sin que f_hi deje de ser suave.
5. **Cascada:** capas 3, 4, 5... cada una más fina y rápida. Cada capa es regular. Sumadas, la pendiente de la velocidad se hace vertical en T. La fuerza total sigue suave.
6. **Lo que se rompe:** la norma C¹ de la velocidad; ∫₀ᵀ ‖ω‖_∞ dt diverge (criterio Beale–Kato–Majda). En el resultado de OpenAI, el fluido parte del reposo. [V/A]

Nombres: C–MZ, "péndulos degenerados multicapa" (Boussinesq). Alpöge–Buckmaster: cerca de T, u_lo lineal en espacio y u_hi onda plana; se resuelve exacto y salen ecuaciones ordinarias de modulación con la inestabilidad requerida. C–MZ lo lograron con fuerza suave para IPM; A–B para IPM, Boussinesq y Euler 3D; OpenAI lo reclama para Navier-Stokes (viscosidad > 0). [V/A]

**Qué NO es:** no es una simulación ni un remolino filmado; es una demostración de existencia. No es el forcing de Cohen (teoría de conjuntos): comparten el verbo, no la estructura. No hay información pública sobre "qué algoritmo de búsqueda" usaron los agentes; lo de Q*/A* del hilo anterior es especulación [H, fuera de antena]. La búsqueda de los agentes fue sobre la demostración (ansatz, estimaciones, parámetros), no "puntos en el espacio de fluidos".

## 5. FACT-CHECK DEL GUION ANTERIOR (base.md, 4×10 s)

| Rótulo / afirmación | Veredicto | Corrección |
|---|---|---|
| "90 años" | [V] con matiz | Desde Leray 1934. Las ecuaciones tienen 180. |
| "7 problemas del Milenio. 1 pregunta sin respuesta" | ✗ | 7 problemas, 1 resuelto, **6 abiertos**. |
| "Forzado: demostrado. No forzado: abierto" | ✗ incompleto | Falta que el forzado suave **está en el enunciado** (C/D). Y "demostrado" es [A]: sin verificación independiente, Clay sin pronunciarse. |
| Silueta "difusa" = Buckmaster/Alpöge | ✗ al revés | A–B tienen Lean público desde el 7-sep. Lo difuso y en disputa es OpenAI. |
| "10.000 agentes. 88 horas. 1 holón humano" | [A] + crédito | Cifras de OpenAI. El "holón" tiene nombres: C–MZ; y A–B un año antes. |
| "La formulación de Clay no incluye fuerza externa" (hilo, L667) | ✗ | Condición (5) y salidas (C)/(D). Error central del hilo. |
| "Q* = A* + Q-learning" como algoritmo usado | [H] sin fuente | Fuera de antena. |
| Montecarlo como imagen de la búsqueda | [P] útil con límite | Montecarlo promedia dardos al azar y aproxima; los agentes buscan dirigidos por una estructura humana y Lean certifica. Lo que traslada: el humano dibuja el círculo. |
| "Lo artificial" corregido a "lo ciego" | ✗ lectura errónea | En la nota del autor "lo artificial" = la IA. La corrección sobraba. |

## 6. LECTURA DE HEGEMONES (ontología ROL.md)

- **Hegemón 1 (OpenAI):** "hemos resuelto un problema del Milenio". Constante alterada: el **enunciado**. Vende (C) como si fuera (A), y a la vez dice que no reclamará el millón: sabe cuál es la cláusula.
- **Hegemón 2 (prensa):** "90 años en 88 horas". Constante alterada: el **tiempo**. Borra el año de Alpöge–Buckmaster y los tres años de C–MZ; convierte 880.000 horas-agente en "88 horas".
- **Hegemón 3 (academia):** "lo que importa es sin fuerza". Cierto, pero protege al incumbente: si el resultado "no cuenta", no hay que leer las 165 páginas.
- **Masas inmersas:** la orilla del estanque maldiciendo o vitoreando "la IA ha resuelto el Milenio" como quien maldice la gravedad, cuando nadie cambió la constante: cambiaron el titular. El plano dice lo mismo desde 2000. Y los matemáticos que usaron el modelo para investigar y descubren que "no se puede descartar" que el modelo aprendiera de ellos: el siervo que abona la tierra del señor.

## 7. LA METÁFORA AFINADA (perspectiva de la casa)

- **Estanque quieto / estanque removido** = (A)(B) / (C)(D). La parábola del autor contiene el enunciado.
- **El pescador** sabe dónde pica: la cascada. Martínez-Zoroa. "Yo no uso IA: tengo a Luis."
- **Los diez mil barcos** pescan en 88 h dentro del círculo del pescador. "Lo artificial" es la fuerza bruta; el holón es humano y tiene nombre.
- **El-y-no-al-revés:** buscar ~880.000 horas-agente; comprobar 17 h de Lean. Asimetría NP. Límite honesto: comprobar no es entender (Tao; Buckmaster).
- **Montecarlo:** el humano dibuja el círculo, la máquina tira dardos. 10.000 dardos dan π con 0,24 % de error; 10.000 agentes no dan "π aproximado", dan un pez o nada. Lo que certifica es Lean, no el número de dardos.
- **Riña del forcing:** Cohen brinda (oye su palabra), Gödel gruñe (comprobar ≠ entender; el enunciado tenía cláusula), Cantor pregunta por el continuo. Camarero: número real no constructible.

## 8. ESTADO E IMPLICACIONES

| Dimensión | Estado a 10-sep-2026 |
|---|---|
| Problema del Milenio | **Abierto en la lista de Clay.** Evaluación "sin prisa". Si (C)/(D) se confirman, encaja en el enunciado literal; OpenAI dice que no reclamará. [V/A] |
| Estanque quieto (A)/(B) | **Abierto.** Nada de esta semana lo toca. [V] |
| Estanque removido (C)/(D) | **Reclamado** (OpenAI, Navier-Stokes), **demostrado con Lean público** para Euler/Boussinesq/IPM (A–B). [A/V] |
| Crédito | En disputa. OpenAI corrigió citas a C–MZ; Alpöge sin citar; "no se puede descartar" datos desidentificados. [V] |
| Verificación | Lean compila (repo público). Nadie ha leído aún el argumento humano. [V] |

**Corto plazo [H, probable]:** lectura de las 165 páginas por terceros; pronunciamiento de Clay sobre si (C) literal basta; pelea por autoría y por los datos de uso. **Medio plazo [H]:** el objetivo pasa al estanque quieto; la técnica de capas no se traslada directamente porque la fuerza es justo el cajón que la hace funcionar. **Estructural [H]:** el "paper + Lean" como formato; asimetría de recursos (solo laboratorios grandes tiran 880.000 horas-agente); y la pregunta de Tao: respuestas sin comprensión.

## 9. FUENTES

- Fefferman, enunciado oficial: https://www.claymath.org/wp-content/uploads/2022/06/navierstokes.pdf
- Tao, 7-sep-2026: https://terrytao.wordpress.com/2026/09/07/finite-time-blowup-with-smooth-forcing-term-for-the-incompressible-porous-medium-boussinesq-and-incompressible-euler-equations/
- Quanta, 8-sep-2026: https://www.quantamagazine.org/ai-has-solved-one-of-maths-1-million-millennium-prize-problems-20260908/
- Repo OpenAI: https://github.com/openai/NavierStokesAndEuler
- unite.ai (OpenAI): https://www.unite.ai/openai-says-internal-ai-system-resolved-the-navier-stokes-problem/ · (Buckmaster–Alpöge): https://www.unite.ai/buckmaster-and-alpoge-post-ai-fluid-blowup-proofs-dispute-openai-contact/
- implicator.ai (Clay): https://www.implicator.ai/clay-institute-navier-stokes-openai-proof-claim/
- Carlo Iacono, "Ten thousand agents, 88 hours": https://hybridhorizons.substack.com/p/ten-thousand-agents-88-hours
- Scientific American: https://www.scientificamerican.com/article/openai-claims-blockbuster-math-breakthrough-amid-swirl-of-controversy/
- Infobae/EFE, 9-sep: https://www.infobae.com/america/agencias/2026/09/09/los-investigadores-martinez-zoroa-y-cordoba-bases-intelectuales-de-los-avances-en-torno-al-problema-de-navier-stokes/
- La 7 (Murcia), 10-sep: https://www.la7tv.es/articulo/actualidad/matematico-murciano-luis-martinez-zoroa-clave-avance-que-puede-cambiar-historia-matematicas/20260910114531073225.html
- Andrew Wu (citas corregidas): https://andrewwu.substack.com/p/openai-and-navier-stokes · Mundiario: https://www.mundiario.com/articulo/tecnologia-ciencia/openai-rectifica-gran-hallazgo-matematico-polemica-investigadores-ignorados/20260910140126440343.html
- El País, 10-sep (no accesible desde aquí; citado vía base.md): "Un año de trabajo de dos matemáticos españoles frente a 88 horas y 15 millones de OpenAI"; "OpenAI corrige de tapadillo su prueba del milenio".
- arXiv: 2309.08495 · 2407.06776 · 2410.22920 · 2505.20988 · 2509.14185
- Montecarlo (microsiervos): https://www.microsiervos.com/archivo/azar/demostracion-visual-interactiva-metodo-montecarlo.html
