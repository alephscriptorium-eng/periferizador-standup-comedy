# Índice de montaje — «Tierra de nadie (versión IAIA 2000)»

Dos planos separados, 14 fichas cada uno. Se entregan a los agentes **por vías distintas**:

- **`MUSICA-NN-*.md`** → base instrumental. Sin voz de ningún tipo. Cada ficha reserva el hueco vocal (cuántas frases, de qué longitud, dónde respira) **sin decir las palabras**.
- **`LETRA-NN-*.md`** → texto. Inicializadas con el molde métrico ya fijado y el hueco vacío a rellenar.

El molde métrico es el contrato entre los dos planos: si la letra lo cumple, encaja sobre la música sin retocar nada.

## Orden de ensamblaje

| # | Música | Letra | Sección | Dur. | Din. |
|---|---|---|---|---|---|
| 01 | [MUSICA-01-INTRO.md](MUSICA-01-INTRO.md) | — instrumental | Intro | 0:22 | 3 |
| 02 | [MUSICA-02-ESTROFA-1.md](MUSICA-02-ESTROFA-1.md) | [LETRA-02](LETRA-02-ESTROFA-1.md) 🟡 | Estrofa 1 | 0:28 | 2 |
| 03 | [MUSICA-03-COLETILLA.md](MUSICA-03-COLETILLA.md) | [LETRA-03](LETRA-03-COLETILLA.md) 🟡 | Coletilla stop-time | 0:10 | 3 |
| 04 | [MUSICA-04-ESTROFA-2.md](MUSICA-04-ESTROFA-2.md) | [LETRA-04](LETRA-04-ESTROFA-2.md) 🟡 | Estrofa 2 | 0:28 | 3 |
| 05 | [MUSICA-05-PREESTRIBILLO.md](MUSICA-05-PREESTRIBILLO.md) | [LETRA-05](LETRA-05-PREESTRIBILLO.md) 🟡 | Pre-estribillo | 0:22 | 4 |
| 06 | [MUSICA-06-ESTRIBILLO-A.md](MUSICA-06-ESTRIBILLO-A.md) | [LETRA-06](LETRA-06-ESTRIBILLO-A.md) 🟡 | **Estribillo principal** | 0:22 | 5 |
| 07 | [MUSICA-07-ESTROFA-3.md](MUSICA-07-ESTROFA-3.md) | [LETRA-07](LETRA-07-ESTROFA-3.md) 🟡 | Estrofa 3 silábica | 0:28 | 3 |
| 08 | [MUSICA-08-ESTROFA-LARGA-A.md](MUSICA-08-ESTROFA-LARGA-A.md) | [LETRA-08](LETRA-08-ESTROFA-LARGA-A.md) 🟡 | Estrofa larga A | 0:20 | 4 |
| 09 | [MUSICA-09-ESTROFA-LARGA-B.md](MUSICA-09-ESTROFA-LARGA-B.md) | [LETRA-09](LETRA-09-ESTROFA-LARGA-B.md) 🟡 | Estrofa larga B | 0:20 | 4 |
| 10 | [MUSICA-10-SOLO.md](MUSICA-10-SOLO.md) | — instrumental | Solo de guitarra | 0:30 | 4 |
| 11 | [MUSICA-11-ESTRIBILLO-B.md](MUSICA-11-ESTRIBILLO-B.md) | [LETRA-11](LETRA-11-ESTRIBILLO-B.md) 🟡 | **Estribillo final** | 0:22 | 5 |
| 12 | [MUSICA-12-PUENTE.md](MUSICA-12-PUENTE.md) | [LETRA-12](LETRA-12-PUENTE.md) 🟡 | Puente | 0:23 | 2→5 |
| 13 | [MUSICA-13-ESTRIBILLO-B-BIS.md](MUSICA-13-ESTRIBILLO-B-BIS.md) | [LETRA-13](LETRA-13-ESTRIBILLO-B-BIS.md) 🟡 | Estribillo bis | 0:20 | 5 |
| 14 | [MUSICA-14-CODA.md](MUSICA-14-CODA.md) | [LETRA-14](LETRA-14-CODA.md) 🟡 | **Coda, giro a mayor** | 0:30 | 3→5→cae |

**Total previsto: 5:05.** Doce secciones con voz, dos instrumentales (01 y 10).

## Pares gemelos

Comparten toma musical. Repártelos al **mismo** agente, o pasa el audio del primero como referencia al generar el segundo:

- **08 ↔ 09** — mismo galope, mismos 8 compases. La 09 solo añade armonía de segunda guitarra en la segunda mitad.
- **11 ↔ 13** — mismo estribillo. La 13 tiene un golpe menos y sostiene el final.
- **12 ↔ 14** — misma arquitectura desnudo→crescendo. La 14 gira a **Mi mayor** y afirma donde la 12 niega.

## Curva dinámica

```
5 |                    ██              ██    ██   ██
4 |              ██          ██  ██ ██ ██    ██   ██
3 | ██    ██           ██                ▁▁      ▁██
2 |    ██                                 ▁▁
  +--01-02-03-04-05-06-07-08-09-10-11-12-13-14
```

Dos cimas: el estribillo 06 y el bloque 11–14. Los valles de 02 y 12 existen para que esas cimas se noten. Quien genere una sección baja **no debe** subirla por su cuenta.

## Constantes compartidas

100 BPM · 4/4 · Mi menor · heavy metal español de 1987 · guitarras gemelas, sin teclados · mezcla seca y frontal · voz (cuando llegue) barítono con rasgado, castellano.

Repetidas dentro de cada ficha de música. **Si se cambia una, hay que cambiarla en las 14.**

## Regla que sostiene el paralelismo

Cada ficha de música dice **de qué sale** y **hacia qué entra**. Ninguna sección puede cambiar su juntura sin avisar a las dos vecinas. Es lo único que impide que 14 generaciones independientes suenen a 14 canciones distintas.

Y una obligación específica del plano musical: **reservar el registro vocal** (200 Hz – 2 kHz) en los compases marcados como hueco vocal. Nada de guitarra solista ahí. La voz llega después.

## Aviso sobre la descripción musical

La obra de partida es «Tierra de nadie» de Barón Rojo (LP homónimo, 1987). Lo que las fichas describen **no es una transcripción**: es una reconstrucción prescriptiva deducida de la métrica del texto y de las convenciones del género. Los BPM, la tonalidad y los compases son decisiones de producción de este proyecto para que las 14 piezas encajen, no datos medidos del original.

## Ficheros anteriores

Las 14 fichas `SECCION-NN-*.md` de la primera pasada mezclaban música y letra en un solo documento. Quedan **superadas** por este par de series. No las repartas a los agentes.
