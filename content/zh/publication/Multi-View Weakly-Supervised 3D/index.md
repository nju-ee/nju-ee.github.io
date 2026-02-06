---
title: 'Multi-View Weakly-Supervised 3D Human Pose Estimation for Depth Maps via SoG With Semantic Segmentation Information'
authors:
  - Siyuan Bei
  - Yu Zhou;
  - Yao Yu
  - 都思丹
  
  
#author_notes:
  
date: '2024-07-08T00:00:00Z'
doi: '10.1109/ACCESS.2024.3424414'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-07-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Access*
publication_short: In *IEEE Access*

abstract: We propose a multi-view weakly-supervised 3D human pose estimation network for depth maps. In this network, we introduce the Sum of Gaussians (SoG) model to represent the human body and multi-view depth maps, and add segmentation information to match the two SoG models to weakly-supervise the network parameters. Our method introduces SoG to represent the human body and depth maps, and utilizes SoG integral loss to measure the matching degree of the two SoG models. This allows us to match the two models without estimating the shape parameters of the human body. And we add segmentation information to the SoG models, which allows the network to introduce new sources of information on the basis of matching with the occupancy information contained in the original depth maps. We demonstrate the effectiveness of our method on various datasets and compare our method with other state-of-the-art algorithms to show its advantage in terms of both quality and generalization.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10587250'
#url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_video: ''

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
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
