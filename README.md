# Introduction

This repository is a store of resources for Access Project tutorials. This is an experimental project to use Jupyter notebooks to create resources for mathematics tuition.

# Use

A notebook's contents may be exported to TeX format within Jupyter. Then, the command

```{bash}
sed '/\\begin{tcolorbox}/,/\\end{tcolorbox}/d'
```

may be used to remove code cells from the LaTeX file before manual compilation. Some manual adjustments of this file (*e.g.* in relation to section numbering and title) may be necessary.

