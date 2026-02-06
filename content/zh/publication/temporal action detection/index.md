---
title: 'An efficient action proposal processing approach for temporal action detection'
authors:
  - 胡雪娇
  - 戴京昭
  - 李明
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2024-12-28T00:00:00Z'
doi: 'https://doi.org/10.1016/j.neucom.2024.129294'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing*
publication_short: In *Neurocomputing*

abstract: Temporal action detection is a fundamental yet challenging task in video understanding. It is important to process the action proposals for action classification and temporal boundary localization. Some methods process action proposals by exploiting the relations between them. However, learning the relations between numerous action proposals is time-consuming and requires huge computation and memory storage. Each proposal contains contextual information extracted from video segments, and redundant information aggregation has a negative impact on the final detection performance. In this paper, we exploit an efficient model which processes each proposal individually and learn intra-proposal features adequately, avoiding the interference of redundant information to achieve more effective detection. We also design relational learning models based on mean pooling, self-attention, and temporal convolution to compare with the intra-proposal learning model. Extensive experiments show that our method outperforms the relation learning models and achieves competitive performance on the two standard benchmarks. Moreover, efficiency experiments also verify that our model is more efficient than the relation learning methods.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S0925231224020654?via%3Dihub'
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
