# MineSweeper
Game Design and Implementation

##Goal
The goal of the MineSweeper is to reveal all the empty cases.

##GameWorld
- grid
- hidden mines
- mines
- marked case
- hidden empty case
- empty case

##Rules
- at the start of the game the grid is randomly fill with hidden mines and hidden empty cases
- the player can reveal a case by left clicking on it
- if the player reveal a hidden mine, the player loose the game
- if the player reveal an empty case, the empty case show a number (0 to 8) that indicates the number of mines adjacent to the case
- the player can mark a case by right clicking on it
- the player can mark the empty case or the mines

##GamePlayer
The player have to left click on a case to reveal it or right click on it to mark the case as a mine.
