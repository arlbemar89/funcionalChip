# ProyectoUno

Este proyecto implementa una compuerta lógica AND de dos entradas.

## How it works

El diseño recibe dos entradas digitales (ui[0] y ui[1]) y genera una salida lógica en uo[0].
La salida será 1 únicamente cuando ambas entradas sean 1.

Tabla de verdad:

| A | B | Output |
|---|---|--------|
| 0 | 0 |   0    |
| 0 | 1 |   0    |
| 1 | 0 |   0    |
| 1 | 1 |   1    |

## How to test

1. Aplicar valores binarios a las entradas ui[0] y ui[1].
2. Observar la salida en uo[0].
3. Verificar que la salida solo sea alta cuando ambas entradas estén en alto.

Ejemplo:
- ui[0] = 1
- ui[1] = 1
- uo[0] = 1
