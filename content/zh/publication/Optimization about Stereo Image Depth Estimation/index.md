---
title: ' A Discussion of Optimization about Stereo Image Depth Estimation Based on Multi-baseline Trinocular Camera Model'
authors:
  - 王汉镕
  - 李明
  - 王杰
  - 李杨
  - 都思丹
  
#author_notes:
  
date: '2022-05-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-05-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computational Science and Computational Intelligence*
publication_short: In *CSCI*

abstract: The huge computational complexity and occlusion problems make stereo matching a major challenge. In this work, we use multi-baseline trinocular camera model to accelerate the stereo matching algorithms and improve the accuracy of disparity estimation. We propose a special scheme named the trinocular flexible disparity searching range (FDSR) to accelerate the stereo matching algorithms. In this scheme, we optimize stereo matching by reducing the disparity searching range. Based on FDSR, we proposed the FDSR-MCCNN for trinocular stereo matching. According to the evaluation results, the FDSR-MCCNN could not only reduce the computational complexity but also improve the accuracy. Moreover, the optimization schemes we designed can be extended to other stereo matching algorithms that possess pixel-wise matching cost calculations and aggregation steps. We proved that the proposed optimization methods for trinocular stereo matching are effective and that trinocular stereo matching is useful for either improving accuracy or reducing computational complexity.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://doi.org/10.1109/CSCI54926.2021.00325'
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
