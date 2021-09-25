+++
title = "Conference Startup Guide"
description = ""
tags = [
    "startup",
    "packages",
    ]
date = "2021-04-01"
categories = [
    "startup",
    "packages",
]
+++

## Install R 4.1 or higher
 - Navigate to CRAN mirror: https://cran.r-project.org/
 - Choose the download for your operating system
  
## Install RStudio 1.4.1717 or higher
  - Navigate to https://rstudio.com/products/rstudio/download/
  - Choose the download for your operating system

## Install the following R packages in your R instance
```{r eval=FALSE}
install.packages(c('rmarkdown', 'DT', 'plotly', 'highcharter', 
'reactable', 'kableExtra', 'devtools', 'reticulate', 
'shiny', 'shinydashboard', 'writexl', 'readxl', 
'shiny.semantic’, bslib', 'DT', 'fGarch','kableExtra', 'pacman', 
'png', 'gifski', 'gganimate', 'survminer', 'tidyverse', 
'igraph', 'ggraph', 'RColorBrewer'))

devtools::install_github("Trusted-AI/AIF360/aif360/aif360-r")
```