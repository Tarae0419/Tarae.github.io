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
    content:
      title: 박준영의 소개 사이트
      text: <br> 박준영의 소개 사이트에 오신 것을 환영합니다.<br><br>
        {{% cta cta_link="./about/" cta_text="See My Profile →" %}}
        
  - block: features
    id: features
    content:
      title: <span style="font-size:75%">관심사</span>
      text: 저의 관심사를 소개합니다<br><br><br><br>
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
        - name: 영화
          icon: film
          icon_pack: fas
          description:  <span style="font-size:90%">영화를 보러 영화관에 가는 것을 즐깁니다. </span><br><br>
        - name: 음악
          icon: music
          icon_pack: fas
          description:  <span style="font-size:90%">음악을 듣는 것을 좋아하며 사람들과 노래방에 가는 것을 좋아합니다. </span><br><br>
        - name: 음식
          icon: bowl-food
          icon_pack: fab
          description:  <span style="font-size:90%">먹는 것을 좋아해 맛집 탐방을 하는 것을 즐깁니다. </span><br><br>        
---