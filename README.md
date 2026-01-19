# Modelo conceptual mecanicista de ENSO

Este repositorio contiene un **modelo conceptual mecanicista de baja dimensión** del fenómeno ENSO (El Niño–Southern Oscillation), implementado en Python y diseñado con fines docentes.

El objetivo del material no es reproducir ENSO de forma realista, sino **analizar cómo una variabilidad climática organizada puede emerger** a partir de la interacción entre un número reducido de procesos dominantes, formulados de manera explícita en un sistema dinámico simple.

El repositorio forma parte de las actividades prácticas de una asignatura centrada en **modelos climáticos**, y está alineado con un enfoque de jerarquía de modelos y aislamiento de fenómenos.

---

## Contenido del repositorio

- `notebooks/ENSO_recharge_oscillator.ipynb`  
  Notebook principal con el desarrollo del modelo y las actividades guiadas.
- `environment.yml`  
  Definición del entorno de Python para garantizar la reproducibilidad (Binder).
- `figures/`  
  Figuras utilizadas en el notebook (si procede).

---

## Ejecución en Binder

El notebook puede ejecutarse directamente en la nube, sin necesidad de instalación local, a través de Binder:

[![Abrir en Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/USUARIO/REPOSITORIO/HEAD)

Al pulsar el enlace se abrirá un entorno interactivo con el notebook listo para su ejecución.

---

## Alcance y limitaciones

El modelo implementado es deliberadamente simple:

- no reproduce patrones espaciales realistas,
- no está diseñado para realizar proyecciones climáticas,
- no permite una comparación cuantitativa directa con observaciones.

Su finalidad es **pedagógica y conceptual**, centrada en la comprensión de mecanismos dinámicos, retroalimentaciones y escalas temporales.

---

## Licencia

Material de uso docente.  
Salvo indicación contraria, el contenido se distribuye bajo una licencia abierta para fines educativos.
