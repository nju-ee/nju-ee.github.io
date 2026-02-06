---
title: 'Pyramid Feature Attention Network for Monocular Depth Prediction'
authors:
  - 徐一舫
  - 彭成磊
  - 李明
  - 李杨
  - 都思丹
  
#author_notes:
  
date: '2021-07-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-07-05T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2021 IEEE International Conference on Multimedia and Expo*
publication_short: In *ICME*

abstract: Deep convolutional neural networks (DCNNs) have achieved great success in monocular depth estimation (MDE). However, few existing works take the contributions for MDE of different levels feature maps into account, leading to inaccurate spatial layout, ambiguous boundaries and discontinuous object surface in the prediction. To better tackle these problems, we propose a Pyramid Feature Attention Network (PFANet) to improve the high-level context features and lowlevel spatial features. In the proposed PFANet, we design a Dual-scale Channel Attention Module (DCAM) to employ channel attention in different scales, which aggregate global context and local information from the high-level feature maps. To exploit the spatial relationship of visual features, we design a Spatial Pyramid Attention Module (SPAM) which can guide the network attention to multi-scale detailed information in the low-level feature maps. Finally, we introduce scale-invariant gradient loss to increase the penalty on errors in depth-wise discontinuous regions. Experimental results show that our method outperforms state-of-the-art methods on the KITTI dataset.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9428446'
#url_code: 'https://github.com/nju-ee/MODE-2022'
#url_dataset: '#'
#url_poster: '#'
#url_video: 'https://www.youtube.com/watch?v=Fw-KR35UWgQ'

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
