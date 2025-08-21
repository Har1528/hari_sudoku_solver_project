# hari_sudoku_solver_project
# Sudoku Solver (C++)

## 📌 Overview
This is a simple **Sudoku Solver** implemented in **C++** using the **backtracking algorithm**.  
It takes a 9x9 Sudoku puzzle (with `0` representing empty cells) and fills it with a valid solution.

## ⚡ Features
- Solves any valid Sudoku puzzle.
- Uses recursion and backtracking.
- Simple console-based program.

## 🛠️ How It Works
1. Find the first empty cell (`0`).
2. Try placing digits `1–9`.
3. Check if the digit is valid (row, column, and 3x3 subgrid constraints).
4. If valid, place it and move to the next empty cell.
5. If stuck, backtrack (remove the digit and try the next).
6. Continue until solved.
