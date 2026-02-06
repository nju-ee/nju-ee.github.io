---
title: 'ATHENA - Autonomous Vehicle Trajectory Planning Considered Human Action Awareness'
authors:
  - 曹靖豪
  - 刘晟
  - 武超凡
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2025-04-10T00:00:00Z'
doi: '10.1109/LSP.2025.3559832'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-10T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Signal Processing Letters*
publication_short: In *IEEE Signal Processing Letters*

abstract: Large language models have brought revolutionary changes to autonomous driving algorithms, ushering them into the era of multimodality. However, existing vehicle trajectory planning methods primarily focus on obstacle avoidance in autonomous driving scenarios, overlooking interactions with entities within the scene, such as humans. In this letter, we propose a new research direction:vehicle trajectory planning that takes into account human actions. We establish ATHENA, the first autonomous driving dataset that integrates multimodal human actions, comprising 33,855 scenarios. Each scenario contains status information about ego vehicle, as well as pedestrian actions that actively or passively interact with the vehicle, such as signaling the vehicle to proceed by waving and the unexpected falls by pedestrians that force the vehicle to stop. Based on each type of interaction, ATHENA also provides the corresponding driving suggestions and the reasons behind them. Moreover, we present an LLM-based baseline that consists of two agents:the Action Understanding Agent and the Vehicle Control Agent. Our baseline implements the generation of driving recommendations and vehicle control functions, which are guided by pedestrian actions. Experiments demonstrate the effectiveness and strong performance of our method.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/document/10960718'
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
