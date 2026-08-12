# Prueba Práctica - Unidad IV (Ingeniería de Requisitos)

Estudiante: Gamarra Zárate Jamileth
Docente: Ing. Gleiston Guerrero, Mg.
Caso: Sistema de Gestión de Pedidos

## Qué hay en este repo

- `main.tex` -> el archivo con todas las respuestas (P1 a P10).
- `main.pdf` -> el PDF ya compilado, es el que se entrega en el SGA.
- `diagrama_de_clases.png` -> el diagrama de clases de P1.
- `README.md` -> este archivo.

## Cómo compilar

Compilar significa convertir el archivo main.tex en el PDF final.
Se hace con el programa pdflatex, escribiendo esto en la terminal,
dentro de la carpeta del proyecto:

pdflatex main.tex
pdflatex main.tex


Se escribe dos veces el mismo comando (se corre dos veces) para que
todo quede bien ordenado en el PDF final.

El archivo principal que se compila es `main.tex`.

Si se compila en Overleaf: se sube toda la carpeta (incluyendo figuras/),
se marca `main.tex` como documento principal, y se compila con pdfLaTeX.

## Paquetes que usa

babel (español), geometry, fancyhdr, graphicx, tikz, array, longtable,
booktabs, xcolor, enumitem, hyperref. Son los normales de cualquier
instalación completa de TeX Live o MiKTeX, no hay que instalar nada aparte.

## Nota

La imagen `diagrama_de_clases.png` debe estar dentro de la carpeta
`figuras/` con ese nombre exacto, porque así la busca el main.tex.
Si no está ahí o tiene otro nombre, el PDF no se genera.
