---
title: Rigid Body Simulation
summary: Implement rigid body simulation
tags:
  - Computer_Graphics
date: '2023-05-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Rigid body
  focal_point: Smart

# links:
#   - icon: github
#     icon_pack: fab
#     name: Code
#     url: https://github.com/cthye/ReSTIR-on-La-Jolla
url_code: 'https://github.com/cthye/simulation/tree/master/hw1'
url_pdf: 'https://drive.google.com/file/d/1N6UzexTRzI-4LiI1mi2u1qjpciLu-kbp/view?usp=sharing'
url_slides: ''
url_video: 'https://drive.google.com/file/d/1-T3uPccf2d29Nx9x5UNcY2ra9PBI3Qz1/view?usp=sharing'
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
<style>
  /* Set the width and height of the video element */
  video {
    width: 100%; /* You can change this to a specific width in pixels or percentage */
    height: auto; /* This will maintain the aspect ratio of the video */
    /* Alternatively, you can set a specific height if you want to fix the aspect ratio */
    /* height: 400px; */
  }
</style>

This project contains two parts:
- The first part implements the rigid body simulation (simple double pendulum) and derive its equation of motion using the least action principle. Please see the [document](https://drive.google.com/file/d/1N6UzexTRzI-4LiI1mi2u1qjpciLu-kbp/view?usp=sharing) for the proof and the [code](https://github.com/cthye/simulation/tree/master/hw1)

<video controls>
    <source src="double_pendulum.mp4" type="video/mp4">
</video>

- The second part implements the rigid body collision detection and response with impulsed-based method. Please see the [code](https://github.com/cthye/103/tree/master/hw1).

<video controls>
  <source src="collision.mp4" type="video/mp4">
</video>


