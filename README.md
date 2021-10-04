# Master thesis: Morse Theory

## *A visual guide from handlebodies to the generalized Poincaré conjecture*


I did my masters thesis at KU Leuven in Belgium on Morse theory under the supervision of Charlotte Kirchhoff-Lukat on Morse theory.

### Goal

The goal of the thesis is to state and prove some important results in classical Morse theory, including:

* Existence of Morse functions
* Handlebody decomposition
* Definition of Morse homology and the fact that it does not depend on the chosen Morse function/gradient vector field
* Morse homology is isomorphic to singular homology
* Morse inequalities
* h-cobordism theorem, from which the higher dimensional Poincaré conjecture follows

### Target audience

The thesis should be accessible to mathematics master students with basic knowledge of differential geometry. To ease the understanding of the geometrical proofs, the thesis also contains more than 100 figures.

### Template

Feel free to use this thesis as a template. It is inspired by the work of Edward Tufte.
![2021_10_04_001](https://user-images.githubusercontent.com/7069691/135912959-b73f2080-ad53-40d3-bd45-ee54fac604d0.png)
![2021_10_04_002](https://user-images.githubusercontent.com/7069691/135912965-37c8ddf9-4d93-4c59-9f89-a9fc03d4dd4a.png)
![2021_10_04_003](https://user-images.githubusercontent.com/7069691/135912973-a7eaceff-9cb8-4dda-ab87-7a19f5358718.png)




### Compiling

Use `latexmk` to compile the thesis:
```sh
cd thesis
latexmk master.tex
```

Note that I use BibLaTeX (not BibTeX) so be aware of this if you're compiling this with something else than `latexmk`.
