# 2D Pacman-Style Game with a Twist

## Description

This project is a 2D Pacman-style game with an added twist. In this game, the player controls a knight/warrior character navigating, aiming to consume all demons (represented by ghosts). The game includes special snacks that, when consumed, temporarily boost the player's speed.

## Files

- `game.h`: This is the header file for the main Game class. It contains declarations of all functions and variables used in the game. This includes initialization functions for the game window, background, player, ghosts, and snacks, as well as functions for movement, collision detection, and rendering.

- `game.cpp`: This file contains the implementation of the Game class. It defines the game logic, including how the game window is created, how the player and ghosts are controlled, and how collisions are handled. The file also contains the game loop, which continuously updates the game state and renders the game to the screen.


## Dependencies
1. SFML (Simple and Fast Multimedia Library)
2. A C++11 compatible compiler

## Game Mechanics
1. The player uses arrow keys to navigate the knight through the maze.
2. The goal is to consume all ghosts (demons) in the window.
3. Consuming a snack gives a temporary speed boost to the player.
4. The game ends when the player consumes 25 ghosts.

## Assumptions
The game is developed and tested in an environment with SFML installed.

# Extra Features
1. Speed Boost: Eating a snack increases the knight's speed for a short duration.
2. End Game Condition: The game concludes successfully when the player consumes 25 ghosts.

## Installation Guidelines

To run this game, you need to have the SFML library installed on your computer. Follow these steps to compile and run the game:

1. Clone the repository to your local machine.
2. Compile the code using a C++ compiler. Make sure to link the SFML library. For example:
   ```
    g++ src/*.cpp -Iinclude -I/usr/local/Cellar/sfml/2.6.1/include -L/usr/local/Cellar/sfml/2.6.1/lib -lsfml-graphics -lsfml-window -lsfml-system
   ```
3. to run the game:
   ```
   ./a.out
   ```
**These commands are ran on a macbook laptop**

   
   