---
title: 'A Monocular Depth Estimation Method for Indoor-Outdoor Scenes Based on Vision Transformer'
authors:
  - 帅江海
  - 李明
  - 冯永康
  - 李杨
  - 都思丹
  
#author_notes:
  
date: '2023-11-17T00:00:00Z'
doi: '10.1109/UEMCON59035.2023.10316039'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Ubiquitous Computing,Electronics & Mobile Communication Conference*
publication_short: In *UEMCOM*

abstract: In the field of computer vision, monocular depth estimation has garnered significant attention as a research direction. However, current depth estimation methods often overlook the impact of depth range variations in indoor and outdoor scenes, consequently limiting the model’s generalization ability. To achieve high-precision depth estimation across different depth ranges, we propose a new method. We employ the pretrained model Dinov2 as encoder, combined with decoder based on CNN architecture, to enhance the network’s capacity for extracting global information from indoor and outdoor scenes. Also, we design a mapping module to transform diverse depth ranges into a unified 0-1 range, which can effectively adapt to indoor and outdoor scenes. We validate our method on the DIODE dataset, which comprises mixed indoor and outdoor scenes. Experimental results demonstrate that our method achieves higher depth estimation accuracy and stronger generalization performance when dealing with scenes of diverse depth ranges.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10316039'
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
