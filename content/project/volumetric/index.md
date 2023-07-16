---
title: Volumetric Rendering
summary: Implement Volumetric Rendering on La Jolla Render
tags:
  - Computer Graphics
date: '2023-02-20T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Colored Smoke
  focal_point: Smart

# links:
#   - icon: github
#     icon_pack: fab
#     name: Code
#     url: https://github.com/cthye/ReSTIR-on-La-Jolla
url_code: 'https://github.com/cthye/ReSTIR-on-La-Jolla'
url_pdf: ''
url_slides: ''
url_video: ''
links:
- name: Images
  url: https://drive.google.com/drive/folders/12RBozvVcAfRn4X1lHlSd_-fD2GV78jF_?usp=sharing

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project implements the Disney principled BSDF, a Bidirectional Scattering Distribution Function in La Jolla Renderer. The Disney principled BSDF aims to provide a universal solution for representing common materials using a single BSDF. While it is based on physical principles and real-world data, its primary focus is not strict physical accuracy. Instead, it serves as a practical tool for parameterizing a wide range of materials to facilitate artistic expression.

- Heterogeneous Smoke
![colored_smoke](images/hetvol_color.png)
- Homogeneous Smoke
![smoke](images/hetvol.png)
- Fog
![cornellbox](images/vol_cbox.png)
![fog](images/foggy_monkey.png)
- Transparent Material
![teapot](images/vol_cbox_teapot_final.png)
