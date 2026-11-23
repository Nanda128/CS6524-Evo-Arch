# EvoMorph

EvoMorph is a proposed 2D evolutionary robotics system that will co-evolve creature morphology and joint controllers for locomotion.

## Current status

Initial research and design proposal only. No working evolutionary engine or physics simulation is claimed yet.

## Research journal

The LaTeX source is in `journal/main.tex`, with BibTeX references in `journal/main.bib`.

Build locally using:

```bash
cd journal
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Research question

Under an equal fitness-evaluation budget, does co-evolving virtual-creature morphology and joint-control parameters improve locomotion performance relative to evolving joint control alone with a fixed morphology?

## Repository

The project will include custom EA source code, tests, experiment scripts, presentation materials and a chronological research/design journal. Add the lecturer's GitHub account `@dearg` as a collaborator.
