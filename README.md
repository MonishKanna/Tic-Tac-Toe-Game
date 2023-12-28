# Tic Tac Toe Game

A simple console-based implementation of the classic Tic Tac Toe game in Python.

## How to Play

1. The game is played on a 3x3 grid.
2. Players take turns to mark their symbol ('X' or 'O') in an empty cell.
3. The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
4. If the board is filled and no player has won, the game ends in a draw.

## Getting Started

To run the game, follow these steps:

1. Ensure you have Python installed on your machine.
2. Copy the provided code into a Python script (e.g., `tic_tac_toe.py`).
3. Open a terminal or command prompt.
4. Navigate to the directory containing the script.
5. Run the script using the command `python tic_tac_toe.py`.

## Gameplay

- The game randomly selects the starting player ('X' or 'O').
- Players take turns entering the row and column numbers (1-3) to make a move.
- The board is displayed after each move for reference.
- The game ends when a player wins or the board is filled.

## Code Overview

The code uses a 3x3 matrix to represent the game board. Key functions include:

- `is_board_filled()`: Checks if the board is completely filled.
- `is_winner(current_player)`: Checks if the current player has won.
- `print_board()`: Prints the current state of the board.
- `play_game()`: Main function to start and control the game.

Feel free to explore and modify the code to enhance or customize the game according to your preferences.

Have fun playing Tic Tac Toe!
