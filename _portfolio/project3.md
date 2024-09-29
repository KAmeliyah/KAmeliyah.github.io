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

<img src = "assets/img/portfolio/level-text.png">

I think if I were to come back to this project, I would write a function to shuffle the deck instead to **compare the performance** of the two randomisation methods.

I wrote an audio manager script to play sound clips whenever there was a successful hit.


### Scene Management


### Other Team Members
- <a href = "https://gisellepe.com/"> Giselle Pe</a> - Static assets & tiles, Environmental design, UI design
- Oyku Erdenlig - Character Design & Sprites
- Stephany Hérnandez - Gameplay programming \(Puzzle)


{:.list-inline}

- Date: January 2024
- Team Size: 4
- Unity & C#
- Time Span: 5 Days

