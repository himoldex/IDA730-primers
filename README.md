
<!-- README.md is generated from README.Rmd. Please edit that file -->

# him.ida730

The goal of `him.ida730` R package is to provide students access to
repository with selected interactive course materials locally (offline).
The package is hosted on GitHub at `himoldex/him.ida730` as public
repository.

## Installation of the package

You can install the latest version of `him.ida730` in RStudio as
follows:

-   by executing the code below iteratively (line by line) in console of
    RStudio
-   by running the copied code from within a new document (`*.r`,
    `*.rmd`, etc..) inside of your R Project

``` r
# install necessary package
install.packages("devtools")

# load installaed package
library(devtools)

# run the code chunk in RStudio
devtools::install_github("himoldex/him.ida730")
```

It is recommended that you create New Project(s) for course work in
RStudio and save them locally on your disk. It is possible to save your
work on GitHub as private repository to access the course materials from
any PC or browser from within RStudio Cloud account at some point in the
future.

## Example

This is a basic example which shows you how to interact with included
tutorials:

``` r
#library(him.ida730)

# Load an available interactive file in `him.ida730`,
# specify only first argument (see example):
# primer1   : "Programming Basics"    (adopted from rstudio-education/primers)
# primer2   : "Visualization Basics"  (adopted from rstudio-education/primers)
#learnr::run_tutorial("primer1", "him.ida730")
```
