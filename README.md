# tic-tac-toe
Tic-Tac-Toe Game (Python)
A simple Python implementation of a Tic-Tac-Toe (or Noughts and Crosses) game using NumPy. The game features two players who randomly place their marks (1 for Player 1 and 2 for Player 2) on a 3x3 grid. The game continues until one player wins or the board is full (resulting in a tie).

Features:
2-Player Game: Simulates a two-player game where each player takes turns.
Random Moves: Players make random moves on available spots on the board.
Win Detection: The game automatically detects when a player wins by filling a row, column, or diagonal.
Tie Detection: The game also checks for a tie if all spots are filled and no player has won.
Interactive Display: The board is printed after each move to show the game's progress.

Game Logic:
Players are represented by the numbers 1 (Player 1) and 2 (Player 2).
The board is a 3x3 NumPy array where 0 indicates an empty space.
The game randomly selects an empty space for each player on their turn.
After every move, the game checks for a winner or a tie.
