---
title: 'The study of stereo matching optimization based on multi-baseline trinocular model'
authors:
  - 王杰
  #- 彭成磊
  - 李明
  - 李杨
  - 都思丹
  
author_notes:
  
date: '2022-2-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-2-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Multimedia Tools and Applications*
#publication_short: In *CNIOT*

abstract: The huge computational complexity, occlusion and low texture region problems make stereo matching a big challenge. In this work, we use multi-baseline trinocular camera model to study how to accelerate the stereo matching algorithms and improve the accuracy of disparity estimation. A special scheme named the trinocular dynamic disparity range (T-DDR) was designed to accelerate the stereo matching algorithms. In this scheme, we optimize matching cost calculation, cost aggregation and disparity computation steps by narrowing disparity searching range. Meanwhile, we designed another novel scheme called the trinocular disparity confidence measure (T-DCM) to improve the accuracy of the disparity map. Based on those, we proposed the semi-global matching with T-DDR (T-DDR-SGM) and T-DCM (T-DCM-SGM) algorithms for trinocular stereo matching. According to the evaluation results, the T-DDR-SGM could not only significantly reduce the computational complexity but also slightly improving the accuracy, while the T-DCM-SGM could excellently handle the occlusion and low texture region problems. Both of them achieved a better result. Moreover, the optimization schemes we designed can be extended to the other stereo matching algorithms which possesses pixel-wise matching cost calculation and aggregation steps not only the SGM. We proved that the proposed optimization methods for the trinocular stereo matching are effective and the trinocular stereo matching is useful for either improving accuracy or reducing computational complexity.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://link.springer.com/content/pdf/10.1007/s11042-022-12579-8.pdf'
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
