---
layout: project
type: project
image: img/connectfour_logo.png
title: "Connect Four"
date: 2021-10-01
published: true
labels:
  - C
  - Game
summary: "My group programmed a game that simulated a real game called 'Connect 4' for our final project in EE 160."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Connect Four is an online game that functions similarly to the identically-named game, Connect 4, programmed in C as the final group project for EE 160. As the lead for this group project, I programmed the basic algorithms required to map the grid, win or draw, keep track of the score and placement of the discs, and set the Computer's move. The player was set to be able to play with another player or a computer that randomly places its pieces, named as 'discs,' across the 6 x 7 grid. Just like the renowned Connect 4 game, the player must place their discs four in a row either horizontally, vertically, or diagonally. When neither user wins after the final square is filled, it will be considered a draw. The game can keep track of how many games are won by either player or ended in a draw. For additional texture, the player(s) can choose their own piece, be it 'X' or 'C'.

To keep the text-based user interface of the grid, the package curses was used. To run 'Connect4', recompile the files using `gcc -o connect4 functions.c connect4.c -lncurses` and run the command `./connect4`.
