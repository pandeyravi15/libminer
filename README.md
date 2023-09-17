
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->

[![R-CMD-check](https://github.com/pandeyravi15/libminer/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/pandeyravi15/libminer/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of libminer is to …

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("pandeyravi15/libminer")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminer)
lib_summary()
#>                                                                                       Library
#> 1                        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
#> 2 /private/var/folders/l_/j1p3t8ms3vsf4g6n9wcl2450d_46rg/T/Rtmp8r0PeT/temp_libpath2208bc49aa3
#> 3                                                  /Users/pandera/Library/R/arm64/4.2/library
#>   n_packages
#> 1         29
#> 2          1
#> 3        482
lib_summary(sizes = TRUE)
#>                                                                                       Library
#> 1                        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
#> 2 /private/var/folders/l_/j1p3t8ms3vsf4g6n9wcl2450d_46rg/T/Rtmp8r0PeT/temp_libpath2208bc49aa3
#> 3                                                  /Users/pandera/Library/R/arm64/4.2/library
#>   n_packages   lib_size
#> 1         29   66559407
#> 2          1      14208
#> 3        482 4455233205
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
