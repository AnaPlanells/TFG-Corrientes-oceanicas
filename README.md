# TFG – Simulación de corrientes oceánicas y disipación energética

Este repositorio contiene el código y materiales del Trabajo de Fin de Grado **"Relaciones entre variables en un sistema oceánico retroalimentado: simulaciones y simetrías"**.

## Resumen

El objetivo del trabajo es **explorar desde cero las relaciones fundamentales entre variables oceánicas** como temperatura, densidad, presión y velocidad, utilizando analogías con teorías físicas como la ecuación de Callan-Symanzik. Se desarrollan nuevas formulaciones y se simula el comportamiento del sistema ante perturbaciones.

## Contenido

- Simulaciones con distintos tipos de perturbaciones: temperatura, salinidad y topografía.
- Análisis de disipación energética del sistema.
- Estudio del efecto de parámetros clave (`a`, `α`) en la evolución del sistema.

## Estructura del repositorio

- `simulación sin perturbacion.ipynb`: modelo base con circulación sin alteraciones.
- `salinidad.ipynb`: perturbación por salinidad.
- `desnivel.ipynb`: perturbación por topografía.
- `disipacion.ipynb`, `disipacionvariandoa.ipynb`, `disipacionvariandoalpha.ipynb`: análisis de disipación energética.
- `ecuaciondiferencial.ipynb`, `solucionecuaciondiferencial.ipynb`: modelo basado en analogías con física de partículas.
