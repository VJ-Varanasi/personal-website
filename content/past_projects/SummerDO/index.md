---
title: "Testing the Efficient Market Hypothesis in Peer-to-Peer Loan Markets"
summary: "Placed 2nd in Citadel Securities' 2022 Summer Data Open"
tags: 
  - Finance
  - Data Science
date: '2022-06-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image: 
#  caption: Stereographic Projection
#  focal_point: Smart

links:
  - icon: 
    icon_pack: fab
    name: Final Report
    url: 'uploads/Team_3_report.pdf'

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

Founded in 2006, LendingClub pioneered the peer-to-peer lending space by providing a platform for investors
and potential borrowers to connect. Individuals on the platform make decisions on which loans to fund on the
basis of the debtor’s credit history and loan specifications.

As seen in LendingClub’s public reports, the majority of capital on the platform originates from institutional
investors. Banks and managed accounts do not lend money to individuals, but rather invest in multiple loans
at once. LendingClub’s reports classify loans by grade group, and present the performance of grade groups as
a whole.

In this context, from an institutional investor’s perspective, the platform is similar to a bond market, with
baskets of loans classified by grade acting as assets. We measure the value of a basket of loans by the returns it
brings. With this framework, the goal of our project is to study the efficiency of LendingClub’s loan market to
draw conclusions about the following:

  1. Market Stability: Market efficiency is an integral component of stable markets which are characterized
by their resilience to technological and demand shocks. Stable markets are also known to promote healthy
fiscal environments in which economic decisions can be made without fear of unpredictable volatility and
mis-valued assets.
  2. Market Fairness: Efficient markets can be characterized as fair markets since under conditions of market
efficiency, each participant is judged fairly on the basis of their creditworthiness. Therefore, an efficient
market prevents discriminatory lending practices.

Our analysis of market efficiency is based on the Efficient Market Hypothesis (EMH). Published in 1970, Eugene
Fama’s Noble Prize winning work classifies three classes of market efficiency:
  1. Weak Form: The simplest of all three, the weak form of the EMH states that future asset prices cannot be
predicted based on past performance.
  2. Semi-Strong Form: The semi-strong of EMH states that asset prices spontaneously reflect all publicly
available information.
  3. Strong Form: The strong form of the EMH states that asset prices account for all public and private
information. This final form of the hypothesis has the most lenient model assumptions, but is also the
most difficult to test.

Our study touches upon each form of the EMH to answer the following questions:

  1. Are the annual returns from LendingClub loans fully reflective of available return data?
  2. Can publicly available information, such as macroeconomic indicators, be used to predict the returns on
LendingClub loans?
  3. Is there evidence for insider trading or other leakage of private information on the LendingClub platform?


{{% staticref "uploads/Team_3_report.pdf" "newtab" %}}Final Report{{% /staticref %}}