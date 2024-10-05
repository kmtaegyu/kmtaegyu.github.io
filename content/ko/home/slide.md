---
widget: slide_image

#This file represents a page section.
headless: true

#Order that this section appears on the page.
weight: 15

title: ''
subtitle: ''

sections:
 - block: slider
   content:
      slides:

      - title: <span style="font-size:90%">AI</span>
        content: <span style="font-size:90%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:90%">
        align: center
        background:
          image:
            filename: icon.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Medical AI</span>
        content: <span style="font-size:90%">의료AI를 통한 질병 진단 및 환경 개선</span>
        align: center
        background:
          image:
            filename: icon1.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Healthcare</span>
        content: <span style="font-size:90%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
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