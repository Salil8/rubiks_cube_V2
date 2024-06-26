# Rubik's Cube Solver

## Korf's Research Paper
A PDF of Richard Korf's seminal research paper on solving the Rubik's Cube using the Iterative Deepening A* (IDA*) algorithm is available in the repository. This paper serves as the theoretical foundation for the IDA* solver implemented in this project.

## Description:
This project is a Rubik's Cube solver implemented in C++ using CLion. The virtual Rubik's Cube is modeled using a 3D array data structure, leveraging Object-Oriented Programming (OOP) principles for clarity and modularity. It includes advanced solving algorithms such as Depth-First Search (DFS), Breadth-First Search (BFS), Iterative Deepening Depth-First Search (IDDFS), and Iterative Deepening A* (IDA*) for optimal solving strategies. Additionally, a Corner Pattern Database is utilized for efficient heuristic computation, significantly enhancing Rubik's Cube solving efficiency.

## Features:
Rubik's Cube modeling: The cube's state is represented using a 3D array data structure.
DFS Solver: Utilizes depth-first search to explore and solve the Rubik's Cube.
BFS Solver: Implements breadth-first search to find the shortest solution path.
IDDFS and IDA* Solvers: Implements iterative deepening algorithms for efficient solving.
Corner Pattern Database: Utilizes a database for heuristic computation, optimizing solving strategies.

## Installation:
Clone the repository or download the source code.
Open the project in CLion.
Build and compile the project (main.cpp) using the C++ compiler.

## Usage:
Run the compiled executable file.
Uncomment the desired solving algorithm (DFS, BFS, IDDFS, or IDA*).
The cube gets randomly jumbled.
The program will find a solution and display the steps to solve the Rubik's Cube.
Dependencies:
This project has no external dependencies and is developed solely using C++, leveraging the standard library.

## Contributions:
Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, feel free to create a pull request or open an issue.

## Author:
This project is created by Salil Lokhande. You can contact me at salillokhande14@gmail.com.

Enjoy solving the Rubik's Cube with the provided solver!
