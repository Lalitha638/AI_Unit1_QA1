AI – Qualitative Assessment 1
Tower of Hanoi Implementation (DFS, BFS, A*)

This repository contains the implementation of the Tower of Hanoi problem with 3 disks and 3 pegs using three different search strategies as required for QA1 – Artificial Intelligence.

📁 Repository Structure
ai_files/  
   ├── dfs.py / dfs.java  
   ├── bfs.py / bfs.java  
   ├── astar.py / astar.java  

output/  
   ├── dfs_output.png  
   ├── bfs_output.png  
   ├── astar_output.png  


ai_files folder → Contains the 3 program source code files (DFS, BFS, A*).

output folder → Contains the full-screen output screenshots showing date, time, and program result.

🧠 Search Strategies Implemented
1. Depth First Search (DFS)

Explores the deepest possible move before backtracking.

Suitable for simple search but may get stuck in deep paths.

2. Breadth First Search (BFS)

Explores all nodes level by level.

Guarantees the shortest solution path for Tower of Hanoi.

3. A* Search Algorithm

Uses cost function f(n) = g(n) + h(n).

Efficient and finds the optimal solution using heuristic evaluation.

🎯 Problem Description

The task is to move 3 disks from the source peg to the goal peg following the rules:

Only one disk can be moved at a time.

A larger disk cannot be placed on top of a smaller disk.

Pegs must be used logically according to the search strategy.

📌 How to Run the Programs
If using Python
python dfs.py
python bfs.py
python astar.py

If using Java
javac DFS.java
java DFS

javac BFS.java
java BFS

javac AStar.java
java AStar

✔️ Submission Requirements Covered

 DFS program

 BFS program

 A* program

 All three program files uploaded

 Full-screen outputs added with date & time

👩‍💻 Author

Lalitha
Qualitative Assessment – Artificial Intelligence
