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
What are the core features that your program should have? These should be things that __must__ be implemented in order to make the program useable/playable, not extra features that could be added to make the program more interesting/fun.

In order to recreate Conway's game of life and other extensions in Java, we will reference the Python code provided through NetLogo. By implementing functions that NetLogo simplified at the core, we will be able to build a setup and various booleans (setting the living status of different cells). To add, there needs to be a function to randomize the spawning cells and control the neighbors surrounding each live cell.

### Extra Features
What are some features that are not essential to the program, but you would like to see (provided you have time after completing the necessary features. Theses can be customizations that are not part of the core requirements.

Other than the primary automata, there needs to be additional randomization cell setups to make spawning images. By controlling the patterns of spawning, we could attempt to create  tessalations tiles (but less structured). 

### Array Usage
How will you be using arrays in this project?

1D Array:
- 1D Arrays can find the neighbors surrounding a single patch. Also, the 1D array can also help control colors if implemented.

2D Array:
- 2D Arrays are going to be used to control the columns and rows in the whole automata. It will help locate each cell and corporate with the 1D Arrays to work with neighbors.


### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.

Keyboard Commands:
- SPACE BAR -- pause + begin

Mouse Control:
- Mouse movement: restricted
- Mouse pressed: The cells surrounding the mouse pressed will be randomly switched to a live status.


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.

CLASS MainFrame
- Instance variables:
  - LIST INSTANCE VARS HERE
- METHODS
  - LIST METHODS HERE

CLASS Cell
- Instance variables:
  - LIST INSTANCE VARS HERE
- METHODS
  - LIST METHODS HERE
