
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminder

<!-- badges: start -->
<!-- badges: end -->

The goal of libminder is to help you understand your libraries …..

## Installation

You can install the development version of libminder from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("JiangShangZY/libminder")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(libminder)

lib_summary()
#>                                                                  Library
#> 1                                     C:/Program Files/R/R-4.3.1/library
#> 2                        C:/Users/lewang/AppData/Local/R/win-library/4.3
#> 3 C:/Users/lewang/AppData/Local/Temp/RtmpQ9zFSy/temp_libpathab9c411a5d08
#>   n_packages
#> 1         30
#> 2        280
#> 3          1

# Also can calculate sizes
lib_summary( sizes = TRUE )
#>                                                                  Library
#> 1                                     C:/Program Files/R/R-4.3.1/library
#> 2                        C:/Users/lewang/AppData/Local/R/win-library/4.3
#> 3 C:/Users/lewang/AppData/Local/Temp/RtmpQ9zFSy/temp_libpathab9c411a5d08
#>   n_packages   lib_size
#> 1         30   68858812
#> 2        280 3921810091
#> 3          1      13253
```
