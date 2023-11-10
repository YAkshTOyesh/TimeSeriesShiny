## Goal

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

This document provides a walk through of analysing Fetch’s data and the
steps taken for statistical modelling.

### Loading data

Let’s load all the required for this project:

``` r
#This code appears
```

Below is an overview of the data:

``` r
fetch_daily_receipt_count_df <- read.csv('Data/data_daily.csv')
head(fetch_daily_receipt_count_df)
```

    ##      X..Date Receipt_Count
    ## 1 2021-01-01       7564766
    ## 2 2021-01-02       7455524
    ## 3 2021-01-03       7095414
    ## 4 2021-01-04       7666163
    ## 5 2021-01-05       7771289
    ## 6 2021-01-06       7473320
