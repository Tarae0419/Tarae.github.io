---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: background.jpg
          size: cover
          position: center
          parallax: false
        
  - block: features
    id: features
    content:
      title: <span style="font-size:75%">interests</span>
      text: Let me introduce my interests!<br><br><br><br>
      items:
        - name: Development
          icon: laptop-code
          icon_pack: fas
          description: <span style="font-size:90%">We are developing game clients and servers. </span><br><br>
        - name: Economy
          icon: sack-dollar
          icon_pack: fas
          description:  <span style="font-size:90%">I am interested in economics, so I am double majoring in accounting. </span><br><br>
        - name: Game
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">I like to play games. </span><br><br>
        - name: astronomical observation
          icon: star
          icon_pack: fas
          description:  <span style="font-size:90%"> I like astronomical observation, so I joined a club called "별무리" and work as an executive. </span><br><br>
        - name: Music
          icon: music
          icon_pack: fas
          description:  <span style="font-size:90%">I like listening to music and I like to go to karaoke with people. </span><br><br>
        - name: Food
          icon: bowl-food
          icon_pack: fab
          description:  <span style="font-size:90%">I like to eat, so I enjoy exploring famous restaurants. </span><br><br>     

  - block: collection
    content:
      title: Project
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - myproject
    design:
      view: compact
      columns: '2'
  - block: collection
    content:
      title: Books and lectures studied
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - book
    design:
      view: showcase
      columns: '2'
  - block: collection
    content:
      title: astronomical observation
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - constellation
    design:
      view: community/custom_card
      columns: '2'
      
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">Game clients and servers</span>
        align: center
        background:
          image:
            filename: develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">Hobby</span>
        content: <span style="font-size:70%">astronomical observation</span>
        align: center
        background:
          image:
            filename: Stars.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">interests</span>
        content: <span style="font-size:70%">Economy</span>
        align: center
        background:
          image:
            filename: stock.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
---