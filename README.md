# PRODIGY_SD_04

Title: Sudoku Solver

This project implements a Sudoku solver using backtracking, a powerful algorithm for solving constraint satisfaction problems. It effectively solves Sudoku puzzles of any valid starting configuration.

Features:

* Solves Sudoku puzzles: Accurately solves Sudoku puzzles with valid starting configurations.
* Efficient backtracking: Employs backtracking for an efficient search through the solution space.
* Comprehensive validation: Ensures that solutions adhere to the core rules of Sudoku.
* Clear output: Presents the solved Sudoku grid in a well-formatted manner.

Prerequisites:

* Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))

Provide the Sudoku puzzle:

   The program will prompt you to enter the Sudoku puzzle in a specific format. You can either:
       - Manually enter the grid values row by row, separated by spaces.
       - Provide a path to a text file containing the Sudoku puzzle in the same format.

   Example manual input:

   ```
   5 3 0 0 7 0 0 0 0
   6 0 0 1 9 5 0 0 0
   ```

-> View the solution:

   If a solution exists, the program will display the solved Sudoku grid in a clear format. Otherwise, it will indicate that no solution is possible for the given puzzle.

Example Usage:

1. Run the program:

   ```bash
   python sudoku_solver.py
   ```

2. Enter a valid Sudoku puzzle:

   ```
   5 3 0 0 7 0 0 0 0
   6 0 0 1 9 5 0 0 0
   ```

3. The program will print the solved Sudoku grid:

   ```
   5 3 1 6 8 4 9 2 7
   6 7 2 1 9 5 3 4 8
   4 9 8 3 2 7 5 1 6
   8 5 9 7 6 1 4 3 2
   1 2 6 8 5 3 7 9 4
   7 4 3 2 9 8 6 5 1
   2 6 7 4 1 9 8 5 3
   9 1 5 3 4 2 1 7 6
   3 8 4 5 7 6 2 1 9
   ```

