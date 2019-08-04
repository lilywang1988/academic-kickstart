---
title: Penalized Survival Models for the Analysis of Alternating Recurrent Event Data
summary: 
tags:
- Recurrent events
- Frailty models
date: "2019-07-10T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Alternating recurrent episodes

  focal_point: Smart

links:
#- icon: twitter
# icon_pack: fab
# name: Follow
#url: https://twitter.com/georgecushen
url_code: "https://github.com/lilywang1988/BivPPL"
#url_pdf: "content/post/super_spy/poster.pdf"
#url_slides: "content/slides/super_spy/slides.pptx"
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Recurrent event data are widely encountered in clinical and observational studies. Most methods for recurrent events treat the outcome as a point process and, as such, neglect any associated event duration. This generally leads to a less informative and potentially biased analysis. We propose a joint model for the recurrent event rate (of incidence) and duration. The two processes are linked through a bivariate normal frailty. For example, when the event is hospitalization, we can treat the time to admission and length-of-stay as two alternating recurrent events. In our method, the regression parameters are estimated through a penalized partial likelihood, and the variance-covariance matrix of the frailty is estimated through a recursive estimating formula. Simulation results demonstrate that our method provides accurate parameter estimation, with relatively fast computation time. We illustrate the methods through an analysis of hospitalizations among end-stage renal disease patients.
