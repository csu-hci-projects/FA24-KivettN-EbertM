# FA24-KivettN-EbertM

 ## Class: CS/IDEA 310H
## Assignment: Homework Assignment 1 (FPS Game)
## Semester: Spring 2024


# Team Members and Contributions

### Important Note: Max's device does not work well with Unreal Engine so most work was done on Noah's github and device by both parties

https://youtu.be/NGOkwCnjFSg?feature=shared

# Max:
Developed the menu (Level 1) with a start and quit button.

Could not Implemented level transition functionality between levels.

Set up targets and ammo pickups.

Coded the ammo system to display ammo count and restrict shooting when out of ammo.

Designed Level 3 gameplay layout

Could not loop back to Level 1.

# Noah:
Designed and implemented hazards 

Could not have hazards reduce player health on collision.

Created the health system for the player

Implemented health pickups and capped health at 100.

Could not set up the target health system to handle target destruction at zero health.

Designed Level 2 gameplay layout.

Project Setup and Dependancies



## Game Instructions
Engine Used: UE 5.4.4

Required Assets/Plugins: n/a

 Starting the Game:
  Launch the game from the menu scene (Level 1).

 Options include:
  
  Start: Loads the first playable level.
  
  Quit: Exits the game.
  
## Gameplay Overview:
  Levels: Three levels in total.
  
   Level 1: Menu scene with start and quit options.
   
   Levels 2 and 3: Gameplay levels with unique layouts, hazards, and targets.
   
  Objectives: Destroy all targets in each gameplay level to progress.

  Hazards: Avoid or take damage from hazards, which reduce player health on contact. Could not get functuon.
  
  ## Controls:
  Movement: WASD keys
  
  Fire: Left Mouse Button
  
  Start and Quit: Left Mouse Button
  
## Game Mechanics:
  Player Health: Caps at 100. Gains health from pickups.
  
  Does not have function for colliding with hazards decreases health, and on reaching 0, the level restarts.
  
  Ammo: Limited ammo that decreases with each shot. Ammo pickups replenish ammo count.
  
  Targets: Targets are what stops the level, can be destroyed.
  
  Does not have each target has 100 health, reducing with each shot until destroyed.
  
  Pickups: Distinct mesh visuals for both ammo and health pickups, which increase ammo or health on contact. Health caps at 100.

  ## Gameplay
   Gameplay is fairly basic, following a level-based method after the start level. You use your available rifle pickup, and picking up health packs, you want to eliminate targets and destroy all the targets with your available ammo, using ammo pickups as well. You do this for two levels to complete the game. 

   ## External Resources
   Youtube:
   https://www.youtube.com/watch?v=uI5ps5DbFgI
   
   https://www.youtube.com/watch?v=K1vVbwMJCTQ

   ## Meeting Days

   10/24/24

   10/29/24

   10/31/24

   ## Submission Videos

   Demo -
   Blueprints - https://www.youtube.com/watch?v=pEfII-39xHw
