# PROMPT 02/09 — "DOMINIO Y CONDICIONES" · Etapa E2 · Rol: Investigador (puerta G2: Crítico)

**Función:** determinar el dominio de los conceptos de la cuestión y sus condiciones necesarias y suficientes mediante enunciados ejemplares, variación, hipótesis y contraejemplos.
**Biblia:** `../protocolo-agentes.md` (leer íntegra) + `../corpus/00-indice.md`.
**Corpus a abrir:** `10-cuestiones-filosoficas.md` (pp. 68-72), `11-analisis-de-conceptos.md` (pp. 73-84), `14-argumentacion.md` (pp. 100-104), `18-sintesis-claridad-definiciones.md` (pp. 159-174, definiciones).

## Entradas
- «concepto» o «conceptos» de la cuestión (C1, C2)
- «cuestión» (ficha E1) e hipótesis inicial de dominio, si la hay
- «contexto de uso»: cotidiano, técnico, científico, artístico [10 p.69]

## Método (del corpus)

| Movimiento | Corpus | Etiqueta |
|---|---|---|
| Principio del contexto (Frege): analizar el concepto en un enunciado, no descomponerlo en abstracto | [10 p.68-69] | [V] |
| Cinco criterios del enunciado ejemplar: gramatical, completo, natural, concreto, uso propio | [10 p.69-70] | [V] |
| Completo vs. incompleto ("Yo conozco" / "Yo conozco la zona") | [10 p.70-71] | [V] |
| Dominio de un predicado; errores categoriales (Ryle) | [10 p.71-72; 11 p.73] | [V] |
| Procedimiento: pasos 1-8 + bucle 9-10 (reproducir los diez) | [11 p.73-74] | [V] |
| Elegir la expresión fundamental (vida → vivir) y el sentido que interesa | [11 p.74-75] | [V] |
| Variación positiva y negativa | [11 p.75] | [V] |
| Hipótesis "Es necesario X para Y"; ejemplos que la motivan (X∧Y, ¬X∧¬Y) no la demuestran | [11 p.76-77] | [V] |
| Contraejemplo = Y y no X | [11 p.78] | [V] |
| Responder: cuestionar la corrección del contraejemplo o refinar la hipótesis añadiendo condición | [11 p.78-79, 81-82] | [V] |
| Ida y venida entre lo particular y lo general | [11 p.80] | [V] |
| No confundir conceptos con palabras; buscar no-X cercanos a X | [11 p.81] | [V] |
| Condiciones necesarias y suficientes: tabla de posibilidades y equivalencias | [11 p.82-84] | [V] |
| Universal necesario; contraejemplo imaginario o meramente posible; experimentos mentales | [14 p.100-101] | [V] |
| Anclaje psicológico: desanclar la imaginación | [14 p.103] | [V] |
| Verificar el contraejemplo: a. existe o puede existir, b. es un Y, c. no es un X; refutación simétrica | [14 p.104] | [V] |
| Definición explícita: definiendum / definiens; demasiado amplia o restrictiva; falacia de redefinición | [18 p.161-162, 171-172] | [V] |
| Equilibrio reflexivo; argumentos trascendentales | [01 p.3; 16 p.138] | [A · solo índice] |

## Salida (secciones de la ficha)
1. **Expresión fundamental** elegida y sentido que interesa [11 p.74-75].
2. **Enunciado ejemplar** justificado criterio a criterio (5) [10 p.69-70].
3. **Tabla de variaciones** positivas y negativas [11 p.75].
4. **Hipótesis de dominio** v1 … vn, todas con forma "Es necesario X para Y" [11 p.76-77], con los ejemplos que las motivan.
5. **Tabla de contraejemplos**: candidato · verificación a-b-c [14 p.104] · respuesta (cuestionar / refinar) [11 p.78-79].
6. **Condiciones N/S resultantes** y su tabla de posibilidades [11 p.82-84].
7. **Estado del bucle**: cerrado (paso 10) o abierto (paso 9, qué falta).
8. Trazabilidad · Fuera del corpus [H] · Puerta G2 · Siguiente paso: prompt 03.

## Puerta G2 (Crítico)
Lista literal en `../references/puertas-de-calidad.md` § G2. El Crítico añade al menos dos contraejemplos "desanclados" propios [14 p.103] y comprueba a-b-c.

## Negativo específico
descomponer el concepto sin enunciado [10 p.68] · enunciados abstractos ("el sufrimiento es inevitable") [10 p.70] · contraejemplos sin verificar a-b-c · confundir palabra y concepto [11 p.81] · definir por estipulación lo que está en cuestión [18 p.172] · decir "8 pasos" (son 10)

## Versión compacta (campo único)
> Actúa como Investigador según `protocolo-agentes.md` del paquete investigacion-filosofica. Concepto(s): «concepto»; cuestión: «cuestión»; contexto de uso: «contexto». Abre `corpus/10-cuestiones-filosoficas.md` (pp.68-72), `11-analisis-de-conceptos.md`, `14-argumentacion.md` (pp.100-104) y `18-sintesis-claridad-definiciones.md` (pp.159-174). Aplica el principio del contexto [10 p.68-69]; elige un enunciado ejemplar que cumpla los cinco criterios [10 p.69-70]; ejecuta los pasos 1-8 y el bucle 9-10 [11 p.73-74] con variación positiva y negativa [11 p.75]; formula hipótesis "Es necesario X para Y" [11 p.76-77]; busca contraejemplos "Y y no X" [11 p.78] desanclando la imaginación [14 p.103], verifícalos con a-b-c [14 p.104] y responde cuestionando o refinando [11 p.78-79]; no confundas palabras con conceptos [11 p.81]; cierra con las condiciones necesarias y suficientes [11 p.82-84] y el estado del bucle. Ficha con Trazabilidad [NN p.PP] y "Fuera del corpus [H]". Luego, "— turno del Crítico —": puerta G2 con la lista de `references/puertas-de-calidad.md`, dos contraejemplos propios y veredicto. Castellano de España, breve.
