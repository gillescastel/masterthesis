# Master thesis

## * Morse theory*: a visual guide from handlebodies to Floer homology


I'm doing my masters thesis at KU Leuven in Belgium on Morse theory under the supervision of Charltote Kirchhoff-Lukat.
It is currently a work in progress and should be completed in the beginning of June 2021.

### Goal

The goal of the thesis is to state and prove some important results in classical Morse theory, including:

* Existence of Morse functions
* Handlebody decomposition
* Definition of Morse homology and the fact that it does not depend on the chosen Morse function/gradient vector field
* Morse homology is isomorphic to singular homology
* Morse inequalities
* h-cobordism theorem, from which the higher dimensional Poincaré conjecture follows
* An introduction to Floer homology.

### Target audience

The thesis should be accessible to mathematics master students with basic knowledge of differential geometry. To ease the understanding of the geometrical proofs, the thesis also contains more than 100 figures.

### Template

Feel free to use this thesis as a template. It is inspired by the work of Edward Tufte.

### Compiling

Use `latexmk` to compile the thesis:
```sh
cd thesis
latexmk master.tex
```

Note that I use BibLaTeX (not BibTeX) so be aware of this if you're compiling this with something else than `latexmk`.
You can also download the latest version as follows

1. Click on Actions (located on the top)
1. Click on the latest commit with a green checkmark
1. Click on master.pdf to download the file
