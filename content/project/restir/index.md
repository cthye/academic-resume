---
title: ReSTIR DI
summary: Implement ReSTIR DI on La Jolla Render
tags:
  - Computer Graphics
date: '2023-03-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Cyberpunk
  focal_point: Smart

# links:
#   - icon: github
#     icon_pack: fab
#     name: Code
#     url: https://github.com/cthye/ReSTIR-on-La-Jolla
url_code: 'https://github.com/cthye/ReSTIR-on-La-Jolla'
url_pdf: 'https://drive.google.com/file/d/1TLZh64V2zknsVvBiiteAcnIq1dyykyNn/view?usp=sharing'
url_slides: ''
url_video: ''
links:
- name: Images
  url: http://example.org

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This final project implements the Reservoir-based Spatiotemporal Importance Resampling (ReSTIR)
in La Jolla to render multiple-light scenes. The ReSTIR is known for achieving real-time rendering
in interactive lighting scenes without extra complex data structures or high-sample costs. Generally
speaking, it combines Resampled Importance Sampling (RIS), Weighted Reservoir Sampling (WRS),
and Spatio-temporal Reuse to provide those outstanding features: 1) approximate perfect importance
sampling proportionally to a target PDF, which no practical sampling algorithm may exist (e.g.
ρ · Le · G); 2) using a constant length "reservoir" to store accepted samples; 3) reusing information
from nearby samples both spatially and temporally.

Please see the [report](https://drive.google.com/file/d/1TLZh64V2zknsVvBiiteAcnIq1dyykyNn/view?usp=sharing) for further explanation about the mathematical background of ReSTIR and more rendering results.

Below section shows different result rendered with Monte Carlo and ReSTIR of a scene with 400 lights in total to present the power of ReSTIR.

![ReSTIR with spp 4](images/final_restir_1_bunny_4.png)
![Monte Carlo with spp 4](images/mc_bunny_4.png)
![ReSTIR with spp 40](images/final_restir_1_bunny_40.png)
![Monte Carlo with spp 40](images/mc_bunny_40.png)

