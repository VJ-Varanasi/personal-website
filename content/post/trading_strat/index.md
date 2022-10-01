---
title: 3. Preliminary Trading Trategies
subtitle: A summary of initial trading strategies implemented using Metaculus User Data

# Summary for listings and search engines
summary: A summary of initial trading strategies implemented using Metaculus User Data

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

After our preliminary exploration of our timeseiries, our next objective was to develop a proof of concept alpha yielding trading strategy using the metaculus user data. We designed and tested our trading strategies via BackTrader. A complete write-up of our testing strategies can be found at {{% staticref "uploads/Trading Strategies Guide.pdf" "newtab" %}}Trading Strategies Guide{{% /staticref %}}. Corresponding code and strategies can be found at [VXX_Metaculus_POC.py script](https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/VXX_Metaculus_POC.py) and [trading_strat.py script] (https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/trading_strat.py). At a high level, we our optimized trading strategies were able to produce profits, but we were unable to develop simply strategies with positive sharpe-ratios. Further work is needed to amplify the signal and produce alpha-generating strategies. 







