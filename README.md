# 🧩 Sudoku Solver & Backtracking Visualizer

## Overview
This project is an interactive web application that solves 9x9 Sudoku puzzles using a recursive backtracking algorithm. Built entirely in Python using Streamlit, it goes beyond a standard backend script by providing a live, real-time visualization of the algorithmic state, showing exactly how the computer guesses, traverses, and backtracks to find the solution.

## Features
* **Interactive UI:** Users can input their starting puzzle directly into a clean, locked 9x9 grid on the web browser.
* **Live Algorithm Visualization:** Watch the recursive call stack in action. The grid updates in real-time, highlighting correctly placed digits in green and visually displaying backtracking paths.
* **Optimized Engine:** Utilizes mathematical sub-grid isolation to check validity in constant O(1) time, avoiding complex lookup tables.
* **Instant Solve Mode:** Option to bypass the animation and instantly calculate the final board state.

## Tech Stack
* **Language:** Python 3
* **Frontend/UI:** Streamlit
* **Data Handling & Styling:** Pandas

## Quick Start
To run this project locally, ensure you have Python installed, then follow these steps:

1. **Clone the repository**
   ```bash
   git clone [https://github.com/yourusername/sudoku-visualizer.git](https://github.com/yourusername/sudoku-visualizer.git)
   cd sudoku-visualizer


2. **Install Dependencies**
   ```bash
   pip install streamlit pandas

3. **Run the application**
    ```bash
    streamlit run app.py
