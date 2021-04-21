---
title: "variables"
metaTitle: "This is the title tag of this page"
metaDescription: "This is the meta description"
---

https://swcarpentry.github.io/r-novice-inflammation/01-starting-with-data/index.html

##

```r
weight_kg <- 57.5
weight_lb <- 2.2 * weight_kg
```

seperator를 `,`로 읽어야 하는 경우 아래와 같이 가능하다.
```r
read.csv(file = "data/commadec.txt", sep = ";", dec = ",")
```
