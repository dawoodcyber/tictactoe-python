# TicTacToe Project

This is a simple TicTacToe game implemented in Python using Jupyter Notebook. The game allows two players to take turns and input their moves until one of them wins or the game ends in a draw.

## How to Play

1. The game starts with an empty 3x3 board.
2. Player 'X' makes the first move by entering the position (e.g., 'top-l', 'med-m', etc.).
3. The board is updated and displayed after each move.
4. Players take turns until one player wins by placing three of their marks in a horizontal, vertical, or diagonal row, or until the board is full, resulting in a draw.

## Board Positions

The board positions are labeled as follows:

```
top-l | top-m | top-r
------+-------+------
med-l | med-m | med-r
------+-------+------
low-l | low-m | low-r
```

## Winning Conditions

A player wins if they have three of their marks in any of the following:

- Horizontal rows: `top-l, top-m, top-r`, `med-l, med-m, med-r`, `low-l, low-m, low-r`
- Vertical columns: `top-l, med-l, low-l`, `top-m, med-m, low-m`, `top-r, med-r, low-r`
- Diagonal: `top-l, med-m, low-r`, `top-r, med-m, low-l`

## How to Run

1. Clone the repository to your local machine.
2. Open the Jupyter Notebook.
3. Copy and paste the code into a new Jupyter Notebook cell.
4. Run the cell and follow the on-screen instructions to play the game.
