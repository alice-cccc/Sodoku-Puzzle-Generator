# Sodoku-Puzzle-Generator
## Project Title
Project Sodoku Puzzle Generator
## Student Name
Alice Chan
## How to Run the Program
1. Open your preferred Java IDE 
2. Create a new Java project.
3. Add a new class named SudokuGenerator.
4. Copy and paste the program code into the class file.
5. Make sure the file is saved and that the class contains a main method.
6. Run the program by clicking the Run button in the IDE 
7. The completed Sudoku board will appear in the IDE’s output window.
## Summary of how the Sodoku Board is Generated
The Sudoku board is generated using a recursive backtracking algorithm. The program begins with an empty 9×9 2D array. It scans the board to find the next empty cell and generates a list of numbers from 1 to 9 using an ArrayList. These numbers are then shuffled manually using random swapping.

For each empty cell, the program attempts to place numbers in random order. Before placing a number, it checks whether the placement is valid by ensuring the number does not already exist in the same row, column, or 3×3 subgrid. If the number is valid, it is placed in the cell, and the program recursively attempts to fill the next cell.

If the program reaches a point where no valid number can be placed, it backtracks by clearing the current cell and trying a different number. This process continues until the entire board is successfully filled. The use of randomization ensures that each generated Sudoku board is unique.
## List of Files Included in the Project
SudokuGenerator.java – Contains the main method and all supporting methods, including board generation, validation, randomization, and output formatting.

