
<!-- README.md is generated from README.Rmd. Please edit that file -->

# gisruk-rmd

<!-- badges: start -->
<!-- badges: end -->

The goal of gisruk-rmd is to provide a template for GISRUK paper
submissions that enables reproducible manuscripts to be submitted with
embedded R, Python or other code, based on the [RMarkdown superset of
LaTeX](https://rmarkdown.rstudio.com/). At some point it may also work
with ‘.qmd’ [Quarto](https://quarto.org/) documents, which allows
[conversion](https://quarto.org/docs/tools/jupyter-lab.html#converting-notebooks)
to and from IPython notebooks.

It will create nicely formatted pdf documents, like this:
<https://github.com/Robinlovelace/gisruk-rmd/releases/download/0.22/example-paper.pdf>

Reproduce that file and create your own reproducible geographic data
analysis paper as follows:

1.  Edit the example-paper.Rmd document, e.g. by [downloading this repo
    as a .zip
    file](https://github.com/Robinlovelace/gisruk-rmd/archive/refs/heads/main.zip),
    unzipping it, opening the RStudio project and entering the
    following:

``` r
file.edit("example-paper.Rmd")
```

2.  Edit the minimal abstract and authors section in the updated
    `GISRUKPaperTemplate.tex` file, e.g. with:

``` r
file.edit("GISRUKPaperTemplate.tex")
```

When you’d like to see if it works, run the following command:

``` r
rmarkdown::render("example-paper.Rmd")
```

You can also press Ctrl+Shift+K in RStudio, which should result in see
something looking like this:

![](https://user-images.githubusercontent.com/1825120/148705536-d52866d7-f121-4da2-a0b2-f0904d8afddf.png)

To produce this document the original LaTeX template was downloaded as
follows:

``` bash
wget http://leeds.gisruk.org/paper_templates/GISRUKPaperTemplate2015-Latex.zip
unzip GISRUK*
```

See commits to see how it was modified to work as a .Rmd template.
