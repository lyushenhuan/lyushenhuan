---
title: 'On the Consistency Rate of Decision Tree Learning Algorithms'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qin-Cheng Zheng
  - admin
  - Shao-Qun Zhang
  - Yuan Jiang
  - Zhi-Hua Zhou

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding author.'

date: '2023-01-19T00:00:00Z'
# doi: 'https://proceedings.mlr.press/v206/zheng23b.html'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-20T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 26th International Conference on Artificial Intelligence and Statistics*, page to appear, Valencia, ES, 2023.
publication_short: In *Proceedings of the 26th International Conference on Artificial Intelligence and Statistics* **(AISTATS)**, pp. 7824-7848, Valencia, ES

abstract: Decision tree learning algorithms such as CART are generally based on heuristics that maximizes the impurity gain greedily. Though these algorithms are practically successful, theoretical properties such as consistency are far from clear. In this paper, we disclose that the most serious obstacle encumbering consistency analysis for decision tree learning algorithms lies in the fact that the worst-case impurity gain, i.e., the core heuristics for tree splitting, can be zero. Based on this recognition, we present a new algorithm, named Grid Classification And Regression Tree (GridCART), with a provable consistency rate $\mathcal{O}(n^{-1/(d+2)})$, which is the first consistency rate proved for heuristic tree learning algorithms.

# Summary. An optional shortened abstract.
summary: 

tags: [desicion tree, consistency]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: DOI
  url: 'https://proceedings.mlr.press/v206/zheng23b.html'

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
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
