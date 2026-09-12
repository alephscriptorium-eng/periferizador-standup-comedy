# PROMPTS DE VÍDEO (4 × 10 s): EL ORÁCULO DE LA FUERZA Y LA FORMACIÓN DEL BLOW-UP

> Fuente única: `dosier.md` (§1, §4, §5, §8) y `bases-materiales.md` (B3, B4). Cada rótulo lleva etiqueta de evidencia del dosier. Regla de la casa: lo que no lleve etiqueta no sale por el micro.
> Fecha de redacción: 10-sep-2026. Revisar `dosier.md` §8 antes de emitir el clip 04 (estado Clay / verificación independiente).

## 0. AVISO DE RIGOR (leer antes de generar)

1. **Qué es real y qué es conceptual.** El mecanismo de los clips 01-04 es el de Tao (7-sep) sobre Córdoba–Martínez-Zoroa y Alpöge–Buckmaster: **la fuerza f es el cajón donde se mete lo que la ecuación no cuadra, con la obligación de que el cajón siga suave hasta T con infinitas capas** [V, dosier §4]. Eso es el "oráculo": una pregunta binaria por capa (¿f sigue suave y de energía finita?).
2. **El algoritmo de búsqueda no es público.** OpenAI no ha dicho qué algoritmo usaron los agentes; Q*/A* es especulación [H, dosier §4 y §5]. En el clip 02 el buscador se dibuja como **árbol de candidatos con una función de valor Q(s,a)** en sentido genérico de aprendizaje por refuerzo. En pantalla **nunca** aparece "Q*", ni logotipo de OpenAI, ni la frase "OpenAI usó...". Lo que buscaron los agentes fueron **parámetros de la demostración** (ansatz, frecuencias, amplitudes, tiempos), no "puntos en el espacio de fluidos" [V, dosier §4].
3. **Lo que se rompe** es la norma C¹ de la velocidad; ∫₀ᵀ‖ω‖∞ dt diverge (criterio Beale–Kato–Majda) [V]. No es una simulación ni un remolino filmado: es una **demostración de existencia**. Los fluidos de los clips son diagramas, no CFD.
4. **Estado.** Euler/Boussinesq/IPM: Lean público (Alpöge–Buckmaster, 7-sep) [V]. Navier-Stokes (ν>0): reclamado por OpenAI (8-sep) [A]. Sin fuerza (salidas A/B, "estanque quieto"): abierto [V].

## 1. BIBLIA VISUAL COMÚN (aplica a los 4 clips)

| Parámetro | Especificación |
|---|---|
| Formato | 16:9, 3840×2160, 24 fps, 10,0 s exactos por clip. Zona segura central 9:16 (1215×2160) para recorte vertical: todo rótulo y todo objeto clave dentro de esa zona. |
| Estilo | "Pizarra técnica": fondo pizarra oscura #0B1220 con grano fino; trazos de tiza vectorial blanca #F2F2F2; el fluido como **diagrama de líneas de corriente** (no render fotorreal, no CGI de agua). Iluminación plana, sin volumétricos, sin partículas decorativas. |
| Paleta funcional | Azul #3A7BD5 = velocidad u. Dorado #D4AF37 = fuerza f (el cajón). Rojo #D7263D = rechazado / no suave. Verde #2ECC71 = aceptado / suave. Gris #8A94A6 = texto secundario. |
| Objetos persistentes (mismo diseño en los 4 clips) | **(a) La losa**: un bloque rectangular translúcido 3D, visto en tres cuartos, que contiene el fluido como líneas de corriente azules. **(b) El libro mayor**: a la derecha, la ecuación ∂ₜu + (u·∇)u + ∇p − νΔu = f escrita a tiza, con cada término como una casilla que se ilumina cuando se calcula. **(c) El cajón**: caja dorada abierta bajo el signo "= f"; su contenido se dibuja como una curva (perfil de f en el tiempo, de 0 a T). **(d) La regla de T**: barra de tiempo horizontal en la parte inferior, de 0 a T, con una marca roja vertical en T. **(e) Los dos indicadores**: dos medidores verticales, "‖u‖_{C¹}" (azul) y "‖f‖_{C^k}" (dorado), pegados al borde derecho. |
| Tipografía | Sans-serif fina (Inter Light o similar), rótulos blancos, 64 px en 4K, centrados en el tercio inferior, fondo sin caja. Fórmulas a tiza en serif matemática (Latin Modern). |
| Audio | Sin música épica. Base: tictac seco de metrónomo a 60 bpm que **marca el tiempo hacia T** en todos los clips. Efectos: trazo de tiza (dibujar), "clac" de cajón (aceptación), "zumbido" grave breve (rechazo). Silencio absoluto en el último 0,5 s de cada clip. Sin voz en off (los rótulos llevan el texto; la cuña va aparte). |
| Cámara | Fija o dolly muy lento. Nada de orbitales, flashes a blanco, ni fundidos a negro largos. Cortes secos. |
| Prohibido en pantalla | "Resuelto", "demostrado" aplicado a Navier-Stokes, "Q*", "A*", logotipos, "90 años en 88 horas", "1 pregunta sin respuesta", siluetas de personas, muros, grietas, faros, redes, océanos de puntos. |

