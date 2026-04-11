---
title: 3. Preliminary Trading Strategies
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

After our preliminary timeseiries exploration, our next objective was to develop a trading strategy using the metaculus user data.  We designed and tested a set of proof of concept trading strategies using python's BackTrader. A complete write-up of our strategies and corresponding results can be found at {{% staticref "uploads/VIX-Metaculus Trading Strategies.pdf" "newtab" %}}Trading Strategies Guide{{% /staticref %}}. More details about the backtrading script and trading strategies code can be found at [VXX_Metaculus_POC.py script](https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/VXX_Metaculus_POC.py) and [trading_strat.py script](https://github.com/VJ-Varanasi/VIX-Metaculus/blob/master/trading_strat.py). At a high level, our proof of concept was partially successful in that our strategies were able to produce profits; however, despite that, our strategies were unable to generate positive sharpe ratios. Further work is required to amplify metaculus signal and produce an alpha-generating strategy. 







