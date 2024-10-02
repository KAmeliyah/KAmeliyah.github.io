---
title: University Resource Manager
subtitle: UI / Gameplay Programmer
image: assets/img/portfolio/uni-game-intro.gif
alt: Unity Recreation of Bournemouth University

caption:
  title: University Resource Manager
  subtitle: BU Code Jam 2024 - Ferocious Fruits
  thumbnail: assets/img/portfolio/uni-game-intro.gif
---
### Accolades
**Most Visually Appealing**

### Introduction
For this Code Jam, our prompt was given by Bournemouth University's Sustainability team to develop a prototype of an "interactive experience" that the team could be used for people to play with to explore making the buildings on campus net zero on energy consumption. Since our team was made up of a majority of Creative Technology students, we felt it would be best to make a game. We came up with the idea of a take on a Real-Time-Strategy game where the player takes control of the uni's budget for a year.

My contributions are focused on the non-diegetic in-game shop.

### UI Programming
Utilising Unity's built-in UI objects, I designed and implemented a simple collapsible shop that overlayed onto the game. Each upgrade in the shop had a button that when pressed would take money from the player's budget and would have an impact on their other stats. I wrote scripts that would implement this. The effect was determined by the data I plugged into the Scriptable Objects that I made.

<img src = "assets/img/portfolio/shop-in-use.gif">

### Scriptable Objects
Since the shop contains multiple items that have similar components, I decided it would be best to use Unity's Scriptable Objects \[SOs]. Since each building has it's own shop, SOs made it easy for me to swap different upgrades in and out as required. I wrote the ShopItemSO script that detailed the data each upgrade would include. This method also saved on memory consumption as SOs don't need to be instantiated the way that Monobehaviours do.

<img src = "assets/img/portfolio/so-shop.gif">

### What I learned
We had less time for this project than I did when I did the Game Jam, so even with a larger team of programmers, we felt the pressure. We made sure that we agreed on a coding standard between us as soon as possible to prevent confusion down the line since we all paid attention to writing clean code. 

Our primary issue was with the version control. We were using Git and would keep running into merge issues when multiple developers would make changes to the main scene. As a result of this, we all learned how to resolve merge issues as they came up and learned to communicate clearly and frequently to prevent conflicts from occuring in the first place.

### Team Members
- Scott Lewis
- Kyle Russouw
- Chris
- Michael

{:.list-inline}
- Date: February 2024
- Team Size: 5
- Unity & C#
- Time Span: 4 Days

