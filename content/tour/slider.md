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
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Welcome to Federation AI lab
      content: We stand together!
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
    - title: this page could be the intro of lab
      content: 'intro; intro; intro'
      align: center
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
    - title: World-Class graph learning Lab
      content: 'just intro, remember to change the images'
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
