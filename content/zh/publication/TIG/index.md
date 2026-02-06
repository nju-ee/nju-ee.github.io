---
title: 'TIG: A Multitask Temporal Interval Guided Framework for Key Frame Detection'
authors:
  - 王师捷
  - 胡雪娇
  - 刘晟
  - 李明
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2024-09-01T00:00:00Z'
doi: '10.1587/transinf.2024EDP7031'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEICE TRANSACTIONS on Information*
publication_short: In *IEICE TRANS*

abstract: Detecting key frames in videos has garnered substantial attention in recent years, it is a point-level task and has deep research value and application prospect in daily life. For instances, video surveillance system, video cover generation and highlight moment flashback all demands the technique of key frame detection. However, the task is beset by challenges such as the sparsity of key frame instances, imbalances between target frames and background frames, and the absence of post-processing method. In response to these problems, we introduce a novel and effective Temporal Interval Guided (TIG) framework to precisely localize specific frames. The framework is incorporated with a proposed Point-Level-Soft non-maximum suppression (PLS-NMS) post-processing algorithm which is suitable for point-level task, facilitated by the well-designed confidence score decay function. Furthermore, we propose a TIG-loss, exhibiting sensitivity to temporal interval from target frame, to optimize the two-stage framework. The proposed method can be broadly applied to key frame detection in video understanding, including action start detection and static video summarization. Extensive experimentation validates the efficacy of our approach on action start detection benchmark datasets:THUMOS’14 and Activitynet v1.3, and we have reached state-of-the-art performance. Competitive results are also demonstrated on SumMe and TVSum datasets for deep learning based static video summarization.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://globals.ieice.org/en_transactions/information/10.1587/transinf.2024EDP7031/_f'
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
