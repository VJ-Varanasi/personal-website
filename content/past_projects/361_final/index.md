---
title: Correlating Exchange Traded Funds with Underlying Commodity Future Contracts
summary: 'Final Project for S&DS361: Data Analysis'
tags:
date: '2022-06-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image: 
  #caption: Stereographic Projection
  #focal_point: Smart

links:
  - icon: 
    icon_pack: fab
    name: Final Report
    url: 'uploads/361_Final_Report.pdf'

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


### Abstract

The goal of this project is to study the relationship between commodity futures contracts and sector-specific
ETFs (and to specifically examine whether commodity futures contracts can provide predictive power into
the ETF prices of related sectors). The procedure for doing so involved running a LASSO regression of
historical commodity data sets against sector-specific ETFs (Energy, Home-Construction, Industrials, and
Technology). By selecting LASSO regression thresholds that kept relatively high null-deviance while minimizing the number of predictors, we identified the significant commodity predictors for each of our ETFs.
Specifically, we noticed that Lumber, Palladium, and Platinum were consistently present in each of our
models. Due to the distinctiveness of our ETF sectors, we hypothesize that their presence does not support
a causality relationship between these three commodities and our ETFs in question. Instead, we believe that
their presence is a statistical artifact of our small sample size. Further work would involve rerunning this
project with additional commodity and ETF data sets in order to see if the observed trends are specific to
our data sets or indicative of larger phenomena.


{{% staticref "uploads/361_Final_Report.pdf" "newtab" %}}Full Report{{% /staticref %}}