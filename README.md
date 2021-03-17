
<!-- README.md is generated from README.Rmd. Please edit that file -->

## him.ida730

The goal of `him.ida730` R package is to provide students access to
repository with selected interactive course materials locally (offline).
The package is hosted on GitHub at `himoldex/him.ida730` as public
repository.

### Installation of the package

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

### Loading a tutorial

Please take a look at the list of topics with examples and exercises
that you can practice with following interactive tutorials. The
tutorials are split into four sections that cover the basics, how to
tidy and transform data, and visualize data while performing exploratory
data analysis:

``` r
#library(him.ida730)

# Work offline with interactive tutorials available at RStudio in `him.ida730`:
#----------------------------------------------
# Section 1 : The Basics
#----------------------------------------------
# primer1_1 : "Data Visualization Basics"
# primer1_2 : "Programming Basics"

#----------------------------------------------
# Section 2 : Transform and Work with Data
#----------------------------------------------
# primer2_1 : "Working with Tibbles"
# primer2_2 : "Isolating Data with dplyr"
# primer2_3 : "Deriving Information with dplyr"

#----------------------------------------------
# Section 3 : Visualize Data
#----------------------------------------------
# primer3_1 : "Exploratory Data Analysis"
# primer3_2 : "Bar Charts"
# primer3_3 : "Histograms"
# primer3_4 : "Boxplots and Counts"
# primer3_5 : "Scatterplots"
# primer3_6 : "Line Plots"
# primer3_7 : "Overplotting and Big Data"
# primer3_8 : "Customize Your Plots"

#----------------------------------------------
# Section 4 : Tidy Data
#----------------------------------------------
# primer4_1 : "Reshape Data"
# primer4_2 : "Separate Columns"
# primer4_3 : "Join Data Sets"

# To load a specific tutorial execute a following command:
#learnr::run_tutorial("primer1_1", "him.ida730")

# Source:
# https://rstudio.cloud/learn/primers
# https://github.com/rstudio-education/primers
```