---

## CLIP 01 — "EL CAJÓN" (mecanismo a, parte 1: qué es el oráculo de la fuerza)

**Mecanismo real que se enseña:** con fuerza cualquiera, romper es trivial (defines f := lo que la ecuación no cuadra, y f revienta con u). El teorema exige que **f siga suave hasta T incluido y con energía finita**. Toda la dificultad está en ese cajón [V, dosier §4.1].

**Prompt para el agente multimodal:**

Genera un clip de 10,0 s, 16:9, 4K, 24 fps, estilo pizarra técnica (ver biblia). Sin voz. Metrónomo a 60 bpm de fondo desde 0,0 s.

| Tiempo | Visual (qué se dibuja y cómo) | Cámara | Audio | Rótulo |
|---|---|---|---|---|
| 0,0–1,5 s | Sobre la pizarra vacía se dibuja a tiza, trazo animado de izquierda a derecha en 1,2 s, la ecuación ∂ₜu + (u·∇)u + ∇p − νΔu = f. Bajo el término "f" se dibuja el **cajón dorado**, vacío. A la izquierda aparece la **losa** con un fluido azul liso: líneas de corriente paralelas, apenas onduladas. Debajo, la **regla de T** con la marca roja en T. | Plano general fijo, la ecuación ocupa el tercio superior. | Trazo de tiza. Tic, tac. | — |
| 1,5–4,0 s | **Intento trivial.** En la losa, las líneas azules se aprietan hacia un punto y forman un pico que crece (una espiga vertical) mientras el cursor de la regla de T avanza. Cada término de la ecuación se ilumina en secuencia (0,4 s cada uno) al "calcularse", y lo que sobra cae, como polvo de tiza dorada, dentro del cajón. La curva del cajón (perfil de f) **sube en espiga roja** al acercarse a T: f revienta igual que u. A 3,6 s un sello rojo "NO SUAVE" se estampa sobre el cajón. | Dolly lento hacia el cajón (10 % de zoom). | Tic, tac. Zumbido grave a 3,6 s. | 2,0–4,0 s: **"Con fuerza cualquiera, romper es trivial."** [V] |
| 4,0–5,0 s | La losa y el cajón se borran con un gesto de borrador (0,6 s). Queda la ecuación. | Vuelve al plano general. | Sonido de borrador. | — |
| 5,0–7,5 s | **La exigencia.** Junto al cajón se dibujan a tiza dos condiciones, una por segundo: "f suave en [0, T]" y "∫∫|f|² < ∞". Se dibujan los **dos indicadores** en el borde derecho: ‖u‖_{C¹} en azul, ‖f‖_{C^k} en dorado, ambos con una línea de tope. Aparece una nueva losa con un fluido azul liso de baja frecuencia (u_lo) y el cajón recibe una curva dorada **plana y suave** (f_lo). Sello verde "SUAVE" a 7,2 s. | Fijo. | Trazo de tiza ×2. Clac de cajón a 7,2 s. | 5,5–7,5 s: **"La dificultad es que el cajón siga suave hasta T."** [V] |
| 7,5–9,5 s | Sobre la losa u_lo aparecen, dibujados a tiza y vacíos, cinco marcos superpuestos y cada vez más finos, numerados 1, 2, 3, 4, 5, con puntos suspensivos "…∞". Son las capas que faltan. El cursor de la regla de T se detiene a mitad de camino. | Dolly muy lento hacia atrás (5 %). | Tic, tac. | 8,0–9,5 s: **"Infinitas capas. El cajón tiene que aguantar todas."** [V] |
| 9,5–10,0 s | Congelado. Silencio. | Fijo. | Silencio. | — |

