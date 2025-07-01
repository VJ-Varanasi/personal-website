---
title: Koopman Dynamics
summary: 'Final Project for S&DS631: Optimization and Computation'
tags:
  - Dynamical Systems
date: '2022-06-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

#image: 
  #caption: Stereographic Projection
  #focal_point: Smart

links:
  - icon: 
    icon_pack: fab
    name: Paper
    url: 'uploads/KoopmanDynamics.pdf'
  # - icon: 
  #   icon_pack: fab
  #   name: Presentation
  #   url: 'uploads/KoopmanDynamicsPresentation.pdf'

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image: 
  caption: "Schematic from 'Notes on Koopman Theory'"
  focal_point: ''
  placement: 2
  preview_only: false

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


### Introduction

Dynamical systems are near ubiqituous in the natural world with rich applications in biology, chemistry, physics,
economics, and control theory. They are often applied in modeling real-world phenomena to predict future action,
better understand how system parameters impact performance, actively control dynamic systems through interactive
feedback cycles, and discover governing equations. Modeling these systems can often be difficult due to uncertainities
in measurement, unknown parameters, and inexact equations of motion. They are further complicated by non-
linearities which introduce added complexity and inhibit the use of well understood linear analysis techniques.
With no known overarching framework for non-linear systems, they are often studied by assuming local linearity in
certain phase space regimes. Koopman Operator Theory was designed to address these specific issues. The high
level idea behind the operator theory is to transform the non-linear systems into a higher dimensional space where
linearities can emerge. The idea is that in these high dimensional spaces we can extend the regions where linear
approximations of non-linear dynamical systems are appropriate. Koopman dynamical models also provide additional
physical interpretability of the system. For these reasons, Koopman dynamics have become a recent interest for the
dynamical systems and control theory communities for understanding and modeling complex systems.
