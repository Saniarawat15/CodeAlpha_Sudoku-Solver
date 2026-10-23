# 🧩 CodeAlpha Sudoku Solver in C++

A simple console-based **Sudoku Solver implemented in C++** using the **Backtracking Algorithm**. The program accepts a 9×9 Sudoku puzzle from the user, solves it by filling in the empty cells, and displays the solved puzzle if a solution exists.

## 📌 Features

- Solves valid 9×9 Sudoku puzzles using backtracking.
- Accepts user input through the console.
- Checks whether a number can be placed safely in a row, column, and 3×3 subgrid.
- Uses recursion to explore possible solutions.
- Displays the original Sudoku puzzle and the solved board.
- Reports when no solution exists.

## ⚙️ Technologies Used

- **Programming Language:** C++
- **Algorithm:** Backtracking
- **Concepts:** Recursion, 2D arrays or vectors, conditional statements, and console input/output.
- **Compiler:** GCC (`g++`) or any compatible C++ compiler.

## 🚀 How It Works

1. **Input:** The user enters the numbers of a 9×9 Sudoku puzzle row by row.
2. **Find Empty Cells:** The program identifies empty cells, represented by `0`.
3. **Check Validity:** It checks whether a number from 1 to 9 can be placed without violating Sudoku rules.
4. **Backtracking:** The program places a valid number and recursively attempts to solve the remaining puzzle. If a choice leads to a dead end, it removes that number and tries another possibility.
5. **Output:** The program displays the solved Sudoku puzzle or reports that no solution exists.

## 🛠️ Prerequisites

Before running the project, make sure you have:

- A C++ compiler, such as GCC.
- A terminal or command prompt.
- A code editor, such as Visual Studio Code (optional).

## ▶️ How to Compile and Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd CodeAlpha_Sudoku-Solver
```

### 2. Compile the Program

Make sure the source file is named `sudoku_solver.cpp`, then run:

```bash
g++ sudoku_solver.cpp -o sudoku_solver
```

### 3. Run the Program

**Windows:**

```bash
.\sudoku_solver.exe
```

**Linux / macOS:**

```bash
./sudoku_solver
```

## 🖥️ Sample Input

Enter the following Sudoku puzzle row by row. Use `0` to represent an empty cell.

```text
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

## ✅ Sample Output

```text
Solved Sudoku:

5 3 4 6 7 8 9 1 2
6 7 2 1 9 5 3 4 8
1 9 8 3 4 2 5 6 7
8 5 9 7 6 1 4 2 3
4 2 6 8 5 3 7 9 1
7 1 3 9 2 4 8 5 6
9 6 1 5 3 7 2 8 4
2 8 7 4 1 9 6 3 5
3 4 5 2 8 6 1 7 9
```

*Note: The exact console messages depend on your program's implementation.*

## 🧠 Algorithm: Backtracking

Backtracking is a recursive problem-solving technique that tries possible choices one by one. If a choice does not lead to a solution, the algorithm reverses that choice and tries another.

### Algorithm Steps

1. Find an empty cell in the Sudoku grid.
2. Try placing a number from 1 to 9.
3. Check whether the number satisfies the Sudoku rules.
4. If valid, recursively solve the remaining grid.
5. If the choice fails, reset the cell to `0` and try another number.
6. If no empty cells remain, the puzzle is solved.

## 📚 Concepts Learned

- Backtracking algorithm
- Recursive functions
- Sudoku validation
- Two-dimensional data structures
- Logical problem-solving
- C++ programming fundamentals

## 🎯 Project Objective

The objective of this project is to understand and implement the backtracking algorithm in C++ by solving a Sudoku puzzle efficiently through recursion and logical validation.

## 👩‍💻 Internship

**Internship Program:** CodeAlpha  
**Project:** Sudoku Solver in C++  
**Language:** C++

---

⭐ If you find this project useful, consider giving the repository a star!

