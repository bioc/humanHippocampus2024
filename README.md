# humanHippocampus2024

<!-- badges: start -->

[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental) [![check-bioc](https://github.com/christinehou11/humanHippocampus2024/actions/workflows/check-bioc.yml/badge.svg)](https://github.com/christinehou11/humanHippocampus2024/actions/workflows/check-bioc.yml) [![Codecov test coverage](https://codecov.io/gh/christinehou11/humanHippocampus2024/graph/badge.svg)](https://app.codecov.io/gh/christinehou11/humanHippocampus2024)

<!-- badges: end -->

Welcome to the `humanHippocampus2024` package! This package helps to access the spatially-resolved transcriptomics (SRT) and single-nucleus RNA-sequencing (snRNA-seq) data from adjacent tissue sections of the anterior human hippocampus across ten adult neurotypical donors generated by Lieber Institute for Brain Development (LIBD) researchers and collaborators.

## Installation

You can install humanHippocampus2024 like so:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("humanHippocampus2024")

## Check that you have a valid Bioconductor installation
BiocManager::valid()
```

The development version can be installed from GitHub:

``` r
install.packages("remotes")
remotes::install_github("christinehou11/humanHippocampus2024")
```

Please read [Introduction to humanHippocampus2024](https://christinehou11.github.io/humanHippocampus2024/articles/humanHippocampus2024.html) for detailed descriptions and tutorials.

## Code of Conduct

Please note that the humanHippocampus2024 project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html). By contributing to this project, you agree to abide by its terms.
