
<!-- README.md is generated from README.Rmd. Please edit that file -->

# toy.doubler

<!-- badges: start -->
<!-- badges: end -->

The goal of toy.doubler is to practice creating a package and publishing
it on github. The included function toy_double() will double a numerical
vector.

## Installation

You can install the development version of toy.doubler from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jlolavesen/toy.doubler")
```

## Example

This is a basic example:

``` r
library(toy.doubler)
## basic example code
x <- c(1,3,9)
toy_double(x)
#> [1]  2  6 18
```
