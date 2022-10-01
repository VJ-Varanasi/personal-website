---
title: 4. Correlation Analysis
subtitle: A summary of correlation tests between VIX and Metaculus Data

# Summary for listings and search engines
summary: A summary of correlation tests between VIX and Metaculus Data

# Link this post with a project
projects: []

# Date published
#date: '2022-7-14T00:00:00Z'

# Date updated
#lastmod: '2022-7-14T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

#tags:
#  - Academic


#categories:
#  - Demo

---

## Overview

The objective of this phase of the project was to provide further color on the strength and extent of correlation between our respective timeseries. To do so, we looked into a handful of statistical methods ranging from pearson correlation and granger causality to autcorrelation and dynamic time wrapping methods to measure the correlation between returns on each dataset. Ac complete write up of our correlation methodology and code can be found at {{% staticref "uploads/Correlation.pdf" "newtab" %}}Correlation Guide{{% /staticref %}} and [return_corr.py script](https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/return_corr.py) respectively. 

Our strongest correlations appeared to occur at timelags approximately 10 months in advance of the financial timeseries. While some of these correlations were quite strong, due to the duration, we cannot resonable conclude a causal realtionship between our datasets. Instead, we hypothesize these casual relationships are simply statistical artifacts of our data. Additionally, we hypothesize that the Metaculus user data only leads spikes in market volatility during times of great unrest. As such, during times of stable user views, the VIX and Metaculus are largely uncorrelated. 







