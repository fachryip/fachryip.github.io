---
title: Monkeyland Battleground
subtitle: 
image: assets/img/portfolio/monkeyland-full.png
alt: 

caption:
  title: Monkeyland Battleground
  subtitle: 
  thumbnail: assets/img/portfolio/monkeyland-icon.png
---

At this time our team have 3 programmer and want to further challenge ourself. Come birth this game, Monkeyland Battleground. It is a competitive teamwork 3v3 online multiplayer for mobile android with active ragdoll. Let's break it down.

It is an online game with synchronous network something like gang beast. It is a very very difficult project because first never before we create an online synchronous game like this. Second active ragdoll is such a fun to look at but hard to replicate it. Third how the game server will be replicated in our own server.

For typical online game there are three network model: peer-to-peer, client host, and client server. We want this game to be played for all player in the world so peer-to-peer is out. That leave us to client host or client server. The difference is for client host, the room master will host the game inside their game and another player will join into that device. The advantage is we didn't need server for hosting so it is essentially free. The advantage again is it's relatively more simple compared to client server. The disadvantage is the connection is based on the room master. When the room master has bad connection, all player in the room will have bad ping. Also room master will always have the fastest network, because the hosting is in their device. 

The client server on the another hand will have the most stable connection and more fair connection for all player. Furthermore it is more difficult to temper the game state because all command come from server, client simply render state from server and send input. After much discussion we pick client server architecture and the server will be hosted in Polytron own server. 

Our own original timeline is 6 month to build this game. Can you believe it? 6 month! How naive we was. The final build is close to 1.5 years with the help from another team for backend and server deployment. Fortunately our own boss like the game so it's all good. 


{:.list-inline}

- Date: Jan 2021 - Feb 2022
- Associated with: Polytron Indonesia
- Platform: Mobile
- Engine: Unity
- PlayStore: https://play.google.com/store/apps/details?id=com.hit.monkeylandbattleground
