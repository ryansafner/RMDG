# R Markdown: A Modest Guide

**Note to Students**: This guide is available on [my website](http://ryansafner.com/tutorial/RMDG.html), which Blackboard will link to. The source files are also available [on GitHub](http://github.com/ryansafner/RMDG)

**Note to Everyone Else**: This guide is oriented primarily for my [Econometrics class](http://ryansafner.com/courses/econ480) at Hood College, but should be of wider use to anyone interested in learning `R` for data analysis. Lecture slides, handouts, and guides (both PDFs and source code in R Markdown) are openly available [on GitHub](http://github.com/ryansafner/ECON480/).

**See also my companion guide to using R** hosted on [my website](http://ryansafner.com/tutorial/R4EH.html), with source available also [on GitHub](http://github.com/ryansafner/R4EH)

This repository comes with several files to help you practice learning `R Markdown`:

- `RMDG.Rmd` is the raw `R Markdown` file (`.Rmd`) that generates the readable guide
- `RMDG.html` is the readable guide in `html` form, simply download and open in any web browser
- `Rmd_practice.Rmd` is a raw `.Rmd` that you can edit and then `knit` to produce an `html` file with your answers.
- `Rmd_practice.html` is a readable `html` output of the `.Rmd` file: you can't edit it, but it is what the final product will look like.
- `Rmd_practice_answers.Rmd` contains the answers to the practice questions, in the raw `.Rmd` format, which can be `knit`ted to produce:
- `Rmd_practice_answers.html` is the readable final product as `html` output
- `bibexample.bib` is an example bibliography `.bib` file used as a demonstration in the guide
- `mybib.bib` is an example bibliography `.bib` file for practicing citations in the `Rmd_practice` files. 
- `econfreedom.csv` is the dataset used in the `Rmd_practice` questions
- `From_rmd_to_latex_to_pdf` shows how `knit` converts `.Rmd` into `.tex` into `pdf`, showing what the code (or output) looks like at each stage (see both the raw `.Rmd` and the final `pdf`)