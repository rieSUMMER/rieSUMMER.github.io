---
title: FinQA
summary: Global Rank 1 on FinQA Competition, Based on the paper "FinQA A Dataset of Numerical Reasoning over Financial Data"
tags:
  - Question Answering
date: '2022-11-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Logo
  focal_point: Smart

links:
  - name: Paper
    url: https://arxiv.org/abs/2212.07249
  - name: Code
    url: https://github.com/GasolSun36/APOLLO
  - name: Leaderboard
    url: https://codalab.lisn.upsaclay.fr/competitions/4138#results
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---
Paper: "APOLLO: An Optimized Training Approach for Long-form Numerical Reasoning"

We adopt a number-aware negative sampling strategy in retriever to discriminate key numerical facts from others. Moreover, we design consistency-based reinforcement learning with target program augmentation, to increase program diversity and ultimately increase the execution accuracy.

We acachieve **Global Rank 1** on FinQA [Private Leaderboard](https://codalab.lisn.upsaclay.fr/competitions/4138#results) !