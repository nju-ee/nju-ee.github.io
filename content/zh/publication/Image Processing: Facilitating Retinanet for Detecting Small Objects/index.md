---
title: 'Image Processing: Facilitating Retinanet for Detecting Small Objects'
authors:
  - 周子豪
  - 李杨
  - 彭成磊
  - 王汉镕
  - 都思丹
  
#author_notes:
  
date: '2021-02-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Journal of Physics: Conference Series*
#publication_short: In *CNIOT*

abstract: Detecting small objects is a challenging task in object detection due to low spatial resolution and interference by background. Specifically, one-stage detectors struggle with small objects for they generate worse candidate bounding boxes. In this paper, several modifications are made to the original Retinanet to tackle the problem. Dilated convolutional layers are added to the backbone to get fined-grained features along with semantic information. The gradient of loss function is increased near the origin to enhance the quality of candidate boxes for small objects. A novel feature fusion method is also proposed to directly guide low-level features with semantic information. Significant improvement of 5.1 mAP can be seen when evaluating on MOCOD small object dataset, which contains a large amount of small objects. Our method can be easily migrated to other backbone networks with feature pyramids for detecting small objects.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://iopscience.iop.org/article/10.1088/1742-6596/1815/1/012016/meta'
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