**Negativo:** nada de agua fotorreal, sin remolinos dorados, sin explosiones, sin texto adicional, sin logotipos.
**Verificación de rótulos:** los tres son paráfrasis de dosier §4.1 (Tao) [V].

---

## CLIP 02 — "LA INYECCIÓN" (mecanismo a, parte 2: el oráculo dentro del buscador)

**Mecanismo real que se enseña:** una capa nueva es una ondulación de alta frecuencia sembrada exponencialmente pequeña; la ecuación linealizada alrededor de la capa anterior es **inestable** (péndulo invertido) y la amplifica sola. Por eso la corrección de la solución es grande y la corrección de la fuerza es minúscula; el cajón apenas nota la siembra [V, dosier §4.3–4.4]. El buscador elige **parámetros** de la capa (frecuencia N_k, amplitud ε_k, instante t_k) y el oráculo del cajón acepta o rechaza [V para el qué; el cómo del buscador es representación conceptual, H].

**Prompt para el agente multimodal:**

Genera un clip de 10,0 s, misma biblia. Pantalla dividida verticalmente desde 0,0 s: **izquierda (55 %)** el buscador; **derecha (45 %)** la losa, el cajón y los dos indicadores del clip 01, ya dibujados, con u_lo (fluido liso azul) y f_lo (curva dorada plana). Metrónomo a 60 bpm.

| Tiempo | Visual | Cámara | Audio | Rótulo |
|---|---|---|---|---|
| 0,0–2,0 s | **El buscador.** A la izquierda se dibuja a tiza un árbol: nodo raíz "capa 1 (u_lo, f_lo) ✓" arriba; de él cuelgan **ocho ramas** candidatas para la capa 2, cada una etiquetada con tres números pequeños en gris: "N=…", "ε=…", "t=…" (frecuencia, amplitud, instante de siembra; valores ilustrativos, no reales). Junto a cada rama, una barra fina horizontal "Q" que se rellena en distinto grado (función de valor, en gris). Decenas de cursores diminutos (tiza blanca, sin forma humana ni de robot) recorren ramas y las alargan: los agentes. | Fijo. | Trazo de tiza rápido, clics suaves de cursor. | 0,5–2,0 s: **"El buscador propone parámetros: frecuencia, amplitud, instante."** [V: dosier §4 "ansatz, estimaciones, parámetros"] |
| 2,0–3,5 s | La rama con la barra Q más llena se ilumina en blanco. **Inyección:** desde esa rama sale una línea que cruza al panel derecho y toca el cajón en el instante t_k de la regla de T. En el cajón aparece una **ondulación dorada minúscula** (amplitud casi invisible, ~2 px a 4K, se subraya con un círculo de tiza para que se vea). En la losa nace, sobre las líneas azules lisas, una **ondulación azul finísima** de alta frecuencia, también minúscula. El indicador ‖f‖_{C^k} sube un pelo (2 % de su escala). | Dolly de 8 % hacia el panel derecho. | Clac suave de cajón a 2,4 s. | 2,5–3,5 s: **"Siembra: una ondulación exponencialmente pequeña."** [V] |
| 3,5–6,5 s | **Péndulo invertido.** En un recuadro de tiza dentro del panel derecho (esquina superior) se dibuja un péndulo invertido: barra vertical sobre un pivote; a 3,8 s recibe un toque imperceptible y a partir de ahí cae **acelerando** (curva exponencial). Sincronizado con la caída: la ondulación azul de la losa **crece exponencialmente** hasta ser visible y luego grande (de 2 px a 300 px de amplitud entre 3,8 y 6,5 s, con ley e^{λ(t−t_k)}, dibujada también como curva creciente al lado del indicador azul). El indicador ‖u‖_{C¹} sube deprisa. **El cajón no cambia**: la curva dorada sigue plana; el indicador dorado permanece casi en cero. La ecuación del libro mayor muestra sólo el término lineal iluminado: "∂ₜu_hi + L_{u_lo} u_hi ≈ 0". | Fijo. | Tic, tac; un tono ascendente muy suave (seno) que sigue la exponencial, sin llegar a agudo. | 4,5–6,5 s: **"Corrección grande en la solución, minúscula en la fuerza."** [V, Tao] |
| 6,5–8,5 s | **El oráculo poda.** Vuelta al árbol (izquierda). Junto a la rama elegida se muestran, en miniatura, dos ramas hermanas con su cajón: una con t demasiado temprano (la ondulación llega demasiado grande antes de T y el residuo no lineal cae al cajón: espiga roja, sello "NO SUAVE", la rama se tacha en rojo); otra con t demasiado tarde (ondulación aún pequeña en T: la rama se atenúa en gris, "no aporta"). La rama elegida recibe sello verde "SUAVE" y se convierte en nodo "capa 2 ✓", del que empiezan a colgar nuevas ramas para la capa 3. | Dolly de vuelta al plano general. | Zumbido grave (rechazo) a 7,0 s; clac (aceptación) a 8,0 s. | 7,0–8,5 s: **"El oráculo sólo pregunta: ¿el cajón sigue suave?"** [V] |
| 8,5–9,5 s | Sobre el árbol, en gris pequeño y esquina inferior izquierda: "representación conceptual; algoritmo no publicado". El cursor de la regla de T avanza un paso. | Fijo. | Tic, tac. | 8,5–9,5 s: **"Buscar es caro. Comprobar, barato."** [V, B4] |
| 9,5–10,0 s | Congelado. Silencio. | Fijo. | Silencio. | — |

