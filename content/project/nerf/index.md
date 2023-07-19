---
title: Vanilla NeRF Reimplementation
summary: Reimplement vanilla NeRF with PyTorch
tags:
  - Others
date: '2022-09-18T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: NeRF
  focal_point: Smart

# links:
#   - icon: github
#     icon_pack: fab
#     name: Code
#     url: https://github.com/cthye/ReSTIR-on-La-Jolla
url_code: 'https://github.com/cthye/NeRF'
url_pdf: 'https://drive.google.com/file/d/1MktCa1P1rOjWr_TMGfRS_Rtucgvmptyk/view?usp=sharing'
url_slides: ''
url_video: 'https://drive.google.com/file/d/1J8Sq4kPZ6XIdUMg5UfAYL4hesYGfC1gF/view?usp=sharing'
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

This project reimplements the paper "NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis". The Neural Radiance Field, or NeRF, has exploded in popularity since its first debut in ECCV 2020. This image-based rendering technique shows impressive results in reconstructing photorealistic 3D scenes from a set of calibrated 2D images. Due to its widespread use in both academia and industry, we hope to learn NeRF by reimplementing it from scratch in PyTorch.

<style>
  /* Set the width and height of the video element */
  video {
    width: 100%; /* You can change this to a specific width in pixels or percentage */
    height: auto; /* This will maintain the aspect ratio of the video */
    /* Alternatively, you can set a specific height if you want to fix the aspect ratio */
    /* height: 400px; */
  }
</style>

<video controls>
    <source src="nerf.mp4" type="video/mp4">
</video>


