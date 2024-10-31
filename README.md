# FA24-KivettN-EbertM

 ## Class: CS/IDEA 310H
## Assignment: Homework Assignment 1 (FPS Game)
## Semester: Spring 2024


# Team Members and Contributions

# Max:
Developed the menu (Level 1) with a start and quit button.
Implemented level transition functionality between levels.
Set up targets and ammo pickups.
Coded the ammo system to display ammo count and restrict shooting when out of ammo.
Designed Level 3 gameplay layout, and loop back to Level 1.

# Noah:
Designed and implemented hazards that reduce player health on collision.
Created the health system for the player, with automatic restart on death.
Implemented health pickups and capped health at 100.
Set up the target health system to handle target destruction at zero health.
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

  Hazards: Avoid or take damage from hazards, which reduce player health on contact.
  
  ## Controls:
  Movement: [e.g., WASD keys]
  
  Fire: [e.g., Left Mouse Button]
  
  Quit to Menu: [Key bind if available]
  
## Game Mechanics:
  Player Health: Begins at 100. Colliding with hazards decreases health, and on reaching 0, the level restarts.
  
  Ammo: Limited ammo that decreases with each shot. Ammo pickups replenish ammo count.
  
  Targets: Each target has 100 health, reducing with each shot until destroyed.
  
  Pickups: Distinct mesh visuals for both ammo and health pickups, which increase ammo or health on contact. Health caps at 100.

  ## Gameplay
   Gameplay is fairly basic, following a level-based method after the start level. You use your available rifle pickup, and while avoiding losing all your health by avoiding hazards, and picking up health packs, you want to eliminate targets health and destroy all the targets with your available ammo, using ammo pickups as well. You do this for two levels to complete the game. 

   ## External Resources
   Youtube:
   https://www.youtube.com/watch?v=uI5ps5DbFgI
   
   https://www.youtube.com/watch?v=K1vVbwMJCTQ
