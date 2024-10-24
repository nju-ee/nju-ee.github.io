---
title: 'A Study of General Data Improvement for Large-Angle Head Pose Estimation'
authors:
  - 白珏
  - 彭成磊
  - 李兆旭
  - 都思丹
  - 李杨
  
  
#author_notes:
  
date: '2021-10-31T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-31T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Computer Analysis of Images and Patterns*
publication_short: In *CAIP*

abstract: Predicting Euler angles of head pose using end-to-end CNN from a single RGB image is a popular application in recent years. However, the existing methods ignored the information about the rotation order contained in the Euler angles, always following the traditional pitch-yaw-roll order. They also neglected the error sources from outlier samples with large-angle poses. We analyzed current shortcomings and made suggestions for improvement from the perspective of data distribution. We studied the influence of different rotation orders on the data distribution and showed choosing an appropriate rotation order to learn head pose can significantly optimize the data distribution and improve the prediction accuracy. Then a data enhancement method was proposed to increase the large-angle poses by rotating the 2D images randomly and solving the corresponding head poses, which can improve network performance on the large-angle poses. Evaluated on two popular networks and different datasets, our methods were proved to be effective and general.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://doi.org/10.1007/978-3-030-89131-2_18'
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
