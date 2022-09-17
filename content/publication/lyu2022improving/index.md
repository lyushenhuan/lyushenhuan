---
title: 'Improving Generalization of Deep Neural Networks by Leveraging Margin Distributions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Wang Lu
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
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Neural Networks*, 151:48-60, 2022.
publication_short: In *NEUNET'22*

abstract: Recent research has used margin theory to analyze the generalization performance for deep neural networks (DNNs). The existed results are almost based on the spectrally-normalized minimum margin. However, optimizing the minimum margin ignores a mass of information about the entire margin distribution, which is crucial to generalization performance. In this paper, we prove a generalization upper bound dominated by the statistics of the entire margin distribution. Compared with the minimum margin bounds, our bound highlights an important measure for controlling the complexity, which is the ratio of the margin standard deviation to the expected margin. We utilize a convex margin distribution loss function on the deep neural networks to validate our theoretical results by optimizing the margin ratio. Experiments and visualizations confirm the effectiveness of our approach and the correlation between generalization gap and margin ratio.

# Summary. An optional shortened abstract.
summary: This paper presents a margin-based generalization bound for deep neural networks.

tags: [deep neural networks, margin theory, generalization bound, overfitting]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1016/j.neunet.2022.03.019'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
