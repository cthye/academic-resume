---
title: Fluid Simulation
summary: Implement fluid simulation with MLS-MPM
tags:
  - Computer_Graphics
date: '2023-05-13T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Fluid
  focal_point: Smart

# links:
#   - icon: github
#     icon_pack: fab
#     name: Code
#     url: https://github.com/cthye/ReSTIR-on-La-Jolla
url_code: 'https://github.com/cthye/simulation/tree/master/hw4'
url_pdf: 'https://drive.google.com/file/d/1X0CviwHSQMWnLG4erRjlmOkKkm5v61-k/view?usp=sharing'
url_slides: ''
url_video: 'https://drive.google.com/file/d/1MvX_LDy7jrne1enMAPV1CotxfqmpjGkK/view?usp=sharing'
# links:
# - name: Images
#   url: https://drive.google.com/drive/folders/1Ldlqjmn-Mu80Y7492i9RjOTkFNoU9VAF?usp=sharing

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project implements the fluid simulation based on the Material Point Method (MPM). MPM is a hybrid Lagrangian-Eulerian method that can simulate a wide range of physical phenomena. It was originally extended from FLIP and takes the simulation framework of (Particle In Cell) PIC / (Fluid-Implicit-Particle) FLIP. A recent development, Moving Least Squares MPM (MLS-MPM) makes MPM more efficient and easier to implement. This project is basically implemented with MLS-MPM.

**Please click to see the result video:**
[![IMAGE ALT TEXT HERE](000001.png)](https://drive.google.com/file/d/1MvX_LDy7jrne1enMAPV1CotxfqmpjGkK/view?usp=sharing)
