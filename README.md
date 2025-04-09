# Tic-Tac-Toe Game

This is a simple implementation of the classic Tic-Tac-Toe game, written in Python. Players take turns to place their marks on a 3x3 board, with the goal of aligning three marks horizontally, vertically, or diagonally.

## Features

- Two-player gameplay (Player "X" and Player "O")
- Board validation for each move
- Winner check after every turn
- Game ends when a player wins or the board is full (a tie)

## Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/ulquiorraexe/tic-tac-toe.git
    ```

2. Navigate to the project directory:

    ```bash
    cd tic-tac-toe
    ```

3. No additional dependencies are required for this game. Simply run the game by executing the `main.py` file:

    ```bash
    python main.py
    ```

## Gameplay

- The game will alternate turns between two players: "X" and "O".
- On each turn, players will be prompted to enter the row and column (0, 1, or 2) where they want to place their mark.
- The game ends when one player aligns three marks horizontally, vertically, or diagonally.
- If the board becomes full without a winner, the game ends in a tie.

## Example

```
  |   |  
---------
  |   |  
---------
  |   |  

Player X, it's your turn.
Enter row (0, 1, or 2): 0
Enter column (0, 1, or 2): 1
  | X |  
---------
  |   |  
---------
  |   |  

Player O, it's your turn.
Enter row (0, 1, or 2): 1
Enter column (0, 1, or 2): 1
  | X |  
---------
  | O |  
---------
  |   |  

Player X, it's your turn.
Enter row (0, 1, or 2): 0
Enter column (0, 1, or 2): 0
  | X |  
---------
X | O |  
---------
  |   |  

Congratulations! Player X wins!
```

## Notes

- The game board consists of a 3x3 grid, with each cell represented by a space " ".
- Players alternate placing their respective marks ("X" or "O") on the grid.
- A player wins if they manage to place three of their marks consecutively in a row, column, or diagonal.
- The game checks for a winner after every move.
- The game also checks if the board is full, in which case it results in a tie if no winner is found.

## License 

This project does not have a license.
