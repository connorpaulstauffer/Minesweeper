# Minesweeper

## Description

Ruby implementation of the puzzle game, Minesweeper. Playable in the command
line.


## Features

  * Users can save a game state and return to it later
  * $stdin.getch method and [cursor logic][board] enables players to navigate
  the board with the w, a, s, and d keys
  * Recursive reveal method uncovers entire sequence of non-mine positions.
  * Color-coded clues expose the number of neighboring mines.

[display]: ./board.rb


## Instructions

Clone this repository to a local directory. ```cd``` into the repository. Run
```ruby game.rb```. Navigate the board with the w, a, s, and d
keys. Reveal a position with the r key. Flag a position with the f key. Quit
with q and follow the instructions to save your game. 
