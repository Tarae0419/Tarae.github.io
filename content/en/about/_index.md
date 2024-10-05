---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">I am interested in game development, so I am studying game development until now. I am not only developing clients but also studying game servers. I am also interested in finance and ICT, so I am studying accounting with a double major.</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:150%">game client development</span>
        align: center
        background:
          image:
            filename: game1.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:150%">game server development</span>
        align: center
        background:
          image:
            filename: game2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:150%">Finance and ICT</span>
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