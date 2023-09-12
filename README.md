# Source code for the master thesis

You need TexLive and Pygments (for Minted).  Compile with:

```console
$ cd thesis/
$ latexmk -pdflatex -shell-escape thesis.tex
```

Diagram sources in OmniGraffle format is at `diagrams.graffle`.  The Corundum repo is added as a submodule; clone this if you wish to reproduce the data charts.
