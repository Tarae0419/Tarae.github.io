---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">게임 개발에 흥미를 느껴 현재까지 게임 개발 공부를 진행하고 있습니다. 클라이언트 개발뿐만 아니라 게임 서버 공부도 같이 진행하고 있습니다. 금융·ICT에도 관심이 있어 회계학과를 복수전공하여 공부 중에 있습니다.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:150%">게임 클라이언트 개발</span>
        align: center
        background:
          image:
            filename: game1.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:150%">게임 서버 개발</span>
        align: center
        background:
          image:
            filename: game2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:150%">금융·ICT</span>
        align: center
        background:
          image:
            filename: bank.jpg
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