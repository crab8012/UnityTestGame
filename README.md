# UnityTestGame
A unity project intended to be a remake and continuation of TestJMEGame in a fully-fledged game engine

# New ToDo List
1) Create a Main Menu with links to all tests
2) Implement Maze Level
3) Implement Island Level
4) Implement Cave Level
5) Implement Pasture Level
6) Implement Collision and Interaction Level
7) Implement Shooting Range Level
8) Implement City Streets Level
9) Implement Metropolis Level
10) Implement Multiplayer
11) Simple Polish
12) Start work on final game

### Main Menu
1) Create main menu as the default level
2) Level switching based on button clicks
3) Pause Menu (accessible and dismissible via 'ESC')
4) Pause Menu overlaid on top of current gameplay, gameplay is paused
5) Pause Menu has 'Main Menu','Resume', and 'Quit' options

### Maze Level
1) Create Maze
2) Create First Person Player (move, look, jump, stairs)
3) Physics

### Island Level
1) Create an Island
2) Surround Island with water and/or waves
3) Island should have trees and plants
4) Island should have dynamic sounds
5) Island should have a dock
6) Island should have an animated creature or two

### Cave Level
1) Make a small field with a cave on it
2) Cave should have ambient light from a central campfire
3) Smoke and Particle effects coming off fire
4) Fire noises from fire
5) Torch on wall
6) Torch noises from torch
7) Smoke coming off torch
8) Rain/Weather outside of the cave
9) Rain noises outside of cave
10) Water drip particles inside of cave
11) Water drip noises inside of cave
12) Echo inside of cave, but not outside
13) Positional Audio
14) Table with ball
15) Push option on ball (pushes in direction player is looking)
16) Physics
17) Ball Respawn after falling off table

### Pasture Level
1) Terrain should be a field with some grass and flowers
2) Fence surrounding area
3) Animated Farm Animals
4) Simple farm animal AI
5) Pasture and Animal Noises

### Collision and Interaction
1) Rather empty level - intent is to showcase many different mechanics
2) Buttons, doors, trigger boxes, elevators, effects, etc. (All triggerable)
3) Appropriate Sound Effects for interactions
4) Player inventory UI
5) UI for some interactions
6) Simple NPC with dialogue
7) Simple NPC to trigger other actions
8) Objective Markers
9) Interaction Cue (Press E to Interact)

### Shooting Range Level
1) Generic shooting range
2) Wall/tables filled with different guns and weapons (pistols, knives, grenades, magic, etc.)
3) Targets of all kinds (Flat Stationary, Flat Moving, NPC Stationary, NPC Moving)
4) Ragdoll Physics and Effects on Death
5) Dynamic Ammo and Weapon HUD
6) Health HUD
7) Impact/Damage Counters
8) HUD popups/notifications (Toast about getting weapons/tutorial toast)
9) Appropriate particles on impact

### City Streets Level
1) Level with decorative buildings with a focus on streets and highways
2) Interactable Vehicles
3) Tunable traffic
4) Minimap
5) Street Lights
6) Day/Night
7) Lights on Vehicles (headlights, blinkers, underglow, etc)
8) Toggleable 3rd Person Driving Mode Camera
9) Driving HUD

### Metropolis Level
1) Large level with enterable buildings
2) Level Streaming for Open World Games?
3) Ability to see level from inside of buildings
4) Fog in the distance
5) Weather and Time toggles
6) Gradual Random Weather and smooth Day/Night cycle

#### Metropolis Level, Notes from Original Project
* There should be a Map Streaming AppState
* It should start small, surrounding the player with buildings that they can walk through
* As the player moves, buildings and terrain within a radius of the player should load and unload
* The player should not be able to tell that things are loading as they walk, except by app slowdown (bad)
* The player should be able to enter some buildings that are "bigger on the inside" (aka entirely new levels)

### Multiplayer
1) All previous levels should be modified to support a minimum of two players and a maximum of 4 players
2) A Multiplayer Pre-Game Lobby Menu
3) Multiplayer 'Deathmatch' gamemode
4) 'Zombie Horde' survival gamemode
5) Individual Player Slots with SaveGames

### Simple Polish
1) Improve animations, add more where needed
2) Improve sound effects, add more where needed
3) Simple and dynamic background music
4) Post Processing Effects
5) Add blurred motion background to main menu
6) Add blurred stationary background to multiplayer menu

### Final Game
1) Go through proper planning steps
2) Use assets, skills, and lessons learned through this project to make a new game
3) All missions need to support 1-4 players
4) Abililty for all players to do their own thing
5) All mission progress synced with host
6) Timestamped Save Files with recaps ('Busy Adult' and 'My Friend progressed how far without me?' modes)
7) Minimum of 8 hours of gameplay (as played solo) with ability to expand later (to support extra future content)
8) Multiplayer, non-story gamemodes as a gameplay option