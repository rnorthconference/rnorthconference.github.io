+++
title = "Conference Startup Guide"
description = ""
tags = [
    "startup",
    "packages",
    ]
date = "2020-05-23"
categories = [
    "startup",
    "packages",
]
+++

## Install R 4.0.0 or higher
 - Navigate to a nearby CRAN mirror: https://cran.r-project.org/mirrors.html; for example: https://mirror.las.iastate.edu/CRAN/
 - Choose the download for your operating system
  
## Install RStudio
  - Navigate to https://rstudio.com/products/rstudio/download/
  - Choose the download for your operating system

## Install the following R packages in your R instance
```{r eval=FALSE}
install.packages( c('devtools', 'purrr', 'rvest', 
                    'RSelenium', 'dplyr', 'data.table', 
                    'dtplyr', 'epiDisplay', 'lavaan',
                    'reticulate', 'rstanarm', 'rstan',
                    'coda','mvtnorm','loo','dagitty',
                    'h2o', 'rmarkdown', 'shiny', 'plumber', 
                    'pins', 'flexdashboard', 'plotly', 'DT'))

install.packages( 'tidyverse' )
install.packages( 'tidymodels' ) 
#Say yes to any package requiring compilation if asked

#Rethinking and bootstraplib are not yet on CRAN
devtools::install_github('rmcelreath/rethinking')
devtools::install_github('rstudio/bootstraplib') 
#Choose 1 to update all packages if asked
```