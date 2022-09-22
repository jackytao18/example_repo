Simple document
================

``` r
library(tidyverse)
library(ggplot2)
```

I’m an R Markdown document!

# Section 1

Here’s a **code chunk** that samples from a *normal distribution*:

``` r
samp = rnorm(100)
length(samp)
```

    ## [1] 100

# Section 2

The mean is 0.06.

# Section 3

![](template_files/figure-gfm/chunk_assessment%201-1.png)<!-- --> The
median of the variable containing absolute values is 1.12

-   Mean 1.0498327
-   Median 1.0737222
-   Standard Deviation 1.0114853
