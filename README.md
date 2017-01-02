Pulsatile
=========

[![Build Status](https://travis-ci.com/mmulvahill/pulsatile.svg?token=Vzy3B4WH2SvZ4ybN4Uzy&branch=master)](https://travis-ci.com/mmulvahill/pulsatile) [![codecov](https://codecov.io/gh/mmulvahill/pulsatile/branch/master/graph/badge.svg?token=WeMubsj4Is)](https://codecov.io/gh/mmulvahill/pulsatile)

An R package for analyzing time series of hormone concentrations using Bayesian deconvolution analysis.

Run the following code to install the development version:

``` r
# Need devtools package to install from GitHub
install.packages("devtools")
library(devtools)

# install from github
install_github("mmulvahill/pulsatile", auth_token)
```

Programming resources
=====================

[R source (math.h and internal.h)](https://github.com/wch/r-source) [C interface in Advanced R](http://adv-r.had.co.nz/C-interface.html) [R's RNG wrappers](https://svn.r-project.org/R/trunk/src/library/stats/R/distn.R) [R's rmultinom](https://svn.r-project.org/R/trunk/src/nmath/rmultinom.c)
