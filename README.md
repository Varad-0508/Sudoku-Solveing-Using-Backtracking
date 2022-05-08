# Sudoku-Solveing-Using-Backtracking
Java Code that reads any NxN Sudoku-puzzle from a file and finds solution to it. 
Uses Recursive Backtracking algorithm and therefore a solution is always gauranteed, except in case of sudokus with no solution. 
Also displays how much time it takes to find solution to a particular puzzle.

# Usage Instructions:
1) Download the Sudoku.jar along with the puzzle.txt file
2) Make sure these files are in the same directory 
3) Load your puzzle in the puzzle.txt file. Make sure you follow the format posted below. 
An example puzzle has been loaded. 
4) 0 stands for empty cells which the code tries to find solution to.
5) From your terminal navigate to the directory where you saved the file
6) Type in java -jar Sudoku.jar
An alternative is typing java -jar space Drag and Drop the jar file. This only works for Linux and MacOS.

# NOTE:
You need to specify the number of number of rows and columns of the smaller box. 
This is implemented for solving higher NxN puzzles where rows are not equal to the columns. 
Example, for a 12x12 Sudoku Puzzle, each smaller box is 3x4. This also ensures a nice sudoku layout when printed.

