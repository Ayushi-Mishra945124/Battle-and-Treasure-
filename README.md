Battle and Treasure Game

A simple console-based adventure game written in C.
You explore a 5×5 grid, collect treasure, avoid enemies, and manage your health while navigating the map.
This project demonstrates basic C concepts such as arrays, randomization, structures, loops, and interactive game logic — ideal for first-year programming students.

Features

Move the player through a 5×5 grid (up, down, left, right).

Random placement of:

Treasure

Enemies

Empty spaces

Player health system (starts at 100).

Encounter outcomes:

Collect treasure

Lose health if encountering enemies

Win condition when all treasures are collected.

Lose condition when health reaches 0.

Requirements

GCC or any standard C compiler.

Build

To compile the game:

gcc battle_treasure_game.c -o battle_game

Run
Linux / macOS
./battle_game

Windows
battle_game.exe

Gameplay

After running the program:

Use numeric controls to move:

1 – Move Up

2 – Move Down

3 – Move Left

4 – Move Right

The grid updates after each move.

Health decreases when encountering enemies.

Treasure increases your score.

Game ends when:

All treasures are collected → You win!

Health reaches 0 → Game over.

Example Grid
@ . T . X
. . . . .
T . X . .
. . . . T
X . . . .


Symbols:
@ – Player
T – Treasure
X – Enemy
. – Empty

Notes

Grid updates every move.

Enemy and treasure positions are randomly generated each game (using rand() and srand(time(NULL))).

No game state is saved after exit.

Designed for beginners learning arrays and interactive C programs.

File Structure
battle_treasure_game.c
README.md

Future Improvements (Optional)

Add a score history file.

Add multiple levels with increasing difficulty.

Add sound or color-coded output in terminal.

Add saving/loading of game progress.
