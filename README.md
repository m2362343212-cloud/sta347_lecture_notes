# STA347 Lecture Notes

Typed-up lecture notes for **STA347 (Probability Theory)**, converted from handwritten notes into clean, typeset PDFs using LaTeX.

## Contents

| File | Topics Covered |
|------|-----------------|
| `Lec1_Set_Theory_Fundamentals.tex` / `.pdf` | Basic set operations · Convergence of real-valued sequences · Pointwise vs. uniform convergence of functions · Supremum & infimum · limsup / liminf · Left & right limits of functions |

## About

These notes follow the course's development of probability theory from its set-theoretic foundations:

- **Set theory basics** — union, intersection, complement
- **Sequence convergence** — the ε–N definition, and its extension to sequences of functions (pointwise vs. uniform convergence)
- **Limiting processes** — supremum, infimum, and how they differ from max/min; limsup and liminf for sequences that don't converge
- **Function limits** — one-sided limits and their relationship to the two-sided limit

Definitions are boxed and highlighted, with explanatory notes and worked examples included alongside each concept, mirroring the structure of the original handwritten lecture.

## Build

The notes are written in LaTeX. To compile locally:

```bash
pdflatex Lec1_Set_Theory_Fundamentals.tex
pdflatex Lec1_Set_Theory_Fundamentals.tex   # run twice for correct numbering/references
```

Requires a standard LaTeX distribution (e.g. TeX Live, MiKTeX) with the `amsmath`, `amssymb`, `amsthm`, `enumitem`, `xcolor`, and `titlesec` packages.

## License

For personal study use.
