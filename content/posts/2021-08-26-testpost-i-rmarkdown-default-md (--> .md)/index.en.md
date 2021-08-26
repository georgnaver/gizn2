---
title: Testpost i .rmarkdown (default.md)
author: Georg Navér
date: '2021-08-26'
slug: testpost-i-rmarkdown-default-md
categories: []
tags:
  - text
---

Här är en introduktion.

<!--more-->

## Kodparti

Här kommer lite text.


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```

## Diagram

### Diagram 1


```r
library(ggplot2)

qplot(data=cars, x=speed, y=dist, geom="point")
```

<img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-2-1.png" width="672" />

### Diagram 2

<img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-3-1.png" width="672" />

## Sammanfattning

Redit teque digerit hominumque toris verebor lumina non cervice subde tollit usus habet Arctonque, furores quas nec ferunt. Quoque montibus nunc caluere tempus inhospita parcite confusaque translucet patri vestro qui optatis lumine cognoscere flos nubis! Fronde ipsamque patulos Dryopen deorum.
