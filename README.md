# CodeAlpha_Sudoku-Solver
A simple C++ implementation of a Sudoku Solver using the backtracking algorithm. Accepts user input for a 9x9 grid and outputs the solved puzzle or reports if no solution exists.
# 🧩 Sudoku Solver in C++

This project is a console-based C++ Sudoku solver that uses the **Backtracking Algorithm** to fill in empty cells of a 9x9 Sudoku grid. You can enter your own puzzle and get a solution instantly (if it exists).

---

## 📌 Features

- Solves any valid 9x9 Sudoku puzzle using backtracking.
- User-friendly console input/output.
- Checks for validity before placing each number.
- Handles invalid input gracefully.

---

## 🚀 How It Works

1. Accepts user input for a 9x9 Sudoku board.
2. Uses a recursive backtracking function to solve the puzzle.
3. Verifies if a number placement is safe (row, column, and 3x3 box).
4. Prints the original and solved board.

---

## 🛠️ How to Run

### ✅ Prerequisites

- A C++ compiler like `g++`
- Basic terminal/command prompt

### 🔧 Compile and Run

g++ sudoku_solver.cpp -o sudoku_solver
./sudoku_solver

🖥️ Sample Input

Enter row 1 (9 numbers separated by space): 5 3 0 0 7 0 0 0 0
Enter row 2 (9 numbers separated by space): 6 0 0 1 9 5 0 0 0
Enter row 3 (9 numbers separated by space): 0 9 8 0 0 0 0 6 0
Enter row 4 (9 numbers separated by space): 8 0 0 0 6 0 0 0 3
Enter row 5 (9 numbers separated by space): 4 0 0 8 0 3 0 0 1
Enter row 6 (9 numbers separated by space): 7 0 0 0 2 0 0 0 6
Enter row 7 (9 numbers separated by space): 0 6 0 0 0 0 2 8 0
Enter row 8 (9 numbers separated by space): 0 0 0 4 1 9 0 0 5
Enter row 9 (9 numbers separated by space): 0 0 0 0 8 0 0 7 9
✅ Output Example

Original Sudoku Puzzle:
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
...
Solved Sudoku:
5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
...
📚 Concepts Used
Backtracking
2D vectors in C++
Recursive functions
Console input/output
Validity checks for Sudoku rules
