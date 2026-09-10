# STA347 Lecture Notes

Typed-up lecture notes for **STA347 (Probability Theory)**, converted from handwritten notes into clean, typeset PDFs using LaTeX.

## Contents

| File | Topics Covered |
|------|-----------------|
| `Lec1_Set_Theory_Fundamentals.tex` / `.pdf` | Basic set operations · Convergence of real-valued sequences · Pointwise vs. uniform convergence of functions · Supremum & infimum · limsup / liminf · Left & right limits of functions |
| `Lec2_Probability_Measure.tex` / `.pdf` | Sample space · Probability measure axioms (STA 347 version) · Coin-flip & Lebesgue measure examples · Basic properties of probability measures · Subadditivity (Lemma 2.4) · Countable sets have Lebesgue measure zero (Lemma 2.5) |

## About

These notes follow the course's development of probability theory from its set-theoretic foundations:

- **Set theory basics** — union, intersection, complement
- **Sequence convergence** — the ε–N definition, and its extension to sequences of functions (pointwise vs. uniform convergence)
- **Limiting processes** — supremum, infimum, and how they differ from max/min; limsup and liminf for sequences that don't converge
- **Function limits** — one-sided limits and their relationship to the two-sided limit
- **Probability measures** — the axioms defining a probability measure on a sample space, basic derived properties (complement rule, monotonicity, inclusion-exclusion), subadditivity, and the Lebesgue measure of countable sets

Definitions are boxed and highlighted, with explanatory notes and worked examples included alongside each concept, mirroring the structure of the original handwritten lecture.

## Build

The notes are written in LaTeX. To compile locally:

```bash
pdflatex Lec1_Set_Theory_Fundamentals.tex
pdflatex Lec1_Set_Theory_Fundamentals.tex   # run twice for correct numbering/references

pdflatex Lec2_Probability_Measure.tex
pdflatex Lec2_Probability_Measure.tex
```

Requires a standard LaTeX distribution (e.g. TeX Live, MiKTeX) with the `amsmath`, `amssymb`, `amsthm`, `enumitem`, `xcolor`, `titlesec`, and `tikz` packages.

## License

For personal study use.
