---
title: Brick Breaker
subtitle: Gameplay Programmer
image: assets/img/portfolio/breakout-gp.gif
alt: Ball bounces off paddle and hits block

caption:
  title: Brick Breaker
  subtitle: Solo Project
  thumbnail: assets/img/portfolio/breakout-gp.gif
---

<a href = "https://github.com/KAmeliyah/Breakout"> See the code here.</a>

### Introduction
After making my first game in SDL for an assignment for university, I wanted to explore more with the library and how I could utilise it.
I decided to make a Breakout clone and to put my twist on it, I decided to make my own custom levels using text files. I also included 2D physics that I coded myself.

### Text File Parsing
To customise each level, I set up a C++ vector that maps each brick type to a number. In the text files, I can create levels as I want them using the selection of corresponding numbers.

To parse the text file into a playable level, I've written a function that reads the text file and loads the block data into a vector. The code I based this on can be found <a href = "https://stackoverflow.com/questions/46719183/c-using-ifstream-to-read-file"> here.</a> Once all the data is loaded, the level can be initialised with the blocks, ready to be played. Multiple levels can be loaded in, to be played sequentially.

<img src = "assets/img/portfolio/break-level-change.gif" >

### 2D Physics
An important part of brick breaker games is how the ball's collisions can be used to strategise towards breaking blocks as the player wants. So I was committed to writing code to replicate accurate physics for the ball as I learned in my Mathematics for Computer Graphics class at university. I wrote a Vec2D class so that I had 2D vectors to work with for both position and movement. Using the position vector and the x-coordinate of the point of collision, I wrote a function to calculate the movement vector of the ball after it collides with a brick or the paddle. I based it on specular reflection to achieve natural ball movement.

### What I Learned
As I went through this project, I realised I would need to refactor how I applied what I knew about physics. While my prior knowledge was extremely helpful, it also led to some incorrect conclusions earlier in the project. After some<a href = "https://www.reddit.com/r/gamedev/comments/5qcgu9/comment/dcy5r5q/"> research</a> and continued testing of new solutions, I was able to find a method of calculating collisions that worked.

Another lesson I learned is that the profiler and other diagnostic tools in Visual Studio help hugely. With them, I was able to properly understand how my game was performing in terms of CPU and memory usage. This was especially helpful at the beginning of the project, where many Ball objects were being created, causing a severe performance drop. 

{:.list-inline}
- Date: June 2024
- Team Size: 1
- SDL2 & C++
- Time Span: 1 Week

