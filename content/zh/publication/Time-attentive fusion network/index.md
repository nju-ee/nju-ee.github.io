---
title: 'Time-attentive fusion network: An efficient model for online detection of action start'
authors:
  - 胡雪娇
  - 王师捷
  - 李明
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2024-03-13T00:00:00Z'
doi: 'https://doi.org/10.1049/ipr2.13071'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IET Image Process*
publication_short: In *IET Image Process*

abstract: Online detection of action start is a significant and challenging task that requires prompt identification of action start positions and corresponding categories within streaming videos. This task presents challenges due to data imbalance, similarity in boundary content, and real-time detection requirements. Here, a novel Time-Attentive Fusion Network is introduced to address the requirements of improved action detection accuracy and operational efficiency. The time-attentive fusion module is proposed, which consists of long-term memory attention and the fusion feature learning mechanism, to improve spatial-temporal feature learning. The temporal memory attention mechanism captures more effective temporal dependencies by employing weighted linear attention. The fusion feature learning mechanism facilitates the incorporation of current moment action information with historical data, thus enhancing the representation. The proposed method exhibits linear complexity and parallelism, enabling rapid training and inference speed. This method is evaluated on two challenging datasets:THUMOS’14 and ActivityNet v1.3. The experimental results demonstrate that the proposed method significantly outperforms existing state-of-the-art methods in terms of both detection accuracy and inference speed.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/ipr2.13071'
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
