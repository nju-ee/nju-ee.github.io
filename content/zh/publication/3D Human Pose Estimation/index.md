---
title: ' A Novel Skeleton-based Model with Spine for 3D Human Pose Estimation'
authors:
  - 李兆旭
  - 刘晟
  - 白珏
  - 彭成磊
  - 李杨
  
  
author_notes:
  
date: '2022-3-04T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-3-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Computing and Communication Workshop and Conference*
publication_short: In *CCWC*

abstract: Kinematic chain model is widely adopted in 3D human pose estimation tasks while it cannot accurately describe the curvature of the torso. This work proposes for the first time a novel model with spine curve to both express the movement of the limbs and the bending curvature of the torso. We parameterize the spine curve with the Bezier curve as it's controlled by anchor points. In this way, the estimation of the spine curve can be converted back to the estimation of points. The result shows that the anchor points of the spine curve can be estimated accurately by existing networks, similar to other joints. With the help of MOSH++ and SMPL model, the existing datasets can also be employed with our skeleton. We fit the SMPL models with the kinematic chain model and our model respectively, the fitting result shows that our model can provide richer information for the construction of human models.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/9720811'
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
