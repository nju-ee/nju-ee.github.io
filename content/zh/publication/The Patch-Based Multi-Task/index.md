---
title: 'HiFi-Portrait: Zero-shot Identity-preserved Portrait Generation with High-fidelity Multi-face Fusion'
authors:
  - 戴京昭
  - 李杨
  - 都思丹
  
  
#author_notes:
  
date: '2025-01-30T00:00:00Z'
doi: 'https://doi.org/10.1049/ipr2.7007'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *IET Image Processing*
publication_short: In *IET Image Processing*

abstract: In this paper, we propose a global gaze following method using the patched‐based multi‐task multi‐scale reborn network (MMRGaze360) specifically designed for panorama images. Unlike existing approaches that rely on spherical networks or process only local regions, our architecture thoroughly accounts for the distortions introduced by the sphere‐to‐plane projection, enabling gaze following in comprehensive 360‐degree images. MMRGaze360 incorporates field‐of‐view (360‐FoV) and sight line (360‐Gaze) generators to model gaze behaviours and scene information in 360‐degree images. A multi‐task multi‐scale module is introduced to capture features from multiple patches centred around the estimated points located in the 360‐Gaze, using multi‐scale attention maps. These features, along with the 360‐FoV, are fused to produce a final heatmap. Additionally, we employ multi‐layer perceptions and convolutional networks using the reborn mechanism to enhance information usage and feature representation. Moreover, we establish a novel dataset, SRGaze360, which contains more conditions of the sphere‐to‐plane distortion. Experimental results on the GazeFollow360 and SRGaze360 datasets demonstrate the superiority of our method over previous works. It can be validated that our approach effectively addresses the limitations of 2D gaze following in handling out‐of‐frame gaze positions and distortions in 360‐degree images.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://digital-library.theiet.org/doi/10.1049/ipr2.70078'
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
