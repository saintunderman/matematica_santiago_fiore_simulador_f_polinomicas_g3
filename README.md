# Análisis Algebraico de Ecuaciones Cúbicas

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Language: HTML/JS](https://img.shields.io/badge/Language-HTML5%20%2F%20JavaScript-blue.svg)](#)

Una herramienta interactiva, visual y educativa diseñada para explorar en profundidad las funciones de tercer grado ($ax^3 + bx^2 + cx + d = 0$). Este proyecto combina una calculadora con un módulo de aprendizaje sobre la historia y teoría de las ecuaciones cúbicas.

## Características Principales

- **Calculadora Interactiva:** Ajusta los coeficientes mediante sliders y observa los cambios en tiempo real.
- **Resolución Paso a Paso:** Desglose del proceso matemático, incluyendo la reducción de la ecuación (sustitución de Vieta) y el cálculo del discriminante ($\Delta$).
- **Visualización Avanzada (SVG):** - Gráficos dinámicos con detección de raíces.
  - Representación opcional de la derivada ($$f'(x)$$).
  - Análisis de concavidad y puntos de inflexión.
  - Marcado automático de puntos críticos (máximos y mínimos).
- **Contenido Teórico Riguroso:** Explicación de la fórmula de Cardano, el *Casus Irreductibilis* y las relaciones de Vieta.
- **Contexto Histórico:** Una línea de tiempo que recorre los duelos matemáticos del Renacimiento italiano entre Cardano, Tartaglia y Del Ferro.
- **Diseño Adaptativo (Responsive):** Optimizado para su uso en computadoras, tablets y dispositivos móviles.

## Tecnologías Utilizadas

- **HTML5 & CSS3:** Interfaz moderna basada en variables CSS, Flexbox y Grid.
- **JavaScript (Vanilla):** Lógica matemática personalizada para la resolución de raíces reales y complejas sin dependencias externas.
- **MathJax 3:** Para un renderizado impecable de fórmulas matemáticas en formato LaTeX.
- **SVG Dinámico:** Generación de gráficos vectoriales que mantienen la nitidez en cualquier nivel de zoom.

## Cómo usarlo

Acceso al Simulador: https://saintunderman.github.io/matematica_santiago_fiore_simulador_f_polinomicas_g3/

## Casos de Estudio Incluidos

El simulador permite experimentar directamente con ejemplos preconfigurados:
- **Una raíz real:** Casos donde el discriminante es negativo ($$\Delta < 0$$).
- **Raíces múltiples:** Cuando la curva es tangente al eje $$x$$ ($$\Delta = 0$$).
- **Tres raíces reales:** Exploración del método trigonométrico para resolver el caso irreductible.

