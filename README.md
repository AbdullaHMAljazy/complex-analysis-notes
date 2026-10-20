# Complex Analysis Master Course Notes

Lecture notes and examples for the Complex Analysis Master Course, taught by
Dr. Saja Hayajneh. The LaTeX source was typed by Abdullah Aljazy.

## Files

- [`complex.pdf`](complex.pdf) — ready-to-read notes.
- [`complex.tex`](complex.tex) — LaTeX source used to create the PDF.

## Topics covered

- Rectangular and polar forms of complex functions
- Complex limits, continuity, and differentiability
- Cauchy--Riemann equations and analyticity
- Isolated singularities, poles, non-isolated singularities, and logarithmic
  branch points

## Build the PDF

Install a LaTeX distribution that includes `pdflatex` and the standard
`amsmath`, `amsthm`, and `amssymb` packages. From this folder, run:

```sh
pdflatex -interaction=nonstopmode -halt-on-error complex.tex
pdflatex -interaction=nonstopmode -halt-on-error complex.tex
```

Running twice refreshes the table of contents and other generated references.
The source is self-contained; no extra image files are required.

## Sharing

These notes are shared as course study material. Please retain the attribution
in the source and follow your course's rules when redistributing or reusing
lecture material.
