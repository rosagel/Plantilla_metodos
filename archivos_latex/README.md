# 📄 Archivos LaTeX

Esta carpeta contiene los reportes, tareas y documentos escritos en **LaTeX**
relacionados con el curso de Métodos Numéricos II.

## Estructura sugerida

```
archivos_latex/
├── reporte_01/
│   ├── reporte_01.tex
│   └── reporte_01.pdf
├── tarea_01/
│   └── tarea_01.tex
└── plantilla_base.tex
```

## Plantilla base recomendada

```latex
\documentclass[12pt]{article}
\usepackage[utf8]{inputenc}
\usepackage[spanish]{babel}
\usepackage{amsmath, amssymb}
\usepackage{graphicx}
\usepackage{listings}
\usepackage{hyperref}

\title{Título del Reporte}
\author{Sergio SKA27}
\date{\today}

\begin{document}
\maketitle

\section{Introducción}
% Tu contenido aquí

\end{document}
```

## Consejos

- Compila con `pdflatex` o usa [Overleaf](https://www.overleaf.com) en línea.
- Incluye siempre el `.pdf` generado para facilitar la revisión.
- Usa `\lstinputlisting{archivo.py}` para insertar código Python en el reporte.
