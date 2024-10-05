---
widget: slide_image

#This file represents a page section.
headless: true

#Order that this section appears on the page.
weight: 70

title: ''
subtitle: ''

sections:
 - block: slider
   content:
      slides:

      - title: <span style="font-size:90%">Web</span>
        content: <span style="font-size:90%">Node.js를 이용한 backend개발<span style="font-size:90%">
        align: center
        background:
          image:
            filename: icon.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Data Analysis</span>
        content: <span style="font-size:90%">R과 Matlab을 이용한 데이터 분석</span>
        align: center
        background:
          image:
            filename: icon1.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Algorithm</span>
        content: <span style="font-size:90%">c++을 통해 여러가지 문제 해결</span>
        align: center
        background:
          image:
            filename: icon2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'  
      design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
        slide_height: '350px'
        is_fullscreen: true
      # Automatically transition through slides?
        loop: true
      # Duration of transition between slides (in ms)
        interval: 3000
---