**Negativo:** sin la palabra "Q*" ni "A*", sin logotipos, sin robots, sin "OpenAI", sin cifras de agentes u horas (esas van en la cuña, no aquí), sin fórmulas de Q-learning en pantalla (la barra "Q" es sólo un medidor).
**Verificación de rótulos:** 1 y 4 según dosier §4 (búsqueda sobre parámetros de la demostración; asimetría B4); 2 y 3 son paráfrasis de Tao vía dosier §4.3–4.4 [V]. La leyenda "representación conceptual" cubre el [H] del buscador.

---

## CLIP 03 — "LA CASCADA" (mecanismo b, parte 1: cómo se forma el blow-up)

**Mecanismo real que se enseña:** capas 1, 2, 3… cada una más fina y más rápida, cada una regular, cada una cronometrada para hacerse grande justo antes de T. Sumadas, la pendiente de la velocidad se hace vertical en T; la fuerza total sigue suave [V, dosier §4.5; B3 "péndulos degenerados multicapa"].

**Prompt para el agente multimodal:**

Genera un clip de 10,0 s, misma biblia. Pantalla en dos franjas horizontales desde 0,0 s: **franja superior (60 %)**: perfil 1D de la velocidad, u frente a x, dibujado a tiza azul sobre ejes (una sola curva); **franja inferior (40 %)**: perfil de la fuerza total f frente a x, en dorado, y a su derecha el cajón. Regla de T al pie. Metrónomo a 60 bpm que **se mantiene constante** aunque las capas aceleren (el tiempo real no se acelera; las capas son más rápidas).

| Tiempo | Visual | Cámara | Audio | Rótulo |
|---|---|---|---|---|
| 0,0–1,5 s | Curva azul u_lo: una pendiente suave, casi una recta inclinada (cerca de T la capa base es lineal en el espacio [V, A–B]). Curva dorada f: plana y suave. Cursor de T al 30 %. | Fijo. | Tic, tac. | 0,5–1,5 s: **"Capa 1: una solución corriente, sostenida por un empujón suave."** [V] |
| 1,5–3,0 s | **Capa 2** se suma a la curva azul: una onda plana de longitud de onda λ₂ (ocho crestas en pantalla) que nace invisible a 1,5 s y crece hasta amplitud media a 3,0 s; la pendiente máxima de la curva azul aumenta. En la franja dorada, sólo un rizo mínimo (la siembra), que se aplana. Un contador a tiza en la esquina: "capa 2, N₂". | Fijo. | Clac a 1,6 s. | — |
| 3,0–4,5 s | **Capa 3**: onda con la mitad de longitud (dieciséis crestas), nace a 3,0 s y crece **más deprisa** (su exponencial es más empinada). La pendiente de la curva azul se acerca a 60°. Franja dorada: otro rizo, más pequeño aún. Contador "capa 3, N₃". | Dolly de 5 % hacia el punto de pendiente máxima. | Clac a 3,1 s. | 3,5–4,5 s: **"Cada capa: más fina, más rápida, y regular."** [V] |
| 4,5–6,5 s | **Capas 4, 5, 6** en 0,7 s cada una (longitudes 1/4, 1/8, 1/16). Cada onda nace y crece hasta su amplitud justo antes de T. La suma en un punto x₀ marcado con una cruz de tiza se vuelve un escalón casi vertical: 70°, 80°, 85°. Junto al punto, un pequeño transportador de tiza muestra el ángulo. Franja dorada: rizos decrecientes; la curva total f sigue **visiblemente suave**, sin picos. | Continúa el dolly hasta 15 % de zoom sobre x₀. | Clac ×3 más cortos. Tic, tac constante. | 5,0–6,5 s: **"Sumadas, la pendiente se hace vertical en T."** [V] |
| 6,5–8,5 s | Vista partida en tres columnas pequeñas dentro de la franja superior, cada una con el mismo cronometraje: "capa k nace en t_k, alcanza su tamaño en t_k' < T". Tres líneas de tiempo paralelas que convergen a T como un embudo. Se escribe a tiza: "u = u₁ + u₂ + u₃ + …" arriba y "f = f₁ + f₂ + f₃ + … suave" abajo. | Fijo. | Tic, tac. | 7,0–8,5 s: **"Córdoba y Martínez-Zoroa: 'péndulos degenerados multicapa'."** [V, arXiv:2505.20988] |
| 8,5–9,5 s | El cursor de la regla de T queda a un paso de T. La curva azul, casi vertical en x₀. La dorada, lisa. Los dos indicadores del borde: azul cerca del tope, dorado bajo. | Fijo. | Tic. | — |
| 9,5–10,0 s | Congelado. Silencio. | Fijo. | Silencio. | — |

