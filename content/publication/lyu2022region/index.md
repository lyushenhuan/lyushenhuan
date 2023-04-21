---
title: 'A Region-Based Analysis for the Feature Concatenation in Deep Forests'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yi-He Chen
  - Zhi-Hua Zhou

# Author notes (optional)
author_notes:
  - ''
  - ''
  - 'Corresponding author.'

date: '2022-11-09T00:00:00Z'
doi: 'https://doi.org/10.1049/cje.2022.00.178'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Chinese Journal of Electronics*, 31(6):1072-1080, 2022.
publication_short: In *Chinese Journal of Electronics*, 31(6):1072-1080

abstract: Deep forest is a tree-based deep model made up of non-differentiable modules that are trained without backpropagation. Despite the fact that deep forests have achieved considerable success in a variety of tasks, the key to forest representation learning known as feature concatenation still lacks interpretability. In this paper, we aim to understand the influence of feature concatenation on predictive performance. To enable such theoretical studies, we present the first mathematical formula of feature concatenation based on the two-stage structure, which regards the splits along new features and raw features as a region selector and a region classifier respectively. Furthermore, we prove a region-based generalization bound for feature concatenation, which reveals the trade-off between Rademacher complexities of the two-stage structure and the fraction of instances that are correctly classified in the selected region. As a consequence, we show that compared with the prediction-based feature concatenation (PFC), the advantage of interaction-based feature concatenation (IFC) is that it obtains more abundant regions through distributed representation and alleviates the overfitting risk in local regions. Experiments confirm the correctness of our theoretical results.

# Summary. An optional shortened abstract.
summary: This paper presents a region-based analysis for the feature concateantion in deep forests.

tags: [deep forest, region theory, ensemble learning, generalization bound, representation learning]

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
