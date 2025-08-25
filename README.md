# 🧩 Maze Solver (Breadth-First Search)

## 📌 Description
This project implements a **Maze Solver** using the **Breadth-First Search (BFS)** algorithm.  
The maze is displayed in the **terminal using curses**, and the solver visually explores paths until it finds the shortest route from the **start (O)** to the **exit (X)**.

---

## 🚀 How to Run

```js
python.exe find_path_maze.py
```

### ⚠️ Note: This project uses the curses library, which works natively on Linux/macOS.

On Windows, you may need to install windows-curses:3

```js
pip install windows-curses
```

### 🎮 Controls & Features

The maze is displayed in blue

The found path is marked in red (X)

The solver animates the BFS step-by-step in the terminal

### 📚 Concepts Used

Breadth-First Search (BFS)

Queue data structure (queue.Queue)

Maze representation with 2D arrays

Curses library for terminal rendering

Pathfinding visualization

### 🖼️ Example Output

```js

O . # . . . # . # . . . # . # . . # . .
# . # # # . # . # # # . # . # # . # # .
# . . . # . . . . . . . # . . . . . . .
# # # . # # # # # # . # # # # # # # # .
. . # . . . . . . # . . . . . . . . # .
. # # # # # # # . # # # # # # # # . # .
. # . . . . . # . . . . . . . . # . # .
. # # # # # . # # # # # # # # . # # # .
. . . . . # . . . . . . . . # . . . . .
# # # # . # # # # # # # # # . # # # # .
. . . . . . . . . # . . . . . # . . # .
. # # # # # # # . # . # # # # # # . # .
. . . . . . # . . . . # . . . . # . . .
. # # # # . # # # # # # . # # . # # # .
. . . . . . . . . . . . # . . . . . . .
# # # . # # # # # # . # . # # # # # # #
. . . . # . . . . . . # . # . . . . . .
. # # # # # # # # # # # . # # # # # # .
. . . . . . . . . # . . . . . . . . . .
# # # # # # # # # . # # # # # # # # # X

```
(O = Start, X = Goal, # = Wall)




### demo 



https://github.com/user-attachments/assets/af1f7203-9a19-4595-8ffc-1a14e6455c87





### 💡 Ideas to Extend

Load mazes from an external JSON file (mazes.json)

Generate random mazes instead of hardcoding them

Add support for DFS or A search* for comparison

Add color themes for different states (visited, frontier, path)

### source code ☺️👇

[source code](https://github.com/kodjoballo/Maze_solver/blob/main/find_path_maze.py)

