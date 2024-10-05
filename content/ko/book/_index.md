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
    
  - block: slider
    content:
      slides:

      - title: <span style="font-size:70%">개발</span>
        content: <span style="font-size:70%">게임 클라이언트 및 서버</span>
        align: center
        background:
          image:
            filename: develop.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        link:
          icon: list-chcek
          icon_pack: fas
          text: <span style="font-size:60%">my project</span>
          text-color: '#000'
          url: project
      - title: <span style="font-size:70%">취미</span>
        content: <span style="font-size:70%">천체 관측</span>
        align: center
        background:
          image:
            filename: Stars.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
      - title: <span style="font-size:70%">관심사</span>
        content: <span style="font-size:70%">경제</span>
        align: center
        background:
          image:
            filename: stock.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
        
  - block: features
    id: features
    content:
      title: <span style="font-size:75%">관심사</span>
      text: 저의 관심사를 소개합니다!<br><br><br><br>
      items:
        - name: 개발
          icon: laptop-code
          icon_pack: fas
          description: <span style="font-size:90%">게임 클라이언트 및 서버 개발을 하고 있습니다. </span><br><br>
        - name: 경제
          icon: sack-dollar
          icon_pack: fas
          description:  <span style="font-size:90%">경제에 관심이 있어 회계학을 복수전공하고 있습니다. </span><br><br>
        - name: 게임
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">게임을 하는 것을 좋아합니다. </span><br><br>
        - name: 천체 관측
          icon: star
          icon_pack: fas
          description:  <span style="font-size:90%"> 천체 관측을 좋아해 "별무리"라는 동아리에 가입하여 임원진으로 활동하고 있습니다. </span><br><br>
        - name: 음악
          icon: music
          icon_pack: fas
          description:  <span style="font-size:90%">음악을 듣는 것을 좋아하며 사람들과 노래방에 가는 것을 좋아합니다. </span><br><br>
        - name: 음식
          icon: bowl-food
          icon_pack: fab
          description:  <span style="font-size:90%">먹는 것을 좋아해 맛집 탐방을 하는 것을 즐깁니다. </span><br><br>     
          
  - block: collection
    content:
      title: 프로젝트
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - myproject
    design:
      view: community/custom_card
      align: center
      columns: '3'          
---