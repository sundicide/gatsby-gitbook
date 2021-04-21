---
title: "csv"
metaTitle: "This is the title tag of this page"
metaDescription: "This is the meta description"
---

https://swcarpentry.github.io/r-novice-inflammation/01-starting-with-data/index.html

## CSV 파일 읽기
read.csv는 2개의 parameter를 받는다
1. file name
2. csv 파일 내 첫 번째 라인이 header를 포함하고 있는지 여부
    디폴트 값은 TRUE이다.

```r
read.csv(file = "data/inflammation-01.csv", header = FALSE)
```

seperator를 `,`로 읽어야 하는 경우 아래와 같이 가능하다.
```r
read.csv(file = "data/commadec.txt", sep = ";", dec = ",")
```
