---
title: 'MH-DETR: Video Moment and Highlight Detection with Cross-modal Transformer'
authors:
  - 徐一舫
  - Yunzhuo Sun
  - 翟本祥
  - Youyao Jia
  - 都思丹
  
  
#author_notes:
  
date: '2024-06-30T00:00:00Z'
doi: '10.1109/IJCNN60899.2024.10650814'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2024 International Joint Conference on Neural Networks (IJCNN)*
publication_short: In *IJCNN 2024*

abstract: With the increasing demand for video understanding, video moment and highlight detection (MHD) has emerged as a critical research topic. MHD aims to localize all moments and predict clip-wise saliency scores simultaneously. Despite progress made by existing DETR-based methods, we observe that these methods coarsely fuse features from different modalities, which weakens the temporal intra-modal context and results in insufficient cross-modal interaction. To address this issue, we propose MH-DETR (Moment and Highlight DEtection TRansformer) tailored for MHD. Specifically, we introduce a simple yet efficient pooling operator within the uni-modal encoder to capture global intra-modal context. Moreover, to obtain temporally aligned cross-modal features, we design a plug-and-play cross-modal interaction module between the encoder and decoder, seamlessly integrating visual and textual features. Comprehensive experiments on QVHighlights, Charades-STA, Activity-Net, and TVSum datasets show that MH-DETR outperforms existing state-of-the-art methods, demonstrating its effectiveness and superiority. Our code is available at https://github.com/YoucanBaby/MH-DETR.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/document/10650814'
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
