# check R package  
```{r}
library(cranlogs)
aa <- cran_downloads(packages = c("QCSIS"), from = "2015-12-02", to = "2020-11-26")
sum(aa$count) 
plot(aa$date, aa$count, xlab = "", ylab = "QCSIS-count")
```



