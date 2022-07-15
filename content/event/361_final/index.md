---
title: Correlating Exchange Traded Funds with Underlying Commodity Futures Contracts

event: 
event_url: 

#location: 
#address:
#  street: 450 Serra Mall
#  city: Stanford
#  region: CA
#  postcode: '94305'
#  country: United States

summary: 'Final Project for S&DS 361: Data Analysis'
abstract: 'The goal of this project is to study the relationship between commodity futures contracts and sector-specific ETFs (and to specifically examine whether commodity futures contracts can provide predictive power into the ETF prices of related sectors). The procedure for doing so involved running a LASSO regression of
historical commodity data sets against sector-specific ETFs (Energy, Home-Construction, Industrials, and
Technology). By selecting LASSO regression thresholds that kept relatively high null-deviance while minimizing the number of predictors, we identified the significant commodity predictors for each of our ETFs.
Specifically, we noticed that Lumber, Palladium, and Platinum were consistently present in each of our
models. Due to the distinctiveness of our ETF sectors, we hypothesize that their presence does not support
a causality relationship between these three commodities and our ETFs in question. Instead, we believe that
their presence is a statistical artifact of our small sample size. Further work would involve rerunning this
project with additional commodity and ETF data sets in order to see if the observed trends are specific to
our data sets or indicative of larger phenomena'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
#date: ''
#date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
#publishDate: '2017-01-01T00:00:00Z'

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
  - icon: twitter
    icon_pack: fab
    name: Follow
    url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
  - example
---

{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
