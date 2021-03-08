

# tcctemplate 0.0.1

<!-- [![Build Status](https://travis-ci.org/leg-ufpr/legtheme.svg?branch=master)](https://travis-ci.org/leg-ufpr/legtheme) -->

DEST UFPR template for documents.

## Usage

<!-- After installing (sse below), you can create a draft document from one -->
<!-- of the themes available: -->

<!-- - `beamer_leg` is a theme for beamer slides -->
<!-- - `proj_generico` is a theme for a generic project or any other similar -->
<!--   document in PDF -->

To create a draft for use:


```r
library(rmarkdown)
draft(file = "projeto.Rmd", template = "projeto_template",
      package = "tcctemplate", create_dir = FALSE, edit = FALSE)
```
This will create (in the current directory) a file named `proj.Rmd`
which can be further rendered with


```r
render("proj.Rmd")
```

<!-- Similarly, to create a draft document for the `proj_generico` theme, -->
<!-- just use: -->



## Download and install

The easiest way to install is directly from this repository with the
**remotes** (or **devtools**) packages


```r
remotes::install_github("fernandomayer/tcctemplate")
```

## Authors

- [Fernando de Pol Mayer][]

## License

MIT. See [LICENSE](./LICENSE)

<!-- links -->


[Fernando de Pol Mayer]: http://www.leg.ufpr.br/~fernandomayer
