Report from R/Rmd
================

The iris data is boring, but it won’t distract from the Git content.

``` r
aggregate(. ~ Species, data = iris, median)
```

    ##      Species Sepal.Length Sepal.Width Petal.Length Petal.Width
    ## 1     setosa          5.0         3.4         1.50         0.2
    ## 2 versicolor          5.9         2.8         4.35         1.3
    ## 3  virginica          6.5         3.0         5.55         2.0

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](iris_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
