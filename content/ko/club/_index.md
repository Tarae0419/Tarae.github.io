---
title:
date: 2024-03-25
type: landing

sections:
  - block: features
    content:
      title: 
      text: <span style="font-size:150%">현재 제가 활동하고 있는 동아리입니다.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">GPU</span>
        text: 전북대 게임 제작 동아리
        align: center
        background:
          image:
            filename: GPULogo.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">별무리</span>
        text: 전북대학교 천문동아리
        align: center
        background:
          image:
            filename: StarLogo.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---