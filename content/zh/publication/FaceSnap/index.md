---
title: 'FaceSnap: Enhanced ID-Fidelity Network forTuning-Free Portrait Customization'
authors:
  - 翟本祥
  - 徐一舫
  - Guofeng Zhang
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2025-09-09T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2602.00627'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-09-09T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ICANN 2025*
publication_short: In *ICANN 2025*

abstract: Benefiting from the significant advancements in text-to-image diffusion models, research in personalized image generation, particularly customized portrait generation, has also made great strides recently. However, existing methods either require time-consuming fine-tuning and lack generalizability or fail to achieve high fidelity in facial details. To address these issues, we propose FaceSnap, a novel method based on Stable Diffusion (SD) that requires only a single reference image and produces extremely consistent results in a single inference stage. This method is plug-and-play and can be easily extended to different SD models. Specifically, we design a new Facial Attribute Mixer that can extract comprehensive fused information from both low-level specific features and high-level abstract features, providing better guidance for image generation. We also introduce a Landmark Predictor that maintains reference identity across landmarks with different poses, providing diverse yet detailed spatial control conditions for image generation. Then we use an ID-preserving module to inject these into the UNet. Experimental results demonstrate that our approach performs remarkably in personalized and customized portrait generation, surpassing other state-of-the-art methods in this domain.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://arxiv.org/abs/2602.00627'
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