**Negativo:** sin remolino 3D, sin explosión, sin "aceleración" de la música, sin colores incandescentes; el clímax es geométrico (una pendiente), no pirotécnico.
**Verificación de rótulos:** todos paráfrasis de dosier §4.2–4.5 y B3 [V]. La forma "u_lo lineal en espacio, u_hi onda plana cerca de T" es de Alpöge–Buckmaster vía dosier §4 [V].

---

## CLIP 04 — "EL INSTANTE T" (mecanismo b, parte 2: qué se rompe y qué no)

**Mecanismo real que se enseña:** lo que diverge es la norma C¹ de la velocidad y la integral ∫₀ᵀ‖ω‖∞ dt (Beale–Kato–Majda); la fuerza sigue suave **en T incluido**. Estado: Euler/Boussinesq/IPM con Lean público [V]; Navier-Stokes reclamado [A]; sin fuerza, abierto [V] [dosier §4.6, §8].

**Prompt para el agente multimodal:**

Genera un clip de 10,0 s, misma biblia. Arranca con la composición final del clip 03 (curva azul casi vertical en x₀, curva dorada lisa, cursor a un paso de T, dos indicadores). Metrónomo a 60 bpm.

| Tiempo | Visual | Cámara | Audio | Rótulo |
|---|---|---|---|---|
| 0,0–2,0 s | Se añade a la derecha un tercer medidor a tiza: una integral que se rellena, "∫₀ᵗ ‖ω‖∞ dt", con su área sombreada creciendo bajo una curva que sube cada vez más empinada. El cursor de T avanza los últimos milímetros. La pendiente en x₀ pasa de 85° a 89°. | Fijo. | Tic, tac. | 0,5–2,0 s: **"Lo que se rompe: la pendiente de la velocidad."** [V] |
| 2,0–3,0 s | **T.** El cursor toca la marca roja a 2,5 s. La curva azul se vuelve vertical en x₀ (segmento vertical de tiza, con una flecha "∞" arriba). El área de la integral "se sale" del marco (la sombra rebasa el borde superior del medidor y se escribe "= ∞"). El indicador azul ‖u‖_{C¹} rompe su línea de tope. **La curva dorada f sigue lisa** y su indicador queda bajo, con un sello verde "SUAVE EN T" a 2,9 s. | Corte a plano cerrado sobre x₀ y los indicadores (30 % de zoom) a 2,5 s. | El metrónomo **se detiene** a 2,5 s. Clac a 2,9 s. | 2,5–4,0 s: **"En T: velocidad con pendiente infinita. La fuerza, suave hasta T incluido."** [V] |
| 4,0–5,0 s | Pequeña nota a tiza gris bajo la losa: "Beale–Kato–Majda: ∫₀ᵀ‖ω‖∞ dt = ∞". Nada más se mueve. | Fijo. | Silencio. | — |
| 5,0–8,5 s | **Tablero de estado.** La composición se reduce al 50 % y se desplaza a la izquierda; a la derecha se dibujan a tiza tres filas, una cada 1,1 s: (1) "Euler · Boussinesq · IPM — fuerza suave — Lean público (Alpöge–Buckmaster, 7-sep)" con marca verde; (2) "Navier-Stokes (ν > 0) — fuerza suave — reclamado (OpenAI, 8-sep)" con marca gris y la palabra "reclamado" subrayada; (3) "Sin fuerza (f ≡ 0): ¿se rompe solo? — abierto" con un interrogante a tiza y **sin marca**. Bajo la fila 2, en gris pequeño: "parte del reposo, según OpenAI". | Fijo. | Trazo de tiza ×3. | 6,0–8,5 s: **"Con empujón suave: demostrado para Euler, reclamado para Navier-Stokes. Sin empujón: abierto."** [V/A/V] |
| 8,5–9,5 s | Sobre las tres filas se dibuja a tiza la tabla del enunciado en miniatura: "(A)(B) sin fuerza · (C)(D) con fuerza suave", y se rodea con un círculo la letra (C). Esquina inferior derecha, gris: "Clay: evaluación 'sin prisa'. Lista intacta." | Fijo. | Trazo. | — |
| 9,5–10,0 s | Congelado. Silencio. | Fijo. | Silencio. | — |

