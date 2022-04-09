---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 您好，欢迎来到托尼代办
      content: 请左右滑动浏览我们的业务
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: plant.jpeg
    - title: 护照换发补发
      content: 旧金山及洛杉矶领区，中国护照换发和补发
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: china-passport.jpeg
    - title: World-Class Semiconductor Lab
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
