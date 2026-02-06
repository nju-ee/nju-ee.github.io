---
title: 'A Real-Time Method for Railway Track Detection and 3D Fitting Based on Camera and LiDAR Fusion Sensing'
authors:
  - 唐铁健
  - 曹靖豪
  - 杨雄
  - 刘晟
  - Dongsheng Zhu
  - 都思丹
  - 李杨
  
  
#author_notes:
  
date: '2024-04-15T00:00:00Z'
doi: 'https://doi.org/10.3390/rs16081441'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Remote Sens.2024*
publication_short: In *Remote Sens*

abstract: Railway track detection, which is crucial for train operational safety, faces numerous challenges such as the curved track, obstacle occlusion, and vibrations during the train’s operation. Most existing methods for railway track detection use a camera or LiDAR. However, the vision-based approach lacks essential 3D environmental information about the train, while the LiDAR-based approach tends to detect tracks of insufficient length due to the inherent limitations of LiDAR. In this study, we propose a real-time method for railway track detection and 3D fitting based on camera and LiDAR fusion sensing. Semantic segmentation of the railway track in the image is performed, followed by inverse projection to obtain 3D information of the distant railway track. Then, 3D fitting is applied to the inverse projection of the railway track for track vectorization and LiDAR railway track point segmentation. The extrinsic parameters necessary for inverse projection are continuously optimized to ensure robustness against variations in extrinsic parameters during the train’s operation. Experimental results show that the proposed method achieves desirable accuracy for railway track detection and 3D fitting with acceptable computational efficiency, and outperforms existing approaches based on LiDAR, camera, and camera–LiDAR fusion. To the best of our knowledge, our approach represents the first successful attempt to fuse camera and LiDAR data for real-time railway track detection and 3D fitting.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: true

# 外部链接
url_pdf: 'https://www.mdpi.com/2072-4292/16/8/1441'
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
