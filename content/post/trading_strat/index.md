---
title: 2. Timeseries Analysis
subtitle: A summary of the initial timeseries analyses on historical VIX index data

# Summary for listings and search engines
summary: A summary of the initial timeseries analyses on historical VIX index data

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

The first milestone of the project was to conduct a preliminary timeseries analysis on the VIX dataset. Our data is scrapped daily from the CBOE website via the [DownloadCSV.py script](https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/DownloadCSV.py). Our analysis was conducted using the [TimeSeriesPlot.py script](https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/TimeSeriesPlot.py) in which we looked at visualizing timeseries plots, timeseries decompositions, stationarity tests, seasonality, data interpolation, and Granger Causality. The results of our preliminary analysis can be found at {{% staticref "uploads/VIX Timeseries Analysis.pdf" "newtab" %}}VIX Timeseries Analysis{{% /staticref %}}

More information about the datasets and timeseries analysis can be found at {{% staticref "uploads/Timeseries README.pdf" "newtab" %}}Timeseries README{{% /staticref %}}




