# NeuroscienceBench preprint

[Read the PDF](main.pdf). Build from the repository root with `make pdf` using
TeX Live (or MacTeX) and `latexmk`. The entry point is `main.tex`.

Sources were downloaded from the [Overleaf project](https://www.overleaf.com/project/6aedfed6eb1a1cf3d93ecee2)
on November 9, 2026. The house style is from
[benchmark-paper-template](https://github.com/latchbio/benchmark-paper-template),
with the Antibody Development paper as the layout reference.
`latchbench.sty` is unchanged; paper-specific spacing and pagination live in
`main.tex`. The data-type subsection is split into its own source file for placement.

`figures/` contains the five vector PDFs used by the Overleaf manuscript, unchanged.
The export's older figure versions, example paper, synthetic template data, and
template figure generator are omitted: they do not reproduce the neuroscience
results. Building the paper uses the supplied figures and does not regenerate them.
The manuscript's prose, numerical results, references, and author order are retained.
