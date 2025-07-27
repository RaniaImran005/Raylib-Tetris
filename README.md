# Raylib-Tetris
A modern Tetris clone built using the Raylib graphics library. This project recreates the classic Tetris gameplay with smooth controls, colorful visuals, and modular code structure. Designed as a personal learning experience in C++ game development and 2D rendering.The game uses various raylib functions for graphics, input handling, and audio and can be played on Windows, macOS, and Linux computers.

Key Components
Block and Blocks: 
The Block class represents individual Tetris pieces with properties such as position, rotation state, and color. It includes methods for drawing, moving, and rotating the blocks. Derived classes like L-Block, JBlock, I-Block, O-Block, S-Block, T-Block, and Z-Block represent specific Tetris pieces, each with unique configurations.
Grid: 
The Grid class manages the game board where the blocks are placed. It includes methods for initializing the grid, drawing the grid, checking for full rows, clearing rows, and handling block placement and 
collision detection. 
Game: 
The Game class controls the overall game logic, including block generation, user input handling, block movement and rotation, score tracking, and game state management (e.g., game over conditions). It 
integrates audio functionalities using Raylib Library for playing background music and sound effects.
Position: 
The Position class represents the coordinates of cells on the grid and is used extensively in the Block and Grid classes for positioning and movement calculations. 
Colors: 
The colors module defines various colors used for different Tetris pieces and grid cells, enhancing the visual appeal of the game. 

Gameplay Features
Block Rotation and Movement: 
Players can rotate blocks and move them left, right, or down using keyboard inputs. The game ensures blocks do not overlap or move outside the grid boundaries. 
Row Clearing and Scoring: 
Completed rows are automatically cleared from the grid, and the score is updated based on the number of rows cleared. 
Next Block Preview: 
The game displays the next block that will appear, allowing players to strategize their moves. 
Game Over Detection: 
The game detects when no more moves are possible, and displays a "Game Over" message, allowing the player to restart the game. 

Technical Details
Libraries and Tools: 
The game is built using the Raylib library for graphics rendering, handling input, and playing audio. It uses standard C++ libraries for data management and control structures. 
Object-Oriented Design: 
The game leverages OOP principles for modularity and code reuse, with classes representing various entities and functionalities within the game.
