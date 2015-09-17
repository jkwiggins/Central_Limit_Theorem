# Central Limit Therom
Cody Frisby  
September 17, 2015  


```r
exponential <- rexp(1000)
CLT <- NULL
for (i in 1 : 1000) CLT <- c(CLT, mean(rexp(40)))
mean(exponential)
```

```
## [1] 0.989797
```

```r
mean(CLT)
```

```
## [1] 0.9932637
```

Here's are the histograms of the two distributions:

![](CLT_files/figure-html/unnamed-chunk-2-1.png) ![](CLT_files/figure-html/unnamed-chunk-2-2.png) 
