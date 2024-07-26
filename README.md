
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Experiment Calculator

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![Codecov test
coverage](https://codecov.io/gh/sabush/ExperimentCalculator/branch/master/graph/badge.svg)](https://app.codecov.io/gh/sabush/ExperimentCalculator?branch=master)
[![R-CMD-check](https://github.com/sabush/ExperimentCalculator/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/sabush/ExperimentCalculator/actions/workflows/R-CMD-check.yaml)
[![CircleCI build
status](https://circleci.com/gh/sabush/ExperimentCalculator.svg?style=svg)](https://circleci.com/gh/sabush/ExperimentCalculator)
<!-- badges: end -->

The goal of Experiment Calculator is to provide a simple calculator to
plan, analyse and diagnose simple experiments.

## Installation

You can install the development version of ExperimentCalculator like so:

``` r
devtools::install_github('sabush/ExperimentCalculator')
#> Using GitHub PAT from the git credential store.
#> Skipping install of 'ExperimentCalculator' from a github remote, the SHA1 (4d59fc09) has not changed since last install.
#>   Use `force = TRUE` to force installation
```

## Load the Calculator

To load the power and significance calculator, load the library and run
the app

``` r
library(ExperimentCalculator)
#ExperimentCalculator::run_app() # Uncomment to run the app
```

Further usage of the app can be found in the vignettes.

## Code of Conduct

Please note that the ExperimentCalculator project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
