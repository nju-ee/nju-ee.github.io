---
title: 'DPCalib: Dual-Perspective View Network for LiDAR-Camera Joint Calibration'
authors:
  - 曹靖豪
  - 杨雄
  - 刘晟
  - 唐铁健
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2024-05-13T00:00:00Z'
doi: 'https://doi.org/10.3390/electronics13101914'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Electronics 2024*
publication_short: In *Electronics 2024*

abstract: The precise calibration of a LiDAR-camera system is a crucial prerequisite for multimodal 3D information fusion in perception systems. The accuracy and robustness of existing traditional offline calibration methods are inferior to methods based on deep learning. Meanwhile, most parameter regression-based online calibration methods directly project LiDAR data onto a specific plane, leading to information loss and perceptual limitations. A novel network, DPCalib, a dual perspective view network that mitigates the aforementioned issue, is proposed in this paper. This paper proposes a novel neural network architecture to achieve the fusion and reuse of input information. We design a feature encoder that effectively extracts features from two orthogonal views using attention mechanisms. Furthermore, we propose an effective decoder that aggregates features from two views, thereby obtaining accurate extrinsic parameter estimation outputs. The experimental results demonstrate that our approach outperforms existing SOTA methods, and the ablation experiments validate the rationality and effectiveness of our work.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://www.mdpi.com/2079-9292/13/10/1914'
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
