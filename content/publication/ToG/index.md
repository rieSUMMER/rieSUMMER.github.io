---
title: 'Think-on-Graph: Deep and Responsible Reasoning of Large Language Model with Knowledge Graph'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chengjin Xu
  - Lumingyuan Tang
  - Saizhuo Wang
  - Chen Lin
  - Yeyun Gong
  - Heung-Yeung Shum
  - Jian Guo

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-07-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: Large language models (LLMs) have made significant strides in various tasks, yet they often struggle with complex reasoning and exhibit poor performance in scenarios where knowledge traceability, timeliness, and accuracy are crucial. To address these limitations, we present Think-on-Graph (ToG), a novel framework that leverages knowledge graphs to enhance LLMs' ability for deep and responsible reasoning. By employing ToG, we can identify entities relevant to a given question and conduct exploration and reasoning to retrieve related triples from an external knowledge database. This iterative procedure generates multiple reasoning pathways consisting of sequentially connected triplets until sufficient information is gathered to answer the question or the maximum depth is reached. Through experiments on complex multi-hop reasoning question-answering tasks, we demonstrate that ToG outperforms existing methods, effectively addressing the aforementioned limitations of LLMs without incurring additional training costs.

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
  caption: '[**ToG**](https://arxiv.org/abs/2307.07697)'
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
