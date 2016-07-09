---
title       : Developing Data Products Project
subtitle    : July 8, 2016
author      : Alaka
job         :   s
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Project Detail

A simple Shiny application has been built and published to generate the linear regression between two variables of the "mtcars" dataset.

In this application the user chooses the predictor and outcome is always fixed as "mpg".

You can view the application at

[Shiny server link:](https://www.shinyapps.io/admin/#/application/113281)

[Git-hub link:](https://github.com/AlakaSar/developingdata)

---

## Summary of dataset

About mtcars dataset : The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973-74 models).

The mtcars dataset has 32 entries with 11 columns. The mileage (mpg) variation summary is as follows:



```
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
##   10.40   15.42   19.20   20.09   22.80   33.90
```

---

## How it works

The use select the predictor
The user selesct a color of the regression line
In both the cases, when the user make a choice, the plot is updated
It also shows the summary of the predicted varibale selected

---

## Sample Regression

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png)
