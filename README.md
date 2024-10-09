# Sudoku

## Introduction:
Sudoku is a logic-based number-placement puzzle. The objective is to fill a 9x9 grid with digits so that each column, each row, and each of the nine 3x3 subgrids that compose the grid contain all of the digits from 1 to 9. The puzzle setter provides a partially completed grid, which for a well-posed puzzle has a single solution.


## Game rules:
- The game is played on a 9x9 grid, divided into rows, columns, and 3x3 subgrids.
- The goal of the game is to fill in the entire grid with numbers from 1 to 9.
- Each row, column, and 3x3 subgrid must contain each number exactly once.
- The game starts with some cells already filled in, which cannot be changed.
- The player must fill in the remaining cells following the rules mentioned above.

## How to play:
- Run the `sudoku_game.py` file to start the game.
- Use the arrow keys to navigate the cursor on the grid.
- Use the number keys to fill in the cells with numbers.
- Use the `Delete` key to clear a cell.
- Use the `Space` key to check the correctness of the grid.
- Use the `H` key to get a hint for the current cell.
- Use the `S` key to save the game.
- Use the `N` key to start a new game.
- Use the `Q` key to quit the game.
- Use the `D` key to change the difficulty level of the game.
- Use the `R` key to get the solution to the grid.
- Use the `C` key to clear the entire grid.
- Use the `U` key to undo the last move.

## Game screenshots:

![Game start](screenshots/start.png)

## Game features:
- Random generation of Sudoku grids with varying difficulty levels.
- Check correctness of the grid at any time during the game.
- Get a hint for the current cell.

## Requirements:
- Python 3