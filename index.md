---
title       : How Far Should You Sit From The Television
subtitle    : Plus an app to calculate the distance for you
author      : Phat Doan
job         : 
framework   : revealjs      
highlighter : default.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## How Far Should You Sit 
## From The Television

Plus an app to calculate the distance for you

--- .class #id 
### Why Should I care
### About An Optimal Distance
- Sitting too close: Individual dots become visible (pixelation)
- Sitting too far: Pictures appear small and a waste of high-definite contents

--- .class #id 

### your mileage may vary...
Viewing distance depends on:

- The size of your TV
- The resolution of what being played
- Your preference (not covered here)

--- .class #id 
### Rules Of Thumb For Calculate Viewing Distance
<b>THX</b>
<br>
Viewing distance = 1.19 * TV diagonal
<br>
If you have a 40-inch TV, you should sit at:


```r
round(40*1.19,1)
```

```
## [1] 47.6
```
<br>
<b>SMPTE</b><br> Viewing distance = 1.64 * TV diagonal
<br>
If you have a 40-inch TV, you should sit at:


```r
round(40*1.64,1)
```

```
## [1] 65.6
```

--- 

### TV Viewing Distance Calculator

This app calculates optimal distance by asking you for:

1. TV size
2. Resolution
3. Unit


<br>
Get it here:
<br>
https://phatdoan.shinyapps.io/TVDistanceApp/



