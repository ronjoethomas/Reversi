# Reversi
Reversi game with a simple computer AI opponent and a GUI

The rules of reversi are detailed here: https://www.mastersofgames.com/rules/reversi-othello-rules.htm

Following the rules you have to flip as many of the opponents pieces (White or Black) as possible before the game ends

In this rendition of reversi, you are first prompted to enter the dimensions of the board you want to play on. Please choose an even number between 4-24. You are then prompted to choose the color the computer (AI) plays. Enter W or B for computer to play as White or Black respectively. NOTE: Black always goes first.

A 6x6 board starts off looking like this:

![Alt text](Reversi/reversi_pic.PNG?raw=true "Start game 6x6")

As the game continues (with valid moves) it should look like this:

![Alt text](Reversi/reversi_midgame_pic.PNG?raw=true "Start game 6x6")

The game ends in a couple ways:
      1) If a player makes an invalid move (other play wins)
      2) If both players are unable to make a valid move (the player with the most colours on the board wins)
      3) If the board is full (the player with the most colours on the board wins)

Here is one of the win cases:

![Alt text](Reversi/reversi_endgame_pic.PNG?raw=true "Start game 6x6")
