---
title: Disney BSDF 
summary: Implement Disney principled BSDF on La Jolla Render
tags:
  - Computer Graphics
date: '2023-03-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Disney BSDF 
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
  url: https://drive.google.com/drive/folders/1Ldlqjmn-Mu80Y7492i9RjOTkFNoU9VAF?usp=sharing

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project implements the Disney principled BSDF, a Bidirectional Scattering Distribution Function in La Jolla Renderer. The Disney principled BSDF aims to provide a universal solution for representing common materials using a single BSDF. While it is based on physical principles and real-world data, its primary focus is not strict physical accuracy. Instead, it serves as a practical tool for parameterizing a wide range of materials to facilitate artistic expression.

- Diffuse
![Diffuse](images/clearcoat_output.jpg)
- Mental
![Mental](images/clearcoat_output.jpg)
- Glass
![Glass](images/clearcoat_output.jpg)
- Clearcoat
![Clearcoat](images/clearcoat_output.jpg)
- Sheen
![Sheen](images/clearcoat_output.jpg)
