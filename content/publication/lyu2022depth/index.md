---
title: ' Depth is More Powerful than Width with Prediction Concatenation in Deep Forests'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - He Yi-Xiao
  - Zhou Zhi-Hua

# Author notes (optional)
author_notes:
  - ''
  - ''
  - 'Corresponding author.'

date: '2022-12-09T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Advances in Neural Information Processing Systems 35*, in press, 2022.
publication_short: In *NeurIPS'22* **Oral**

abstract: Random Forest (RF) is an ensemble learning algorithm proposed by Breiman [2001] that constructs a large number of randomized decision trees individually and aggregates their predictions by naive averaging. Zhou and Feng [2019] further propose Deep Forest (DF) algorithm with multi-layer feature transformation, which significantly outperforms single-layer random forest in various application fields. Despite its great successes, little is known about the mathematical properties of the cascade structure. In this paper, we analyze the influence of depth and width on the consistency of cascade forest. Especially when the individual tree is inconsistent (as in practice, the individual tree is often set to be fully grown, i.e., there is only one sample at each leaf node), we find that the convergence rate of two-layer DF w.r.t. the number of trees $M$ can reach $\mathcal{O}(1/M^2)$ under some mild conditions, while the convergence rate of single-layer RF is $\mathcal{O}(1/M)$. Therefore, learning decision trees in the “deep” layer will be more powerful than learning in the “shallow” layer. Experiments further confirm the theoretical advantages.

# Summary. An optional shortened abstract.
summary: This paper presents a consistency theory for deep forests.

tags: [deep forest, consistency, ensemble learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: URL
  url: 'https://nips.cc/Conferences/2022/Schedule?showEvent=54559'

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
  caption: ''
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
