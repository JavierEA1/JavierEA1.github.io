Presentation
========================================================
author: Javier Esteban
date: 
autosize: true
css:custom.css
Incremental: true
transition: fade
transition-speed: slow

In this presentation I will work with the data set AccordPrice



```r
head(Data)
```

```
  Age Price Mileage
1   7  12.0    74.9
2   4  17.9    53.0
3   4  15.7    79.1
4   7  12.5    50.1
5   9   9.5    62.0
6   1  21.5     4.8
```

Summary Data
========================================================
type:exclaim


1. Response:Price

2. Variable 1: Mileage

3. Variable 2: Age 

Summary
========================================================
type: movidas

```r
summary(Data)
```

```
      Age             Price          Mileage      
 Min.   : 1.000   Min.   : 3.50   Min.   :  3.00  
 1st Qu.: 3.000   1st Qu.:10.03   1st Qu.: 19.93  
 Median : 4.000   Median :15.60   Median : 51.55  
 Mean   : 5.767   Mean   :14.28   Mean   : 54.53  
 3rd Qu.: 8.500   3rd Qu.:17.75   3rd Qu.: 73.28  
 Max.   :18.000   Max.   :26.80   Max.   :150.50  
```

Plot of Mileage/price
========================================================
type: movidas



<style>
  .p_iframe iframe {
    width:100%;
    height:576px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly.html"></iframe>
</div>

Plot of Age/price
========================================================
type: movidas

<style>
  .c_iframe iframe {
    width:100%;
    height:576px;
}
</style>

<div class="c_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plot2.html"></iframe>
</div>

Density plot Mileage
========================================================
type: historias

<style>
  .f_iframe iframe {
    width:100%;
    height:576px;
}
</style>

<div class="f_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plot3.html"></iframe>
</div>

Density plot Age
========================================================
type: historias

<style>
  .J_iframe iframe {
    width:100%;
    height:576px;
}
</style>

<div class="J_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plot4.html"></iframe>
</div>
