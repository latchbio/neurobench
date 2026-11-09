# NeuroscienceBench

**Benchmarking AI agents on neuroscience data analysis**

Tests whether AI agents can reach correct scientific conclusions from neuroscience research data. Agents get the same data a neuroscientist would, from sequencing, electrophysiology, optical physiology, EEG, brain-computer interface decoding, cell and tissue imaging, behavioral scoring and clinical biomarkers, and return a structured answer that is graded deterministically. Each task centers on an analytical or reasoning trap that a careful scientist would avoid. Scores show the share of attempts that reach the correct answer, counting refusals and errors as failures. A higher score means the model is more accurate at these tasks.

In this repo, there are 3 public example tasks that use the same structure and content as benchmark questions.

The [preprint PDF](paper/main.pdf) and [LaTeX sources](paper/README.md) are in
`paper/`. Build with `make pdf` (TeX Live and `latexmk` required).

## License

Apache 2.0 - see [LICENSE](LICENSE).
