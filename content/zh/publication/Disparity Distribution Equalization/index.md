---
title: 'Disparity Distribution Equalization: An Effective Data Enhancement for Stereo Matching'
authors:
  - 郑嘉璇
  - 吴佳昱
  - 许薯文
  - 都思丹
  - 李杨
  
  
#author_notes:
  
date: '2024-04-24T00:00:00Z'
doi: '10.1109/PAIS62114.2024.10541154'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *2024 6th International Conference on Pattern Analysis and Intelligent Systems (PAIS)*
publication_short: In *PAIS*

abstract: With the continuous development of convolutional neural networks(CNN), stereo matching algorithms have made great achievements. However, existing studies mainly focus on network model structure, ignoring the dataset itself and related data augmentations. In this paper, we focus on the impact of the inhomogeneity of dataset disparity distribution in the field of binocular depth estimation. We performed quantitative analyses on multiple datasets and discovered that an imbalanced disparity distribution resulted in models failing to effectively cover low interval of disparity distribution. Based on this observation, we propose the method of disparity distribution equalization and provide two approaches for adjusting the disparity distribution:scaling transformation and random translation transformation. On this basis, we retrain some representative state-of-the-art algorithms(e.g., PSMNet, GA-Net, AANet). Experiments demonstrate that through the disparity distribution equalization, those algorithms can significantly improved on the test set without introducing additional parameters.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/document/10541154'
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
