# Lecture Notes for CS 7290 Causality in Machine Learning

## Getting started

To contribute to this repository, you need to contribute individual pages in the form of ".Rmd" (R Markdown) files.  To compile the full set of lecture notes into HTML, you will need the [bookdown](https://bookdown.org/) R package.  Install the package and compile using the command:

```r
bookdown::render_book('index.Rmd', 'all')
```
Compiling the "causalml.Rproj" project file in [RStudio](https://www.rstudio.com/) will make things easier.  Read through the [bookdown documentation](https://bookdown.org/yihui/bookdown/) to learn more about bookdown, including how to format R Markdown documents.

## Using Python code in an Rmarkdown document

If you want to run Python code in an R Markdown file, use the [reticulate](https://github.com/rstudio/reticulate#python-in-r-markdown) package in R.

## Using Jupyter notebooks

If you prefer writing up lecture notes as Jupyter notebooks instead of R Markdown, you may try using [Jupytext](https://github.com/mwouts/jupytext) to export the notebooks into ".Rmd" files.

## Submitting lecture notes

To submit lecture notes to this repo, fork the repo, add your lecture notes, and create a pull request.  If working with other students, one student should create the PR.  Make sure you let us know in the PR description who you are, and which of your classmates worked with you on the lecture notes, so we can give you all credit for your work.

The course instructor or TAs may request changes to the PR.  If they do, make the requested changes promptly.  Only when the PR is approved do you and your partners get credit for lecture notes.  
