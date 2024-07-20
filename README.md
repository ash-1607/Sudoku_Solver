# Sudoku_Solver
This project is a C++ implementation of a Sudoku solver. The solver takes a partially filled 9x9 Sudoku board as input and attempts to fill the empty cells with digits from 1 to 9, following the rules of Sudoku. The rules are:
- Each row must contain the digits 1-9 without repetition.
- Each column must contain the digits 1-9 without repetition.
- Each of the nine 3x3 sub-grids must contain the digits 1-9 without repetition.

## Features
- Efficiently solves any given valid Sudoku puzzle using backtracking.
- Uses bitsets to track the digits present in each row, column, and 3x3 sub-grid, enhancing performance.
<br>

## Usage and Instructions
- Compile and run the file. *(input is in the code itself, in the main function)*
- On running, it will display the *initial grid*, the *expected solved grid* and then if solved, outputs *final solved grid*, otherwise error: *not solvable*.
- The file also contains 3 extra sudoku grids to test.
