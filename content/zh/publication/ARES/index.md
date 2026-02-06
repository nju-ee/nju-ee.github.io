---
title: 'ARES: Text-Driven Automatic Realistic Simulator for Autonomous Traffic'
authors:
  - 曹靖豪
  - 刘晟
  - 杨雄
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2024-10-15T00:00:00Z'
doi: '10.1109/LSP.2024.3481151'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Signal Processing Letters*
publication_short: In *IEEE Signal Processing Letters*

abstract: The large-scale generation of real-world scenario datasets is a pivotal task in the field of autonomous driving. Existing methods emphasize solely on single-frame rendering, which need complex inputs for continuous scenario rendering. In this letter, ARES:a text-driven automatic realistic simulator is proposed, which can generate extensive realistic datasets with just a single text input. Its core idea is to generate vehicle trajectories based on the textual description, and then render the scenario by vehicle attributes associated with these trajectories. For learning trajectories generating, supervisory signal temporal logic is proposed to assist conditional diffusion model, which incorporates prior physical information. We annotate textual descriptions for KITTI-MOT dataset and establish an objective quantitative evaluation system. The superiority of our method is demonstrated by its high performance, which is reflected in a matching score of 3.54 and an FID of 8.93in the trajectory reconstruction task, along with a speed accuracy of 0.99 and a direction accuracy of 0.93in the trajectory editing task. The scenarios rendered by the proposed method exhibit high quality and realism, which indicates its great potential in testing of autonomous driving algorithms with vehicle-in-the-loop simulations.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://ieeexplore.ieee.org/document/10716790'
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
