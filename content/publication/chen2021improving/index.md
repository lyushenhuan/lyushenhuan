---
title: 'Improving Deep Forest by Exploiting High-Order Interactions'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Chen Yi-He
  - admin
  - Jiang Yuan

# Author notes (optional)
author_notes:
  - 'Equal contribution.'
  - 'Equal contribution.'
  - 'Corresponding author.'

date: '2021-10-09T00:00:00Z'
doi: 'https://doi.org/10.1109/ICDM51629.2021.00118'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 21th IEEE International Conference on Data Mining*, pp. 1030-1035, Auckland, NZ, 2021.
publication_short: In *ICDM'21*

abstract: Recent studies on deep forests have shown that deep learning frameworks can be built on non-differentiable modules without a backpropagation training process. However, the feature representations of deep forests only consist of predicted class probabilities. The information these class probabilities deliver is very limited and lacks diversity, especially when the number of output labels is far less than the number of input features. Besides, the prediction-based representations require us to save multiple layers of random forests to use them during testing, which is high-memory and high-time cost. In this paper, we propose a novel deep forest model that utilizes high-order interactions of input features to generate more informative and diverse feature representations. Specifically, we design a generalized version of Random Intersection Trees (gRIT) to discover stable high-order interactions and apply Activated Linear Combination (ALC) to transform them into hierarchical distributed representations. These interaction-based representations obviate the need to store random forests in the front layers, thus greatly improving the computational efficiency. Our experiments show that our method achieves highly competitive predictive performance with significantly reduced time and memory cost.

# Summary. An optional shortened abstract.
summary: This paper presents an interaction-based representation method for deep forests.

tags: [deep forest, interaction, representation learning]

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
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

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
