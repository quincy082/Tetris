# InSem2Project

### Group Name: Pixels

<br>

### Student 1: Dia Pitroda
### Student Id: 202404009

<br> 

### Student 2: Vadi Quincy Hiren
### Student Id: 202401488

<br>

### Student 3: Sania Debbarma
### Student Id: 202404037

<br>

# Tetris - C++ Implementation

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Compilation and Execution](#compilation-and-execution)
- [Controls](#controls)
- [High Score System](#high-score-system)
- [Game Screenshot](#game-screenshot)

## Introduction
This is a simple command-line implementation of the classic Tetris game written in C++. It features basic gameplay mechanics, including rotating and moving tetrominoes, clearing rows, and tracking scores.

## Features
- Classic Tetris gameplay with different tetromino shapes.
- Controls for movement, rotation, and hard drop.
- Score and high score tracking, with persistent storage.
- Console-based graphical representation.

## Requirements
- C++ Compiler (G++/MSVC/Clang)
- Windows OS (uses Windows-specific console commands)
- `conio.h` and `windows.h` headers

## Compilation and Execution
To compile the game, use the following command in a terminal (for MinGW/G++):
```sh
g++ -o tetris tetris.cpp -std=c++11
```
To run the compiled program:
```sh
./tetris
```

## Controls
- `A` - Move left
- `D` - Move right
- `S` - Move down
- `W` - Rotate piece
- `Space` - Hard drop
- `ESC` - Exit game

## High Score System
The game saves the highest score in a file named `highscore.txt`. When the game is restarted, the high score is loaded from this file.

## Game Screenshot
![Tetris Screenshot](image.png)

