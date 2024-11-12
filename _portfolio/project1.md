---
title: Derserted Duo
subtitle: Gameplay Programmer
image: assets/img/portfolio/ddintro.gif
alt: 

caption:
  title: Deserted Duo
  subtitle: BFX 2024 Game Jam - Perculiar Produce
  thumbnail: assets/img/portfolio/ddintro.gif
---
### Accolades
**1st Place**  
**Best Mechanics**   
**Best 3D Art** 

<a href = "https://github.com/Joles-Doe/Peculiar-Produce"> See the code here.</a>

### Introduction
The BFX 2024 Game Jam was in October during my 2nd Year of University. We had 48 hours to make a game based on the theme 'Connections'. To meet the prompt, we came up with the concept of sharing controls between two local players. This evolved into interactable physical objects as representations of the controls.

My role during development was to help implement the connected character movement and the control objects. Since I've done a few game jams, I also wanted to try something new so I did the sound design and sound effects for Deserted Duo since I felt it would round out the whole experience.     

### Character Movement 
Both characters have their movement controlled by Unity's built-in character controller because the component is compatible with the ragdoll physics incorporated into the models.
The players can move around using WASD or the arrow keys so they can play on the same keyboard. Each player has 4 block slots for their movements/ actions that can be swapped in and out as needed to get through the level. 

<img src = "assets/img/portfolio/ddmove.gif">

### Movement Blocks
The players' movement options are represented as physical block objects. There are blocks thorughout the level that can be picked up to be used. To pick up these blocks, the player has to drop a block they already have(e.g. their UP block) which prevents them from using that kind of action. When they drop the block, a physical block will be dropped into the world to show the change. They can then pick up the new block they need to fill their empty slot. There are 6 block types, the direction blocks, jump and climb. Each block has it's own custom textures. They also have rigidbodies and colliders so they interact with the world and can be pushed around by the characters. This pushes the teamwork theme as one player can push a block towards the other so that they can pick it up. 

### Audio
It was important to us that we do as much of the game ourselves as we could. To that end, I recorded and edited all the SFX. The other team members were the voice actors. We recorded multiple variations of efforts, jumps and deaths for each player which I edited. This provided us a wide range of sounds we could use to flesh out and humanise the characters, with tonal and pitch differences for both to differentiate them. 

We used Foley for footsteps in the sand. I edited the footage to create variations where the inconsistency of footsteps made it sound more probable and therefore, more immersive.

I found stock music and audio that I layered together for the background music and ambience. A highlight was the use of gull sounds to push a beach/island vibe.

### What I learned
The biggest difference of this jam was the 48 hour time frame I was working to. It really pushed the team and I to nail down a concept as soon as possible. Our biggest strength throughout was how we were able to divide the game mechanics between all the programmers so they could be integrated at the end, causing us to be more efficient and let us take on other roles like audio design, in my case.

While doing the character movement, I learned how to work with ragdoll models and the Unity character controller for the first time. This differs from the rigidbodies that I would naturally use in Unity games for characters. It's always interesting programming with new or different APIs so I feel I gained skills from broadening my experience. 

### Other Team Members
Scott Lewis   
Christopher Hosken   
Felix Wright  
Harvey Hamilton   


{:.list-inline}

- Date: October 2024   
- Team Size: 5   
- Unity & C#   
- Time Span: 48 hours  

