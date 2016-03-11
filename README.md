# MineSweeper
Game Design and Implementation

##Goal
The goal of the MineSweeper is to discover and mark all the mines.

##GameWorld
- grid
- hidden mines
- mines
- marked case
- hidden empty case
- empty case

##Rules
- at the start of the game the grid is randomly fill with hidden mines and hidden empty cases
- if the player reveal a hidden mine, the player loose the game
- the empty case have a number (0 to 8) wich show the number of hidden mines touching that empty case
- when all the mine are marked the player win the game
- the player can mark the empty hidden case but it doesn't count to win the game

##Gameplayer
The player have to left click on a case to reveal it or right click on it to mark the case as a mine.