**Negativo:** sin "resuelto", sin "Milenio" como eslogan, sin balanza, sin muro, sin siluetas, sin cifras de coste, sin "verificado" aplicado a Navier-Stokes (el Lean de OpenAI compila, pero nadie ajeno ha leído el argumento: dosier §8).
**Verificación de rótulos:** fila 1 [V, Quanta/Tao]; fila 2 [A, OpenAI]; fila 3 [V, enunciado de Clay]; "parte del reposo" [A]; BKM y norma C¹ [V, dosier §4.6]; Clay "sin prisa" [V, implicator].
**Fecha:** este clip caduca. Antes de emitir, releer dosier §8 y actualizar filas 2 y 3 si Clay o terceros se han pronunciado.

---

## 2. TABLA DE RÓTULOS Y ETIQUETAS (para el fact-check final)

| Clip | Rótulo | Etiqueta | Origen en dosier |
|---|---|---|---|
| 01 | Con fuerza cualquiera, romper es trivial. | [V] | §4.1 |
| 01 | La dificultad es que el cajón siga suave hasta T. | [V] | §4.1 |
| 01 | Infinitas capas. El cajón tiene que aguantar todas. | [V] | §4.1, §4.5 |
| 02 | El buscador propone parámetros: frecuencia, amplitud, instante. | [V] (qué) / [H] (cómo, marcado en pantalla) | §4 "Qué NO es", §5 |
| 02 | Siembra: una ondulación exponencialmente pequeña. | [V] | §4.3 |
| 02 | Corrección grande en la solución, minúscula en la fuerza. | [V] | §4.4 (Tao) |
| 02 | El oráculo sólo pregunta: ¿el cajón sigue suave? | [V] | §4.1 |
| 02 | Buscar es caro. Comprobar, barato. | [V] | B4 |
| 03 | Capa 1: una solución corriente, sostenida por un empujón suave. | [V] | §4.2 |
| 03 | Cada capa: más fina, más rápida, y regular. | [V] | §4.5 |
| 03 | Sumadas, la pendiente se hace vertical en T. | [V] | §4.5 |
| 03 | "Péndulos degenerados multicapa". | [V] | §2 (arXiv:2505.20988) |
| 04 | Lo que se rompe: la pendiente de la velocidad. | [V] | §4.6 |
| 04 | En T: velocidad con pendiente infinita. La fuerza, suave hasta T incluido. | [V] | §4.1, §4.6 |
| 04 | Con empujón suave: demostrado para Euler, reclamado para Navier-Stokes. Sin empujón: abierto. | [V]/[A]/[V] | §8 |

## 3. ORDEN DE EMISIÓN Y ENGANCHE CON LA CUÑA

01 → 02 (mecanismo a: el cajón y su inyección en el buscador) → 03 → 04 (mecanismo b: cascada e instante T). Los cuatro comparten losa, libro mayor, cajón, regla de T e indicadores, así que se pueden montar seguidos (40 s) o emitir sueltos. Cifras (10.000 agentes, 88 h, 17 h de Lean) y nombres propios van en la cuña y en B4/B5, no en los rótulos, salvo los créditos de la fila 1 del clip 04.
