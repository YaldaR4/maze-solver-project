Yalda Rawan  
CSC-468/668 Artificial Intelligence  
Spring 2026  
Final Project  


Project Title: Maze Solver using BFS, DFS, and A*

Description:
This project compares three search algorithms: Breadth-First Search (BFS), Depth-First Search (DFS), and A* in a grid-based maze. The goal is to find a path from a start point to a goal and evaluate the performance of each algorithm.

What I Did:
- Implemented BFS and DFS algorithms in the first stage
- Added the A* algorithm using the Manhattan distance heuristic
- Increased the maze size and created longer paths to better observe differences
- Compared the algorithms based on:
  - Path length
  - Number of explored nodes
  - Runtime

Results:
- BFS and A* found the shortest path
- DFS found a valid path, but sometimes longer
- A* performed best overall because it uses a heuristic to guide the search

Files Included:
- final_maze_solver_project.ipynb → Jupyter Notebook with code, results, and analysis
- maze_solver_presentation.pdf → Final presentation slides

How to Run:
Open the Jupyter Notebook file and run all cells to see the results.

Research Connection:
While working on this project, I explored research on pathfinding algorithms. I learned that the A* algorithm, introduced by Hart, Nilsson, and Raphael (1968), uses both path cost and a heuristic estimate to improve efficiency. This helped me understand why A* performed better in my results.

Future Work:
In the future, I would like to test larger and more complex mazes, try different heuristics, and add a visualization to show how each algorithm explores the maze step by step.

References:
Hart, P. E., Nilsson, N. J., & Raphael, B. (1968).
A Formal Basis for the Heuristic Determination of Minimum Cost Paths.

Russell, S., & Norvig, P. (2021).
Artificial Intelligence: A Modern Approach.