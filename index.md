---
title       : Compare My Car
subtitle    : A Useful Tool
author      : Emma Shearin
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained    # {standalone, draft}
knit        : slidify::knit2slides
---

## Applications

What can we do with this tool?

1. Compare old car fuel economies by weight
2. Help consumers decide which car to buy

---  

## Mechanisms

The tool produces a plot based on a customer's entries that compares their current car's weight and fuel economy to the car that they wish to buy, predicting the new car's fuel economy. For example, if the consumer owns a Mazda RX4 and wishes to buy a car weighing 3200 pounds:

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

---

## Code

The tool is based on two main functions:

1. Predicting the new fuel economy
2. Plotting data to compare the new data to the old data

The tool uses linear regression to accomplish its prediction and the graphics package in R to plot the data.

---

## Recommendations

This tool works best for people who own one of the 32 car models included in the tool, listed here.

```
##  [1] "Mazda RX4"           "Mazda RX4 Wag"       "Datsun 710"         
##  [4] "Hornet 4 Drive"      "Hornet Sportabout"   "Valiant"            
##  [7] "Duster 360"          "Merc 240D"           "Merc 230"           
## [10] "Merc 280"            "Merc 280C"           "Merc 450SE"         
## [13] "Merc 450SL"          "Merc 450SLC"         "Cadillac Fleetwood" 
## [16] "Lincoln Continental" "Chrysler Imperial"   "Fiat 128"           
## [19] "Honda Civic"         "Toyota Corolla"      "Toyota Corona"      
## [22] "Dodge Challenger"    "AMC Javelin"         "Camaro Z28"         
## [25] "Pontiac Firebird"    "Fiat X1-9"           "Porsche 914-2"      
## [28] "Lotus Europa"        "Ford Pantera L"      "Ferrari Dino"       
## [31] "Maserati Bora"       "Volvo 142E"
```
