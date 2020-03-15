# cillz
Multiplayer game with WebSockets

# Overview 

cillz is a multi-player browser based for or up to 4 players, each player will have a unique color and the players fight to dominate the board (16x16) in 30 seconds. At the end of the 30 seconds the player with the most cells under his or her color wins. Player can capture other players cells. 

# Game Details

Players only use their browser (mobile or desktop) to play, no download or login required. A player goes to the cillz website and create a a new game to get unique link that can be shared with others players. When a player opens the  link, they will have the option to join the game.The game can be joined by exactly 4 players each player will be assigned a unique color based on their order of joining.

## Create Game 
A player goes the cillz website and click on create game this will return a unique url that can be shared. The player who creates the game automatically joins it and get the first color (RED)

## Join Game 
Player opening the link will automatically join the game and get assigned a color. (RED, BLUE, GREEN, PURPLE?). 

The players colors will be displayed in order. The current player color will be magnified indiacting that this is YOU. 

When a player joins a game the board will be drawn (16x16). The board will be in a locked state and no action will be taking when a player clicks on any cell. 


## Game Start
The creator of the game (RED) will have an option to start the game if at least 1 other player joined. Once the game is started no players can join.

The game will give players 3 seconds count down and once its up the game start and the board will be unlocked so players can play. 

## Game Play 
The game runs for 30 seconds, players during this click on cells to change their color to the player's color. Cells initial color is gray means its unequipied.

Player can capture cells that belong to other players in last in win manner. The board updates every few millseconds.

The timer will go down starting from 30 and will be updated every second. 

## Game End 
After the 30 seconds elapses the game is done and the player with most cells wins and board is locked again. 

The game can result in a draw.

## Restart Game
Optional feature to let the players play again. The creator of the game can restart the game and that will reinitiliaze the board and automatically rejoin existing players to the game (if they are still connected) and the counter will start counting.




