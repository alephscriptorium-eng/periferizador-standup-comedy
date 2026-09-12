# BASES DE REFERENCIA PARA MATERIALES FUTUROS (tema: singularidad / Navier-Stokes / OpenAI)

> Plantillas de movimiento: cada base es un molde reutilizable sobre el dosier. Elegir UNA por clip; no apilar. Todas las cifras y citas remiten a `dosier.md`, donde llevan etiqueta de evidencia.

## B1 — "La letra pequeña del enunciado"
El enunciado de Clay (Fefferman, 2000) admite cuatro salidas. Dos sin fuerza externa (A, B). Dos con dato inicial suave **y una fuerza suave y decreciente** (C, D). OpenAI reclama C y D. Romper con empujón (C) no dice nada de si el fluido se rompe solo (A): pueden ser verdad las dos. Remate tipo: *el empujón estaba permitido desde el año 2000; en veintiséis años nadie leyó la cláusula (5). La leyó Luis.*
- Sirve para: titulares "resuelto", disputas sobre el premio, cualquier "la IA ha demostrado X" con condiciones en el enunciado.

## B2 — "Estanque quieto, estanque removido"
La parábola del autor llevada al enunciado. **Estanque quieto** = sin fuerza: ¿puede romperse solo? Abierto. **Estanque removido** = con empujón suave permitido: reclamado (OpenAI, Navier-Stokes) y demostrado con Lean público (Alpöge–Buckmaster, Euler/Boussinesq/IPM). El pescador sabe dónde pica: Martínez-Zoroa. Los diez mil barcos pescan en el círculo que él dibujó.
- Sirve para: explicar en 20 s qué se ha hecho y qué no; base visual de los vídeos 01 y 04.

## B3 — "Péndulos en cascada" (el mecanismo)
Una solución corriente, sostenida por un empujón suave. Encima, una onda minúscula que la ecuación amplifica como un péndulo invertido (nace exponencialmente pequeña, crece exponencialmente). Encima, otra más fina y rápida. Infinitas capas, cada una inofensiva; sumadas, la pendiente se hace vertical en un tiempo T. El empujón nunca deja de ser suave. Córdoba y Martínez-Zoroa lo llaman "péndulos degenerados multicapa".
- Sirve para: cuando alguien pregunta "¿pero qué han hecho?"; vídeo 02; contraste con "la IA tuvo la idea".

## B4 — "El-y-no-al-revés: 880.000 horas de buscar, 17 de comprobar"
La asimetría NP del holón: encontrar es caro, comprobar es barato. Diez mil agentes × 88 horas de búsqueda; 17 horas de Lean para certificar. Límite honesto: comprobar no es entender (Tao: "desacoplamiento sin precedentes entre respuestas y comprensión"; Buckmaster sobre la primera demostración de la máquina: "la más horrenda que he leído"). Montecarlo como guiño: la máquina tira dardos, el humano dibuja el círculo, y los dardos aproximan pero no demuestran; aquí demuestra Lean.
- Sirve para: debates IA-y-ciencia, "la máquina piensa", coste de la investigación.

## B5 — "Yo no uso IA: tengo a Luis" (el holón como pescador; el crédito)
El holón (Koestler): a la vez todo y parte. La idea de la cascada es la parte que contiene el todo. Es humana y tiene nombres: Córdoba (ICMAT-CSIC) y Martínez-Zoroa (tesis 2021, CUNEF). Fefferman: "los héroes de la historia". Buckmaster: "merece una Medalla Fields". OpenAI no los citaba en la primera versión; corrigió después. Alpöge y Buckmaster publicaron 12 horas antes que OpenAI y preguntan si el modelo vio sus sesiones.
- Sirve para: crédito, prioridad, "lo artificial" (= la IA) como fuerza bruta guiada por lo humano.

## B6 — "La riña del forcing" (Cohen contento, Gödel no)
Doble sentido de *forcing*: el de Cohen (1963, teoría de conjuntos: construir un modelo donde la Hipótesis del Continuo es falsa) y el de las EDP (el término de fuerza f en la ecuación). No comparten estructura, solo el verbo. Cohen brinda porque oye su palabra; Gödel gruñe porque comprobar en Lean no es entender y porque el enunciado tenía una cláusula; Cantor solo pregunta por su continuo. El camarero, número real no constructible, cierra.
- Sirve para: cierre cómico de la casa (ROL.md: "hacer como Cohen que introduce al sistema lo que no son esos hegemones"); remate de la cuña.

## B7 — Banco de preguntas hermenéuticas (cebo de turnos)
- ¿Quién gana con que no leas la cláusula (5) del enunciado?
- ¿Qué es más caro: 88 horas de diez mil agentes o un año de Luis? ¿Cuál de las dos cosas no se puede comprar?
- Un teorema de cien páginas que ninguna persona ha entendido todavía, ¿es conocimiento o es inventario?
- Si el modelo aprendió de las sesiones de los matemáticos que lo usaban, ¿quién es el autor?
- Si el estanque quieto sigue quieto, ¿por qué el titular dice "resuelto"? ¿Y por qué OpenAI dice que no reclamará el millón?

## Formatos de salida probados
- **Cuña 30-60 s:** una base + un remate + una pregunta a mesa (ver `cuna-estanque-quieto.md`).
- **Vídeo 10 s:** un mecanismo real por pieza, rótulo verificable, plantilla de `influencers/prompt-video-remate.md` (ver `prompt-video-0*.md`).
- **Dinámica de mesa:** B2 como juego: alguien es el pescador, alguien los barcos, alguien Clay; 2 turnos máximo.
