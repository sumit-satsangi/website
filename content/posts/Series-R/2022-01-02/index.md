---
title: Basics (Part 1)
date: 2022-01-02
menu:
  sidebar:
    name: Basics
    identifier: Basics
    parent: R
    weight: 30
tags: ["Series", "R"]
categories: ["Series-R"]
output: html_document
---



<span class="firstcharacter">I</span>t is always good to clear the concepts first and then take baby steps to execute what you've learnt. This is going to be in parts and I will share some basic concepts behind R here. Let's dive in.
</br>

## Programming Styles in R

There are three main programming styles that R uses:
- Object Oriented Programming
- Array Programming &
- Functional Programming

Let's look into them in detail:


#### Object Oriented Programming

Objects can be created in R which will hold the information with attributes.


```r
data(iris)
head(iris, 6)
```

```
##   Sepal.Length Sepal.Width Petal.Length Petal.Width Species
## 1          5.1         3.5          1.4         0.2  setosa
## 2          4.9         3.0          1.4         0.2  setosa
## 3          4.7         3.2          1.3         0.2  setosa
## 4          4.6         3.1          1.5         0.2  setosa
## 5          5.0         3.6          1.4         0.2  setosa
## 6          5.4         3.9          1.7         0.4  setosa
```

{{< alert type="success" >}}

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
{{< /alert >}}


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


----------------------------------------------------------------------------------------------
<!--
How to Span:
<span class="firstcharacter">S</span>

Shortcode for images:
{{< img src="ibs.png" width="20%" align="center" title="Introductory Business Statistics" >}}


SHORT CODES for highlighting stuff:
{{< alert type="success" >}} This is sample alert with type="success". {{< /alert >}}
{{< alert type="danger" >}} This is sample alert with type="danger". {{< /alert >}}
{{< alert type="warning" >}} This is sample alert with type="warning". {{< /alert >}}
{{< alert type="info" >}} This is sample alert with type="info". {{< /alert >}}
{{< alert type="dark" >}} This is sample alert with type="dark". {{< /alert >}}
{{< alert type="primary" >}} This is sample alert with type="primary". {{< /alert >}}
{{< alert type="secondary" >}} This is sample alert with type="secondary". {{< /alert >}}

-->

<style>
body {
text-align: justify
}
</style>

<style>
.firstcharacter {
  color: #903;
  float: left;
  font-family: Georgia;
  font-size: 75px;
  line-height: 60px;
  padding-top: 4px;
  padding-right: 8px;
  padding-left: 3px;
}
</style>

<style>
.comment {
  color: #999999;
  float: left;
  font-size: 12px;
  font-style: italic;
}
</style>
