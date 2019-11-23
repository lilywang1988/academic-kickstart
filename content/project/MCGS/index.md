---
title: A Simulation-free Group Sequential Design with Max-combo Tests in the Presence of Non-proportional Hazards
summary: 
tags:
- Nonproportional hazards
- Weighted log-rank tests
- Group sequential design
date: "2019-11-14T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Maxcombo tests in group sequential design

  focal_point: Smafeatrt

links:
#- icon: twitter
# icon_pack: fab
# name: Follow
#url: "http://arxiv.org/abs/1911.05684"
url_code: "https://github.com/lilywang1988/IAfrac"
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

Non-proportional hazards (NPH) have been observed recently in many immuno-oncology clinical trials. Weighted log-rank tests (WLRT) with suitably chosen weights can be used to improve the power of detecting the difference of the two survival curves in the presence of NPH. However, it is not easy to choose a proper WLRT in practice when both robustness and efficiency are considered. A versatile maxcombo test was proposed to achieve the balance of robustness and efficiency and has received increasing attentions in both methodology development and application. However, survival trials often warrant interim analyses due to its high cost and long duration. The integration and application of maxcombo tests in interim analyses often require extensive simulation studies. In this paper, we propose a simulation-free approach for group sequential design with maxcombo test in survival trials. The simulation results support that the proposed approaches successfully control both the type I error rate and offer great accuracy and flexibility in estimating sample sizes, at the expense of light computation burden. Notably, our methods display a strong robustness towards various model misspecifications, and have been implemented in an R package for free access online.