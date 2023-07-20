---
title: FinQA
summary: PiXiu Instruct-tuning Large Language Models with Chinese Financial Knowledge Graph
tags:
  - Large Language Models
  - Financial Domain
date: '2023-06-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Logo
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Github
    url: https://github.com/GasolSun36/pixiu
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
This project open-sources the instruction-tuning model based on Chinese financial knowledge (Bloom-7b1). The instruction-tuning data is constructed based on gpt-3.5-turbo and the Chinese Financial Knowledge Graph (by March 2023), and Bloom-7b1 is fine-tuned to improve its performance on financial domain Q&A.
PiXiu was trained using 8 A100-40g for full parameters and RLAIF (Reinforcement Learning with AI Feedback). The first version of PiXiu (v1.0) was trained using only Q&A data. PiXiu v2.0 was trained by more diverse tasks with more instruction data.