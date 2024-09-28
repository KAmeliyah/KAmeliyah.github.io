---
title: Brick Breaker
subtitle: Gameplay Programmer
image: assets/img/portfolio/breakout-gp.gif
alt: Ball bounces off paddle and hits block

caption:
  title: Birck Breaker
  subtitle: Solo Project
  thumbnail: assets/img/portfolio/breakout-gp.gif
---

### Introduction
After making my first game in SDL for an assignment for university, I wanted to explore more with the library and how I could utilise it.
I decided to make a Breakout clone and to put my twist on it, I decided to make my own custom levels using text files. I also included 2D physics that I coded myself.

### Text File Parsing
To customise each level, I set up a C++ vector that maps each brick type to a number. In the text files, I can create levels as I want them using the selection of corresponding numbers.

<img src = "assets/img/portfolio/level-text.png" alt = "Series of numbers in a text file">  

To parse the text file into a playable level, I've written a function that reads the text file and loads the block data into a vector. Once all the data is loaded, the level can be initialised with the blocks, ready to be played. Multiple levels can be loaded in, to be played sequentially.

<img src = "assets/img/portfolio/load-level-code.png" alt = "C++ code function">  

<img src = "assets/img/portfolio/level-init-code.png" alt = "C++ code function">

### 2D Physics

### What I Learned


{:.list-inline}
- Date: 2024
- Team Size: 1
- SDL2 & C++
- Time Span: 1 Week

