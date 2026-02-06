---
title: 'HP3: Tuning-Free Head-Preserving Portrait Personalization Via 3D-Controlled Diffusion Models'
authors:
  - 徐一舫
  - Chenyu Zhang
  - 翟本祥
  - 都思丹
  
  
#author_notes:
  
date: '2025-01-27T00:00:00Z'
doi: '10.1109/LSP.2025.3534120'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Signal Processing Letters*
publication_short: In *IEEE Signal Processing Letters*

abstract: Portrait personalization (PP) has garnered considerable attention recently due to its potential applications. However, existing methods only preserve the face region, with limited capability to customize head attributes, which restricts their practicality. To address these challenges, we introduce HP3, the first head-preserving framework for zero-shot PP. It can generate realistic portraits that preserve the source head, while controlling head expression and pose through the driving image. To accomplish this, we first design the head encoder and 3D reconstruction module to obtain head features and 3D priors. Next, the head controller is devised to align them, producing 3D-aware head conditions. These conditions are injected into UNet via the adaptive connector to achieve superior head preservation and control. Qualitative and quantitative experiments demonstrate that HP3 significantly outperforms SOTA methods. Our project is available at https://github.com/YoucanBaby/HP3.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10854663'
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
