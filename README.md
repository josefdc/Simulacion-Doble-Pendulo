# 🕺 Simulación de Péndulo Doble 🕺

Este repositorio contiene una simulación y animación de un péndulo doble, implementado en Octave, así como un documento LaTeX asociado.

## 📁 Contenido

- **double_pendulum_simulation.m:** Función principal que simula y anima el movimiento del péndulo doble.
- **main.tex:** Documento LaTeX principal.

![Animación del Péndulo Doble](LaTex/bloggif_653031ffd30c5.gif)

## 🛠 Requisitos

- 📊 Octave
- 📄 Paquetes LaTeX (si quieres compilar el documento)

## 🚀 Uso

1. Abre Octave.
2. Navega al directorio donde se encuentra el script `double_pendulum_simulation.m`.
3. Ejecuta `double_pendulum_simulation()`.

Esto iniciará la simulación y animación del péndulo doble.

## 📚 Documentación

- **double_pendulum_simulation()**: Realiza una simulación del péndulo doble y anima su movimiento.
- **pendulumODE(y, t, p)**: Define las ecuaciones diferenciales que rigen el movimiento del péndulo doble.
- **animate_pendulum(t, y, p)**: Crea una animación del péndulo doble usando la solución del sistema de ecuaciones diferenciales.

## 📑 Generar Documento LaTeX

Para generar el documento LaTeX:

1. Navega al directorio que contiene `main.tex`.
2. Ejecuta `pdflatex main.tex`.

Esto generará un PDF con el contenido del documento LaTeX.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Siéntete libre de abrir un problema o hacer un pull request.

## 📜 Licencia

[MIT License]
