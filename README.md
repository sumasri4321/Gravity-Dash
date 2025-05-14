# Gravity-Dash
Gravity Dash is a minimalist 2D platformer game built using Python and Pygame. Designed with simplicity and replayability in mind, the game features basic physics, enemy interactions, and a scoring system, all rendered in a calm and aesthetically pleasing environment.
This project demonstrates core game development concepts including sprite animation, collision detection, event handling, and level design using TMX maps.

-- Tech Stack:
1)Python 3.10
2)Pygame-ce 2.5.3
3)Tiled Map Editor (.tmx support via pytmx)Run the game:
4)Custom Timer & Collision Systems
5)Spritesheet Animation

-- Gameplay Overview : 
1)Players control a character that can move, jump, and shoot enemies.
2)The game takes place on a single handcrafted level with platform gaps — falling off ends the game.
3)Enemies include bees (flying) and worms (ground), each giving different score values when destroyed.
4)A Game Over screen displays the current score, high score, and an option to restart.

-- How to Run:
1)Install requirements: 
>>pip install pygame pytmx
2) Ensure directory structure:
/PlatformGame
├── main.py
├── settings.py
├── sprites.py
├── support.py
├── timer.py
├── groups.py
├── data/
│   └── maps/
│       └── world.tmx
├── images/
├── audio/
└── highscore.txt
3) Run the game:
>> python main.py

--Features Implemented
1)TMX-based tilemap integration using Tiled.
2)Sprite group management and layer rendering.
3)Sinusoidal motion for flying enemies.
4)Local high score tracking using file I/O.
5)Clean separation of logic for animation, physics, and UI.
