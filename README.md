# TetrisBlocks
A browser-based Tetris-style block packing visualizer that uses recursive backtracking to arrange predefined or custom 0/1 matrix shapes into an optimally sized grid.
# 🧩 Optimal Block Packing Visualizer

A browser-based Tetris-style block packing solver and visualization tool.

This application arranges predefined or custom 0/1 matrix blocks into an optimal rectangular grid that minimizes aspect ratio using a backtracking algorithm.

---

## 🚀 Features

- Predefined Tetris shapes (I, O, L, T, S, Z)
- Custom block input using 0/1 matrix format
- Multiple block copies
- Automatic optimal rectangle detection
- Backtracking packing solver
- Step-by-step animation
- Adjustable animation speed
- CSV export of final packed grid
- Responsive UI using Tailwind CSS

## 🛠 Technologies Used

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Canvas API
- Recursive Backtracking Algorithm

## 📂 Project Structure

```
tetris-block-packing/
│
├── index.html
└── README.md
```

## ▶️ How to Run
1. Download or clone the repository.
2. Open `index.html` in a modern browser.
3. Add blocks and click **Solve**.

No installation required.

## 🧠 Algorithm Overview
The solver uses recursive backtracking:
1. Compute total block area.
2. Generate possible rectangle dimensions.
3. Try each dimension sorted by aspect ratio closeness to 1.
4. Recursively place blocks in the first available empty cell.
5. Backtrack if placement fails.
6. Return first valid minimal-aspect solution.

## 📊 Output
- Displays optimal dimensions
- Shows aspect ratio
- Animates placement steps
- Allows CSV download of final grid

## 📌 Future Improvements
- Heuristic block ordering for faster solving
- Web Worker for non-blocking UI
- Backend API integration
- Performance optimization for large block sets
- Drag-and-drop block editor
  
## 📜 License
This project is for educational and demonstration purposes.
