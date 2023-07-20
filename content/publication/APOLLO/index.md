---
title: 'Enhancing Chain-of-Thoughts Prompting with Iterative Bootstrapping in Large Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Jiashuo Sun
  - Hang Zhang
  - Chen Lin
  - Yeyun Gong
  - Jian Guo
  - Nan Duan

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-12-14T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-12-14T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Long-form numerical reasoning in financial analysis aims to generate a reasoning program to calculate the correct answer for a given question. Previous work followed a retriever-generator framework, where the retriever selects key facts from a long-form document, and the generator generates a reasoning program based on retrieved facts. However, they treated all facts equally without considering the different contributions of facts with and without numbers. Meanwhile, the program consistency were ignored under supervised training, resulting in lower training accuracy and diversity. To solve these problems, we proposed APOLLO to improve the long-form numerical reasoning framework. For the retriever, we adopt a number-aware negative sampling strategy to enable the retriever to be more discriminative on key numerical facts. For the generator, we design consistency-based reinforcement learning and target program augmentation strategy based on the consistency of program execution results. Experimental results on the FinQA and ConvFinQA leaderboard verify the effectiveness of our proposed method, achieving the new state-of-the-art.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '[**APOLLO**](https://arxiv.org/abs/2212.07249)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
