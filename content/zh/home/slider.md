---
widget: slider
weight: 15
active: true
headless: true

design:
  spacing:
    padding: ['20px', '100px', '20px', '100px']
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 3000

content:
  slides:
    - title: 欢迎来到emAI！
      content: emAI是南京大学电子科学与技术学院下的一个充满活力的研究小组。我们主要的研究方向是计算机视觉、人工智能、图像处理等。
      align: left
      background:
        position: center
        color: '#666'
        brightness: 0.7
        media: people.JPG
        fit: cover
    - title: emAL
      content: ''
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: 联系我们
        url: ../contact/
---
