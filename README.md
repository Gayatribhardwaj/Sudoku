# Sudoku
This Java program solves a 9x9 Sudoku puzzle using backtracking. It checks each empty cell and fills it with a valid digit (1–9) while following Sudoku rules: no duplicate numbers in any row, column, or 3x3 grid. If a solution exists, it prints the completed puzzle; otherwise, it notifies that no solution exists.

This is a simple Java program that solves any valid 9x9 Sudoku puzzle using the **backtracking algorithm**. The program fills in empty cells (denoted by `0`) while ensuring that all Sudoku rules are followed:
- No duplicate digits in any row
- No duplicate digits in any column
- No duplicate digits in any 3x3 subgrid

## Features
- Uses recursion and backtracking
- Validity check for each digit placement
- Prints the solved Sudoku board

## How to Use
1. Compile and run the `sudoku.java` file.
2. The puzzle is hardcoded as a 2D array.
3. The program will print the solution if one exists.
