# CHM328: Density Functional Theory Guest Lectures

Two-lecture series on Density Functional Theory for Modern Physical Chemistry at the University of Toronto (Winter 2026).

## Contents

```
CHM328/
├── lecture1/
│   ├── slides/                  # Beamer source + compiled PDF
│   │   ├── CHM328_DFT_Lecture1.pdf
│   │   └── CHM328_DFT_Lecture1.tex
│   └── figures/                 # Figures used in slides
│
├── lecture2/
│   ├── slides/
│   │   ├── CHM328_DFT_Lecture2.pdf
│   │   └── CHM328_DFT_Lecture2.tex
│   └── figures/
│
└── notes/                       # Companion notes (LaTeX + PDF)
    ├── lecture1_notes.tex
    ├── lecture1_notes.pdf
    ├── lecture2_notes.tex
    └── lecture2_notes.pdf
```

## Prerequisites

Students should have familiarity with:
- Quantum mechanics (wavefunctions, operators, eigenvalue problems)
- Statistical thermodynamics (partition functions, entropy, free energy)
- Molecular orbital theory basics

## Building from Source

```bash
cd lecture1/slides && pdflatex CHM328_DFT_Lecture1.tex
cd ../../notes && pdflatex lecture1_notes.tex
```
