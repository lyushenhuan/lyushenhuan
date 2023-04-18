---
title: '基于交互表示的多标记深度森林方法'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yi-He Chen
  - Yuan Jiang

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
publication: In 软件学报, 2022.
publication_short: In *JOS 2022*


abstract: In multi-label learning, each sample is associated with multiple labels. The key task is how to use the correlation between labels when building the model. Multi-Label Deep Forest (MLDF) algorithm attempts to mine the correlation between labels by using layer-by-layer representation learning under the framework of deep ensemble learning. MLDF uses the obtained label probability representation to improve the prediction accuracy. However, on the one hand, the label probability representation is highly correlated with the label information, which will lead to its low diversity. As the depth of the deep forest increases, the performance will decline. On the other hand, the calculation of label probability requires us to store all layers of forest structure and use them one by one in the test stage, which will cause unbearable computational and storage overhead. To solve these problems, this paper proposes interaction representation based Multi-Label Deep Forest (iMLDF). iMLDF mines the structural information in the feature space from the decision path of the forest model, extracts the feature interaction in the decision tree path by using the random interaction trees, and obtains two interaction representations of feature confidence score and label probability distribution respectively. On the one hand, iMLDF makes full use of the feature structure information in the forest model to enrich the relevant information between labels. On the other hand, it calculates all the representations through interaction expressions, so that the algorithm does not need to store all the forest structures, which greatly improves the computational efficiency. The experimental results show that iMLDF achieves better prediction performance, and the computational efficiency is improved by an order of magnitude compared with MLDF for larger-scale datasets.

# Summary. An optional shortened abstract.
summary: This paper presents an interaction-based representation method for multi-label deep forests.

tags: [deep forest, multi-label learning, interaction, computational complexity, label correlation]

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
