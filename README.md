# Interactive-Graph-Algorithms

A comprehensive collection of graph theory algorithms implemented in C++. This repository includes interactive Graphical User Interfaces (GUI) to visualize complex algorithmic processes such as pathfinding, network flows, and NP-hard problem approximations.

## 📌 Features & Implemented Algorithms

* **Interactive Graph Drawing:** A GUI application allowing users to manually draw directed and undirected graphs, move nodes via drag-and-drop, and automatically save the adjacency matrix to a file.
* **Maze Solver (BFS):** Reads a maze configuration from a text file and uses Breadth-First Search to find and visualize the shortest paths to all available exits.
* **Topological Sort & Shortest Paths in DAG:** Implements a non-recursive Depth-First Search (DFS) for topological sorting, calculating the shortest paths from a source node to all others in linear time complexity.
* **Graph Connectivity:** Algorithms to determine and color-code Connected Components in undirected graphs, as well as Strongly Connected Components (SCC) in directed graphs, mapping them into a condensation graph.
* **Traveling Salesperson Problem (TSP) Approximation:** Calculates the minimum distances between cities using Floyd-Warshall to generate a complete graph. It then builds a Minimum Spanning Tree (MST) using Prim's or Kruskal's algorithm (with Union-Find) and performs a preorder traversal to approximate the TSP circuit.
* **Max Flow & Min Cut:** Implements the Ford-Fulkerson algorithm to find the maximum flow in a network. The application visually renders the residual network after each iteration and explicitly highlights the edges that form the minimum cut.

## 🛠️ Technologies Used
* **Language:** Modern C++
* **UI/Visualization:** Custom Graphical User Interface (GUI)
* **Concepts:** Graph Theory, Dynamic Programming, Greedy Algorithms, Network Flows

## 🚀 How to Run

### 1. Prerequisites
* A C++ compiler that supports C++17 or later.
* Your preferred C++ IDE (e.g., Visual Studio, Qt Creator, or CLion).

### 2. Build and Execute
Clone this repository to your local machine:
```bash
git clone [https://github.com/your-username/Graph-Algorithms-CPP.git](https://github.com/your-username/Graph-Algorithms-CPP.git)
