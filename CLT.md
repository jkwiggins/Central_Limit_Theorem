# Central Limit Theorem
Cody Frisby  
September 17, 2015  
Here's some R code to simulate the Central Limit Theorem


```r
exponential <- rexp(1000)
CLT <- NULL
for (i in 1 : 1000) CLT <- c(CLT, mean(rexp(40)))
mean(exponential)
```

```
## [1] 0.9582211
```

```r
mean(CLT)
```

```
## [1] 0.9939525
```

Here are the histograms of the two distributions:

![](CLT_files/figure-html/unnamed-chunk-2-1.png) ![](CLT_files/figure-html/unnamed-chunk-2-2.png) 
