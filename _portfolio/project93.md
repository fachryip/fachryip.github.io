---
title: Food Express
subtitle: 
image: assets/img/portfolio/05-full.jpg
alt: 

caption:
  title: Food Express
  subtitle: 
  thumbnail: assets/img/portfolio/05-thumbnail.jpg
---

Fourth game in Polytron. Now we want to push for performance when depolying into tv device. We already learn some mistake from Neon Jump project and create best practice how to approach it. The most obvious one is no post processing, tv device especially low-end cannot handle it. Second limit vertices for each object so dynamic batching can kick in. In the docs the limit is 300 vertices, so artist have many things to adjust. Third use sprite atlas for UI so draw call is reduced. Finally use static batching for static object that didn't move. Altough dynamic batching is more optimize than static batching, but for big object that have many vertice that we cannot reduce anymore static batching does help reduce CPU usage.

Food Express is like dinner dash, but we use swipe gesture in mobile or arrow from remote tv to control waitresses turn. The waitresses itself will move automatically, we cannot stop it. Customer will come to restaurant, sit and order automatically. The waitresses must take the matching order from kitchen and bring it to the customer. If the order is the same, the customer will eat and go home with a happy emotion. Is the order is wrong, the customer will reject it and wait for their order. For each table, there is meter to measure their happiness. The more this meter is remaining, the more score you will get, the more Nagih Coin you will get. 

Late in the game, sometimes some customer will disturb your work and make you down. There is a customer that will throw banana peel that will make you fall. Fortunately there is a power up to help mitigate this problem. Ice powerup can be used to freeze disturbance for some time. When the distubance is freezing, you can get pass them without fall. This game also has life mechanic, for everytime you fall one heart is reducted. For each game player have 3 hearts, so be careful. 


{:.list-inline}

- Date: Apr - Jul 2020
- Associated with: Polytron Indonesia
- Platform: Mobile, TV
- Engine: Unity
- PlayStore: https://play.google.com/store/apps/details?id=com.hit.foodexpress
