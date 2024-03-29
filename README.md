
<!-- README.md is generated from README.Rmd. Please edit that file -->

## IDA730-primers

The goal of `IDA730-primers` R package is to provide students access to
repository with selected interactive course materials locally (offline).
The package is hosted on GitHub at `himoldex/IDA730-primers` as public
repository.

### Installation of the package

You can install the latest version of `IDA730-primers` in RStudio as
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
devtools::install_github("himoldex/IDA730-primers")
```

### Loading a tutorial

Please take a look at the list of topics with examples and exercises
that you can practice with following interactive tutorials. The
tutorials are split into four sections that cover the basics, how to
tidy and transform data, and visualize data while performing exploratory
data analysis:

``` r
#library(IDA730-primers)

# Work offline with interactive tutorials available at RStudio in `IDA730-primers`:
#----------------------------------------------
# Section 1 : The Basics
#----------------------------------------------
# primer1-1 : "Data Visualization Basics"
# primer1-2 : "Programming Basics"

#----------------------------------------------
# Section 2 : Transform and Work with Data
#----------------------------------------------
# primer2-1 : "Working with Tibbles"
# primer2-2 : "Isolating Data with dplyr"
# primer2-3 : "Deriving Information with dplyr"

#----------------------------------------------
# Section 3 : Visualize Data
#----------------------------------------------
# primer3-1 : "Exploratory Data Analysis"
# primer3-2 : "Bar Charts"
# primer3-3 : "Histograms"
# primer3-4 : "Boxplots and Counts"
# primer3-5 : "Scatterplots"
# primer3-6 : "Line Plots"
# primer3-7 : "Overplotting and Big Data"
# primer3-8 : "Customize Your Plots"

#----------------------------------------------
# Section 4 : Tidy Data
#----------------------------------------------
# primer4-1 : "Reshape Data"
# primer4-2 : "Separate Columns"
# primer4-3 : "Join Data Sets"

# To load a specific tutorial execute a following command:
#learnr::run_tutorial("primer1-1", "IDA730-primers")

# Source:
# https://rstudio.cloud/learn/primers
# https://github.com/rstudio-education/primers
```
