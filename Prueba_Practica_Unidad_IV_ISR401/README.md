# ISR401 — Prueba Práctica Unidad IV — Vera Gómez

Repositorio con el desarrollo de la Prueba Práctica de la Unidad IV de la
asignatura Ingeniería de Requisitos (ISR-401), caso "Sistema de Gestión de
Pedidos".

**Estudiante:** Anthony Alfredo Vera Gómez
**Docente:** Ing. Gleiston Guerrero, Mg.
**Repositorio:** https://github.com/Misantho7/ISR401-prueba-U4-vera-gomez

## Estructura del repositorio

```
.
├── main.tex                  # Archivo principal (carátula + P1–P10)
├── img/
│   └── captura_evaluacion.png  # Captura de la evaluación del cuestionario (SGA)
├── main.pdf                  # PDF compilado (resultado final)
└── README.md
```

## Requisitos / dependencias

- Distribución LaTeX con **TeX Live** (o equivalente) que incluya los
  paquetes: `geometry`, `inputenc`, `fontenc`, `tikz` (con librerías
  `arrows.meta`, `positioning`, `shapes.geometric`), `booktabs`,
  `longtable`, `array`, `enumitem`, `titlesec`, `hyperref`, `graphicx`.
- Compilador: **pdflatex**.

## Instrucciones de compilación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Misantho7/ISR401-prueba-U4-vera-gomez.git
   cd ISR401-prueba-U4-vera-gomez
   ```
2. Compilar el archivo principal (se recomienda ejecutar el comando dos
   veces para asegurar referencias e hipervínculos correctos):
   ```bash
   pdflatex main.tex
   pdflatex main.tex
   ```
3. El PDF resultante se genera como `main.pdf` en la raíz del repositorio.

**Archivo principal:** `main.tex`
**Sin archivo `referencias.bib`** (no se citan referencias bibliográficas
en el desarrollo).

