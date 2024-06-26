<!--Title Image-->
![2024-02-0819-52-25-ezgif com-crop](https://github.com/jeanjusten/Grand_Tale-GMS2/assets/156855412/19a89e2d-0d69-4d9c-a744-62c09e0914ca)

# :video_game: Grand Tale - 2d Action Platformer (In development)
  <p>
 Grand Tale is a side project of mine, and the reason i started studying programming in 2023. <br>
 I plan it to be a 2d action platformer with some rpg elements.<br>
 The game is being developed in GameMaker Studio 2 with GML, and im doing everything by myself. <br>
 In this Github repository, i'll post major updates and share a few mechanics coding that i developed.
  </p>

  ## :large_orange_diamond: Table of Content
  

- [1. Game State](#large_orange_diamond-game-state)
- [2. Updates](#large_orange_diamond-updates)
  - [2.1 Latest Update](#pushpin-latest-update)
  - [2.2 Old Updates](#bookmark_tabs-old-updates)
- [3. Mechanics](#large_orange_diamond-mechanics)
  - [3.1 Thunder Machine](#small_red_triangle_down-thunder-machine)
    - [3.1.1 Implementing](#interrobang-how-to-implement-the-thunder-machine-in-your-project)
- [4. Planned Features](#large_orange_diamond-planned-features)
  - [4.1 Riding Mounts](#small_red_triangle_down-riding-mounts)

<!--Game State-->
## :large_orange_diamond: Game State
<p>
The game is currently in its early stages, with lots of tweakings around the mechanics to make the game polished.<br>
Besides coding, a lot of pixel art is also being developed in the time being.
</p>

<!--Updates-->
## :large_orange_diamond: Updates
### :pushpin: Latest Update
<p>
- 
</p>

### :bookmark_tabs: Old Updates
<p>
- <strong>Feb. 2024</strong> <br>
Aside from a lot of particle effects and environmental effects, i finished a mechanic that will do great together with the effect when it's raining: Thunder.
I developed a thunder machine, that makes the screen flash and triggers the thunder sound. 
The white flashes on screen happens in a random but controlled time span. 
</p>

<!--Mechanics-->
## :large_orange_diamond: Mechanics
### :small_red_triangle_down: Thunder Machine
![2024-02-0821-02-04-ezgif com-crop](https://github.com/jeanjusten/Grand_Tale-GMS2/assets/156855412/29e1b3fa-b39f-4c58-91ab-00cd76465ec0)
<p>
The <strong>Thunder Machine</strong> mechanic is very simple, and we'll only need two objects for it to work.
   <ul>
     - The Machine object<br>
     - The Flash on screen object <br>
    </ul>
    Only the Machine object needs to be added on the scene. As it will generate the Flashing object on screen, that will destroy itself after the animation is done.<br>
    You can find the object codes in the files attached to this repository.
</p>

### :interrobang: How to implement the Thunder Machine in your project
<li>Download the 3 Thunder SFX files</li>
<li>Add them into your game and keep their names as 'snd_thunder', 'snd_thunder2' and 'snd_thunder3'</li>
<br>
<li>Create a object for the <strong>Thunder Machine</strong> and name it as you will. Also, make sure the 'Visible' box is checked out</li>
<li>Add the following events on it: Create and Step. Add Draw event if you want some debug values</li>
<li>Paste the respective codes into the events</li>
<br>
<li>Create a 1x1 sprite and paint it white
<li>Rename the sprite as 'spr_fade_in_white'
<br>
<li>Create a object for the Flash and name it 'obj_thunder'</li>
<li>Add the 'spr_fade_in_white' as its sprite
<li>Add the following events on it: Create, Step, Destroy and Draw</li>
<li>Paste the respective codes into the events</li>
<br>
<li>Add the <strong>Thunder Machine</strong> on your scene</li>


![2024-02-0821-41-18-ezgif com-crop](https://github.com/jeanjusten/Grand_Tale-GMS2/assets/156855412/05d94f54-bbee-4d2d-8d8d-a21a37909a05)


### :white_check_mark: Done!
<p>
  Now your room will have a white flash with thunder SFX in a random but controlled time span.<br>
  You can play with its values and adjust the machine to better fit your needs.<br>
  Credit is not needed but apreciated. Feel free to message me if you need anything.
</p>

<!--Planned Features-->
## :large_orange_diamond: Planned Features
### :small_red_triangle_down: Riding Mounts
