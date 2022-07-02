`Course Project` Statistical Inference
================

-   👨🏻‍💻 Author: Anderson H Uyekita
-   📚 Specialization: <a
    href="https://www.coursera.org/specializations/data-science-statistics-machine-learning"
    target="_blank" rel="noopener">Data Science: Statistics and Machine
    Learning Specialization</a>
-   📖 Course:
    <a href="https://www.coursera.org/learn/statistical-inference"
    target="_blank" rel="noopener">Statistical Inference</a>
    -   🧑‍🏫 Instructor: Brian Caffo
-   📆 Week 4
    -   🚦 Start: Friday, 01 July 2022
    -   🏁 Finish: Friday, 01 July 2022

------------------------------------------------------------------------

## R2D2 C3PO

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AndersonUyekita/statistical-inference_course-project/master?urlpath=rstudio)

### Synopsis

------------------------------------------------------------------------

## 1. Introduction

## 2. Objectivies <a href="" id="objectivies"></a>

## 3. Requirements and Settings

``` r
# Loading libraries
library(rmarkdown)
library(tidyverse)
library(ggplot2)
library(magrittr)
```

``` r
# Force the R environment to use English settings
Sys.setlocale("LC_ALL","English")
```

    ## [1] "LC_COLLATE=English_United States.1252;LC_CTYPE=English_United States.1252;LC_MONETARY=English_United States.1252;LC_NUMERIC=C;LC_TIME=English_United States.1252"

    ## R version 4.2.0 (2022-04-22 ucrt)
    ## Platform: x86_64-w64-mingw32/x64 (64-bit)
    ## Running under: Windows 10 x64 (build 22000)
    ## 
    ## Matrix products: default
    ## 
    ## locale:
    ## [1] LC_COLLATE=English_United States.1252 
    ## [2] LC_CTYPE=English_United States.1252   
    ## [3] LC_MONETARY=English_United States.1252
    ## [4] LC_NUMERIC=C                          
    ## [5] LC_TIME=English_United States.1252    
    ## system code page: 65001
    ## 
    ## attached base packages:
    ## [1] stats     graphics  grDevices utils     datasets  methods   base     
    ## 
    ## other attached packages:
    ##  [1] magrittr_2.0.3  forcats_0.5.1   stringr_1.4.0   dplyr_1.0.9    
    ##  [5] purrr_0.3.4     readr_2.1.2     tidyr_1.2.0     tibble_3.1.7   
    ##  [9] ggplot2_3.3.6   tidyverse_1.3.1 rmarkdown_2.14 
    ## 
    ## loaded via a namespace (and not attached):
    ##  [1] tidyselect_1.1.2 xfun_0.31        haven_2.5.0      colorspace_2.0-3
    ##  [5] vctrs_0.4.1      generics_0.1.2   htmltools_0.5.2  yaml_2.3.5      
    ##  [9] utf8_1.2.2       rlang_1.0.3      pillar_1.7.0     glue_1.6.2      
    ## [13] withr_2.5.0      DBI_1.1.3        dbplyr_2.2.1     modelr_0.1.8    
    ## [17] readxl_1.4.0     lifecycle_1.0.1  munsell_0.5.0    gtable_0.3.0    
    ## [21] cellranger_1.1.0 rvest_1.0.2      codetools_0.2-18 evaluate_0.15   
    ## [25] knitr_1.39.3     tzdb_0.3.0       fastmap_1.1.0    fansi_1.0.3     
    ## [29] broom_1.0.0      backports_1.4.1  scales_1.2.0     jsonlite_1.8.0  
    ## [33] fs_1.5.2         hms_1.1.1        digest_0.6.29    stringi_1.7.6   
    ## [37] grid_4.2.0       cli_3.3.0        tools_4.2.0      crayon_1.5.1    
    ## [41] pkgconfig_2.0.3  ellipsis_0.3.2   xml2_1.3.3       reprex_2.0.1    
    ## [45] lubridate_1.8.0  assertthat_0.2.1 httr_1.4.3       rstudioapi_0.13 
    ## [49] R6_2.5.1         compiler_4.2.0

## 4. Data Processing

### 4.1. Downloading

Creating a data folder to store the dataset from NOAA.

### 4.2. Loading

## 5. Data Assessing

### 5.1. Dimensions

### 5.2. Head and Tail

### 5.3. Variables

## 6. Data Manipulation

### 6.1. Subsetting the raw data

### 6.2. Merging Damage and Exponential Variables

### 6.3. Uniforming Event Types

### 6.3. Tidy dataset

## 7. Results <a href="" id="results"></a>
