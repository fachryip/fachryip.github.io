---
title: Perfect Position
subtitle: 
image: assets/img/portfolio/05-full.jpg
alt: 

caption:
  title: Perfect Position
  subtitle: 
  thumbnail: assets/img/portfolio/05-thumbnail.jpg
---

Around this time Polytron want to create a local multiplayer that can be played in tv with handphone for controller. So Ayo Main is created. In Ayo Main, player can choose different game that Polytron created and play it directly in their TV. Our team responsible to create the game, and another team for backend server stuff. For now only Polytron TV can download Ayo Main app.

We use websocket for data transfering and JSON as data structure. In testing the connection when wifi is same between TV and handphone give decent result. However, for highly competitive game that need instant input the lag is noticeably recognizable. So we try to balance the creation of the game, some slow game like card game or turn based, and versus game that need instant input. There will always be lag compared to playing with real controller. 

This game is like moving out, but the furniture is moving in from outside to inside the house. There is marker to help player determine where to put the furniture. There are two types of furniture, small and big. Small furniture can be grabbed and lifted by player. Big furniture however need two player to be moved. If only one player grab that furniture, the furniture is still moving, but the velocity is lower compared when two player grab that furniture. 

There is also enemy that will patrol certain area. Enemy has visual detection, so when player enters it will try to attack. If player is within range of attack, enemy will attack and player will be stunned. But after some time enemy target still outside his range of attack, enemy will come back to his patrol range. Player can also attack enemy to make it stunned and come back to its patrol range. Enemy cannot be killed.


{:.list-inline}

- Date: Feb - Dec 2022
- Associated with: Polytron Indonesia
- Platform: TV (Ayo Main)
- Engine: Unity
