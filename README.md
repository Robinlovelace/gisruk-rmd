
<!-- README.md is generated from README.Rmd. Please edit that file -->

# gisruk-rmd

<!-- badges: start -->
<!-- badges: end -->

The goal of gisruk-rmd is to provide a template for GISRUK paper
submissions.

To use it:

1.  Edit the example-paper.Rmd document, e.g. by downloading this repo,
    opening the RStudio project and entering the following:

``` r
file.edit("example-paper.Rmd")
```

2.  Edit the minimal abstract and authors section in the updated
    `GISRUKPaperTemplate2015.tex` file, e.g. with:

``` r
file.edit("GISRUKPaperTemplate2015.tex")
```

When you’d like to see if it works, run the following command:

``` r
rmarkdown::render("example-paper.Rmd")
```

You can also press Ctrl+Shift+K in RStudio, which should result in see
something looking like this:

![](https://user-images.githubusercontent.com/1825120/148705156-a45645a9-00bc-41ff-874e-d018373c8a38.png)

To produce this document the original LaTeX template was downloaded as
follows:

``` bash
wget http://leeds.gisruk.org/paper_templates/GISRUKPaperTemplate2015-Latex.zip
unzip GISRUK*
```

See commits to see how it was modified to work as a .Rmd template.
