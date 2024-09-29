---
title: Locked & Loaded
subtitle: Gameplay Programmer
image: assets/img/portfolio/locked-loaded-gp.gif
alt: Character runs from left to right towards a door 

caption:
  title: Locked & Loaded
  subtitle: BU Game Jam 2024 - Blue Shells
  thumbnail: assets/img/portfolio/locked-loaded-gp.gif
---
### Accolades
**3rd Overall**  
**Best 2D Art**

### Introduction
This was my first ever game jam. I had heard of them before and seen what others had done during theirs so I was excited to join one for myself. It was also the first time I'd worked in a multi-disciplined team of artists, designers and programmers which was fun, new experience.

Our prompt was "Combination". Our team, Blue Shells, chose to make a puzzle game with RPG elements. The goal was to escape from a dungeon by solving a puzzle and then beating an enemy. I'll highlight my contributions to the project in the following sections.

### Character Movement
As a base starting point, we wanted player controlled movement to immerse the player into the escape storyline. I was responsible for coding the movement and making sure player actions synced up with the animations Oyku drew. I scripted the 2D physics so that the character would interact correctly with the level tiles. To check for ground when the character would jump, I used a layer mask and Physics2D boxcast to check for collisions. I felt it worked really well and I moved forward with the solution.

### Combat Mechanics
A boss before gaining freedom was a story beat we wanted to hit. So, we came up with a rock, paper, scissors style system using cards. The player and enemy can play a card each and whoever wins, deals damage.

For drawing player cards, I wrote a function that randomly select a card to draw.

<img src = "assets/img/portfolio/draw-code.png" class = "center">

I think if I were to come back to this project, I would write a function to shuffle the deck instead to **compare the performance** of the two randomisation methods.

I wrote an audio manager script to play sound clips whenever there was a successful hit. The manager is a static instance that can be used through the entire game if needed. 

<img src = "assets/img/portfolio/sound-locked-loaded.png">

### Scene Management and Transitions
Locked & Loaded has multiple scenes so I added fade outs to make the transitions smoother. I had never worked on transitions before but I found this <a href = "https://www.youtube.com/watch?v=Ox0JCbVIMCQ"> tutorial</a> helped me do it. 

<img src = "assets/img/portfolio/transition-fade.gif" >

On evaluation, I noticed that the fade in isn't as smooth as the fade out. Next time I implement scene transitions, I want to make use of Unity's animator. That would save me time and make it easier for me to configure the transition to how I wanted it.

### What I learned
The biggest lesson I learned was about time management. We had to cut out a lot of what we originally planned to include because there was no time for us to make it fit. Identifying essential features and implementing them quickly became the priority as time dwindled and I think we managed those concessions well. 

Despite the pressures of the jam, I really enjoyed developing alongside the rest of the team and I am really grateful that I got the opportunity to work with such talented people.

### Other Team Members
- <a href = "https://gisellepe.com/"> Giselle Pe</a> - Static assets & tiles, Environmental design, UI design
- Oyku Erdenlig - Character Design & Sprites
- Stephany Hérnandez - Gameplay programming \(Puzzle)


{:.list-inline}

- Date: January 2024
- Team Size: 4
- Unity & C#
- Time Span: 5 Days

