# Prueba Práctica - Unidad IV (Ingeniería de Requisitos)

Estudiante: Gamarra Zárate Jamileth
Docente: Ing. Gleiston Guerrero, Mg.
Caso: Sistema de Gestión de Pedidos

## Descripción del Repositorio

Este repositorio contiene los archivos fuentes en LaTeX, recursos gráficos e instrucciones necesarias para compilar la documentación correspondiente a la Evaluación Práctica de la Unidad IV.

---

## Instrucciones de Compilación y Reproducibilidad

El archivo PDF compilado se genera a partir del código fuente LaTeX (`main.tex`). Siga las instrucciones a continuación según su entorno de trabajo:

### Requisitos y Dependencias
* **Compilador:** `pdflatex` (incluido en TeX Live, MiKTeX o MacTeX).
* **Paquetes LaTeX requeridos:** `inputenc`, `babel` (spanish), `geometry`, `fancyhdr`, `graphicx`, `tikz`, `array`, `longtable`, `booktabs`, `xcolor`, `enumitem`, `hyperref`.

### Compilación desde Terminal (CLI)
1. Clone el repositorio e ingrese a la carpeta del proyecto.
2. Ejecute el compilador `pdflatex` **dos veces consecutivas** para resolver correctamente la numeración de páginas, referencias cruzadas e hipervínculos:

```bash
pdflatex main.tex
pdflatex main.tex
```

---

## Estructura de Archivos del Repositorio

```text
.
├── main.tex                 # Archivo fuente principal con el desarrollo de P1 a P10
├── main.pdf                 # Documento final compilado
├── README.md                # Instrucciones de reproducibilidad del repositorio
└── figuras/                 # Archivos de imágenes y recursos gráficos
    ├── diagrama_de_clases.png   # Diagrama de clases UML (P1)
    ├── resumen_cuestionario.png # Captura 1: Resumen de cuestionario SGA
    └── captura_intento.png      # Captura 2: Revisión de intento SGA
```
---

### Recomendación importante para `main.tex`
Si tus imágenes están dentro de una carpeta llamada `figuras/`, asegúrate de incluir el nombre de la carpeta en las llamadas de `main.tex`, por ejemplo:
* `\includegraphics[width=\textwidth]{figuras/diagrama_de_clases.png}`
* `\includegraphics[width=0.85\textwidth]{figuras/resumen_cuestionario.png}`
* `\includegraphics[width=0.85\textwidth]{figuras/captura_intento.png}`
