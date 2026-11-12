# Apuntes de Lógica

Apuntes de la asignatura Lógica, 2.º del Grado en Filosofía de la Universidad de Sevilla.

- **El libro:** [`ApuntesLogica.pdf`](ApuntesLogica.pdf).
- **Las aplicaciones web para practicar:** https://fersoler.github.io/AplicacionesLogica/ (código en [fersoler/AplicacionesLogica](https://github.com/fersoler/AplicacionesLogica), licencia GPLv3). La guía para los alumnos es [`guia_aplicaciones.pdf`](guia_aplicaciones.pdf).

## Contenido

`ApuntesLogica.tex`, en la raíz, es el documento principal. El resto de los ficheros están en dos directorios:

- **`comun/`:** el preámbulo (`preambulo_comun.tex`).
- **`capitulos/`:** los temas y los apéndices.

| Tema | Ficheros de `capitulos/` |
|---|---|
| 1. Deducción natural en lógica proposicional | `cap1_teoria.tex`, `cap1_ejercicios.tex` |
| 2. Semántica de la lógica proposicional | `cap2_teoria.tex`, `cap2_ejercicios.tex` |
| 3. Metalógica proposicional: corrección y completud | `cap3_metalociga.tex` (con sus ejercicios) |
| 4. Deducción natural en lógica de primer orden | `cap4_teoria.tex`, `cap4_ejercicios.tex` |
| 5. Semántica de la lógica de primer orden | `cap5_teoria.tex`, `cap5_ejercicios.tex` |
| 6. El cálculo de tableaux | `cap6_teoria.tex`, `cap6_ejercicios.tex` |
| Apéndices A–D: conjuntos, Henkin, resumen de reglas, soluciones | `cap_apendice_conjuntos.tex`, `apendice_henkin.tex`, `apendice_resumen_reglas.tex`, `apendice_soluciones.tex` |

`guia_aplicaciones.tex` es un documento aparte, con su PDF.

## Compilar

Con una instalación completa de TeX Live (usa, entre otros, los paquetes `fitch`, `tikz` y `fontawesome5`):

```
latexmk -pdf ApuntesLogica.tex
```

La dirección de las aplicaciones está en la macro `\urlaplicaciones` de `comun/preambulo_comun.tex`.

## Erratas

Se pueden comunicar abriendo una *issue* en este repositorio.

## Licencia

[Creative Commons Atribución-CompartirIgual 4.0 Internacional (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/). El texto completo está en `LICENSE`.
