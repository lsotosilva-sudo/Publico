# Escala Umbral

Batería interactiva de aptitudes cognitivas en dos formas, en español:

- **Forma A** — adultos (16+): 62 ítems, 5 pruebas, ~30 minutos.
- **Forma I** — niñas y niños de 8 años (8;0–8;11): 44 ítems, 5 pruebas, ~20 minutos.

Todo vive en un único archivo estático sin dependencias: [`index.html`](index.html). Se abre en https://lsotosilva-sudo.github.io/Publico/escala-umbral/.

## Estructura

| # | Forma A | Forma I | Índice | Tiempo |
|---|---------|---------|--------|--------|
| 1 | Analogías verbales (12) | Palabras y semejanzas (10) | Comprensión verbal | 6 min |
| 2 | Matrices lógicas (15) | Figuras que siguen (12) | Razonamiento fluido | 12 / 10 min |
| 3 | Razonamiento numérico (13) | Números y problemas (10) | Razonamiento cuantitativo | 10 / 8 min |
| 4 | Amplitud de dígitos (directa 3–9, inversa 2–8) | Recuerda los números (directa 2–6, inversa 2–5) | Memoria de trabajo | sin límite |
| 5 | Claves de símbolos (9 símbolos) | Dibujos con número (6 símbolos) | Velocidad de procesamiento | 90 / 60 s |

Elementos de aplicación estandarizada: orden fijo de pruebas, series de dígitos predeterminadas,
regla de discontinuación (dos ensayos fallidos en la misma longitud), bloques cronometrados con
omisión puntuada como error, y matrices generadas por reglas con semilla fija, de modo que todas
las aplicaciones ven exactamente los mismos ítems y las mismas alternativas en el mismo orden.

## Puntuación

1. Puntuación directa por prueba (aciertos, ensayos correctos o elementos completados).
2. `z = (directa − media) / DE` del grupo normativo de la forma, truncada en ±3.
3. Puntuación escalar `Ep = 10 + 3z` (M = 10, DE = 3) e índice `100 + 15z` por prueba.
4. CI total: `100 + 15 · (Σz / √(k + k(k−1)r))` con k = 5 y r = 0,45 (intercorrelación media
   estimada), en vez de promediar índices correlacionados.
5. Intervalo de confianza del 90 %: `±1,645 · 15 · √(1 − 0,90)` ≈ ±8 puntos.

## Límites

Los baremos son estimaciones abiertas, no provienen de un estudio de tipificación con muestra
representativa, y el instrumento no diagnostica nada. Los ítems son originales: los de WAIS-IV y
WISC-V están protegidos por derechos de autor y difundirlos invalidaría esas pruebas.
