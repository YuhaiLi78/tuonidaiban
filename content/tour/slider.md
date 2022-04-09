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

    - title: 回国隔离一条龙服务（仅限旧金山湾区起飞）
      content: 住宿，核酸检测，接送等一条龙服务。力求让您省心省力，顺利把您送上归国的飞机。
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
      link:
        icon: message-lines
        icon_pack: fa
        text: 联系我们
        url: ../contact/

    - title: 护照换发补发
      content: 旧金山及洛杉矶领区，中国护照换发和补发。手把手教您操作app，并为您提供专业咨询，资料预审。
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: china-passport.jpeg
        
    - title: 旅行证等各种证件申请
      content: 旧金山及洛杉矶领区，成人及儿童旅行证等，各种证件办理。欢迎垂询。
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: travel-doc.jpeg
---
