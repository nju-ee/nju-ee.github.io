---
title: '3D Associative Embedding: Multi-View 3D Human Pose Estimation in Crowded Scenes'
authors:
  - 朱治亦
  - 刘晟
  - 帅江海
  - 都思丹
  - 李杨
  
author_notes:
  
date: '2023-7-27T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-7-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2023 4th International Conference on Computing, Networks and Internet of Things*
publication_short: In *CNIOT*

abstract: Most of the existing multi-view multi-person 3D human pose estimation methods predict the location of each joint of one target person following a top-down paradigm after finding his region. However, these works neglect the interference of others’ joints in the region. When the scene is crowded and the target person is surrounded by others, the information of his joints tends to be disturbed which results in significant errors in 3D results. To overcome this problem, this paper takes advantage of a bottom-up method in 2D pose estimation. We incorporate the Associative Embedding method into 3D pose estimation and propose a Voxel Hourglass Network to predict 3D heatmaps along with 3D tag-maps. As a result, the adverse effects from surrounding persons can be eliminated through the difference between tags. Moreover, we design a three-stage coarse-to-fine framework which can effectively reduce the quantization error. The size of the search space drops at each stage while the resolution increases. We test our method on the CMU Panoptic dataset where it outperforms the related top-down methods.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://dl.acm.org/doi/pdf/10.1145/3603781.3603804'
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
