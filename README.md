[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/PX83n--N)
# NeXtCS Project 01
### Name0: Isabel Zheng
### Name1: Sarah Kim 
---

### Overview
Your mission is create either:
- Life-like cellular automata [life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life), [life-like](https://en.wikipedia.org/wiki/Life-like_cellular_automaton), [demo](https://www.netlogoweb.org/launch#https://www.netlogoweb.org/assets/modelslib/Sample%20Models/Computer%20Science/Cellular%20Automata/Life.nlogo).
- Breakout/Arkanoid [demo 0](https://elgoog.im/breakout/)  [demo 1](https://www.crazygames.com/game/atari-breakout)
- Space Invaders/Galaga

This project will be completed in phases. The first phase will be to work on this document. Use markdown formatting. For more markdown help [click here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) or [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)


---

## Phase 0: Selection, Analysis & Plan

#### Selected Project: Cellular Automata (Conway's Game of Life) 

### Necessary Features
In order to recreate Conway's game of life and other extensions in Java, we will reference the Python code provided through NetLogo. By implementing functions that NetLogo simplified at the core, we will be able to build a setup and various booleans (setting the living status of different cells). To add, there needs to be a function to randomize the spawning cells and control the neighbors surrounding each live cell.

### Extra Features
Other than the primary automata, there needs to be additional randomization cell setups to make spawning images. By controlling the patterns of spawning, we could attempt to create  tessalations tiles (but less structured). 
- Change color of Live Cells (Left-Right Keys)

### Array Usage

1D Array:
- ~~1D Arrays can find the neighbors surrounding a single patch. Also, the 1D array can also help control colors if implemented.~~
  - ~~USE: To determine status of neighbors~~

2D Array:
- 2D Arrays are going to be used to control the columns and rows in the whole automata. It will help locate each cell and corporate with the 1D Arrays to work with neighbors.
  - USE: To populate the world with cells


### Controls

Keyboard Commands:
- SPACE BAR -- pause + begin
- DOWN -- switch simulation
- LEFT-RIGHT -- switch colors
- BACKSPACE -- setup blank
- 'R' -- setup random

Mouse Control:
- Mouse movement: restricted
- Mouse pressed: The cells surrounding the mouse pressed will be randomly switched to a live status.


### Classes

CLASS MainFrame
- Instance variables:
  - int cols, int rows
- METHODS
  - createFrame()
  - display()
  
CLASS Cell
- Instance variables:
  - int x, int y
  - color
  - boolean isAlive
- METHODS
  - void birth()
