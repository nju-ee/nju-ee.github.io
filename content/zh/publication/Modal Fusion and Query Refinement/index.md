---
title: 'Modal Fusion and Query Refinement Network for Video Moment Retrieval and Highlight Detection'
authors:
  - 徐一舫
  - Yunzhuo Sun
  - 翟本祥
  - 谢子恩
  - Youyao Jia
  - 都思丹
  
  
#author_notes:
  
date: '2024-09-30T00:00:00Z'
doi: '10.1109/ICME57554.2024.10687844'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2024 IEEE International Conference on Multimedia and Expo (ICME)*
publication_short: In *ICME 2024*

abstract: Given a video and a linguistic query, video moment retrieval and highlight detection (MR&HD) aim to locate all the relevant spans, while simultaneously predicting saliency scores. Most existing methods utilize RGB images as input, overlooking the inherent multi-modal visual signals like optical flow and depth. In this paper, we propose a Multi-modal Fusion and Query Refinement Network (MRNet) to learn complementary information from multi-modal cues. Specifically, we design a multi-modal fusion module to dynamically combine RGB, optical flow, and depth map. Furthermore, to simulate human understanding of sentences, we introduce a query refinement module that merges text at different granularities, containing word-, phrase-, and sentence-wise levels. Comprehensive experiments on QVHighlights and Charades datasets indicate that MRNet outperforms current SOTA methods, achieving notable improvements in MR-mAP@Avg (+3.41) and HD-HIT@1 (+3.46) on QVHighlights.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/document/10687844'
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
