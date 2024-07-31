This repository contains a C++ implementation of a chess game featuring an AI opponent powered by the Minimax algorithm. The game allows you to play against the computer, which evaluates moves up to a depth of 4 to determine the best possible move.

Features
Classic Chess Gameplay: Enjoy the traditional chess game with all the standard rules.
AI Opponent: Play against an AI that uses the Minimax algorithm to evaluate and make moves.
Dynamic Board Display: View the chessboard with pieces in their current positions.
Interactive Commands: Use simple text commands to make moves, show the board, and toggle coordinates display.
Piece Promotion: Pawns are automatically promoted to queens upon reaching the opponent's back rank.
Victory Conditions: The game ends when either player's king is captured.

How to Play
Choose a side: When prompted, type b to play as black, w to play as white, or q to quit.
Move pieces: Input moves using the format yxyx, where the first two digits are the coordinates of the piece you want to move, and the last two digits are the coordinates of the destination (e.g., 1715 to move a piece from (1, 7) to (1, 5)).
Show the board: Type p to print the current state of the board.
Toggle coordinates display: Type c to toggle the display of coordinates inside the squares.
Show help: Type h or ? to display the help message.
Quit the game: Type q to quit.
