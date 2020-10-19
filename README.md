
<!-- README.md is generated from README.Rmd. Please edit that file -->

# dummy

<!-- badges: start -->

<!-- badges: end -->

The goal of dummy is to teach ME how to create R packages.

## Installation

You can install dummy from from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("petestylianos/dummy")
```

## Example

This is a basic example which shows you how to solve a common problem
with dummy:

It produces 10 random numbers from the standard normal distribution.
Very serious stuff.

``` r
library(dummy)
library(tibble)
library(magrittr)
dummy::random_numbers %>% 
  as_tibble()
#> # A tibble: 10 x 1
#>       value
#>       <dbl>
#>  1 -0.521  
#>  2  0.121  
#>  3  1.26   
#>  4  0.629  
#>  5 -0.875  
#>  6  0.734  
#>  7 -0.498  
#>  8  0.00855
#>  9  0.619  
#> 10  0.633
```

More examples to come soon.
