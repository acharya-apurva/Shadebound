# Shadebound

## Game Trailer
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Sdq8twxePco/0.jpg)](https://www.youtube.com/watch?v=Sdq8twxePco)
## Description Of The Game Engine
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/7E7JqWaTpJA/0.jpg)](https://www.youtube.com/watch?v=7E7JqWaTpJA)

## The features of the game include

### Game Scenes
- Level editor scene that implements level editor functionality
- Main menu scene that implements the main menu / options functionality
- Main gameplay scene that implements the game physics of the main gameplay mode
- Item inventory scene that is used for a relevant function
- A ‘game over’ scene with some sort of animation and game over / credits
  
### Gameplay and Mechanics
-  Collisions
   - Rectangular bounding box collisions between some entities
   - Collision between player and level geometry (walls, tiles, etc)
- Movement 
  - Dash with Invulnerability (with a cooldown)
  - Double Jump
  - Wall Jump
  - Walking
- Weapons
  - Arrows that stuns enemies (Consumes ammo obtainable during gameplay)
  - Sword (Melee Weapon)
  - Weapons are swappable during gameplay via hotkey
- NPCs
  - 4 unique non-player characters in the game that act as enemies
  - All enemies contain basic AI such as path-finding/shooting/patrolling/battling with the player
  - Enemy No 1 will use a sword to attack the player
  - Enemy No 2 will leap towards the enemy to attack the player
  - Enemy No 3 will shoot arrows and use sword
  - Enemy No 4 will breathe fire
- Moving Tiles
- Hit Points/Damage
  - Player/Enemies have hitpoints(life) and take damage and die
  - Invincibility frames are implemented for all entities that take damage
- Status Effects
  - Status effects are obtainable in some way (item, collision, ability, etc) which alter the gameplay for a limited amount of time
  - Slow down spell that slows down all enemy
  - Quad Damage potion that increases the damage the player can deal
  - Invincibility smoke bomb that makes enemies unable to attack
- Object/Inventory
  - Full map scroll that shows all enemies' location in the map
  - Health Pack (used to regain hp)
  - Sprint Potion (will make the player walk faster)
- Raycasting/Visibility
  - Enemy fires when player enters line of sight
  - Player torch illuminates areas within line of sight in certain areas
- Gravity/Acceleration
  - There is gravity in the game that applies acceleration to the player towards the bottom of the screen
- Camera/ World View
  - Standard main camera view of gameplay
  - Mini-map of local area that shows player position
- Pathfinding/Steering
  - Path-finding algorithm is used to guide enemies' throwable weapon towards the player
  - Path-finding algorithm is used to guide the flying enemies towards the player
- Shaders
  - Player glows green after consuming health potion
  - Environment will be redish when the time is slowed down
  -  Enemy turns grayscale when player stuns it
- Parallax
  - Has multiple background layers used to indicate depth in various levels
- User Interface/HUD
  - Player health
  - Weapons and Ammo
  - Game Progression
  - Status Effects / Timers
  - In-game money
- Audio
  - Has background music during gameplay / menu scenes
  - Has sound effects that occur for events when getting hit, hitting the enemy, item pickup, UI selection, and jump etc
- Options
  - Has an options menu which allows you to change the following settings:
    - Music Volume
    - Sound Effects (Can turn it on or off)
    - Game Difficulty - Normal, Easy (deal 2x, take 0.5x damage), Hard (deal 0.5x, take 2x damage, moving platforms move 0.5x)
    - Rebind all main player gameplay scene keys
- Currency system that allows player to buy from shops in-game

### Level Editor
- Game will contains a level editor similar to the one found in the MegaManMaker / Super Mario Maker game
- All of the main gameplay levels will be able to be made from within the editor
- Level editor operates on the grid
- Menu that allows user to select an existing level to edit
- Ability to select and place any Texture / Animation defined in the Assets file into the level
- Any parameters of specific entities will be editable via the level editor (whether or not NPC can block vision, hit points, patrol points of NPC etc.)

### Contributors:
- Apurva Acharya
- Dong Han
- Nhu Nguyen
- Amrinder Singh

