# Interactive-Graph-Algorithms

A comprehensive collection of graph theory algorithms implemented in C++. This repository includes interactive Graphical User Interfaces (GUI) to visualize complex algorithmic processes such as pathfinding, network flows, and NP-hard problem approximations.

## 📌 Features & Implemented Algorithms

* [cite_start]**Interactive Graph Drawing:** A GUI application allowing users to manually draw directed and undirected graphs, move nodes via drag-and-drop [cite: 129, 131][cite_start], and automatically save the adjacency matrix to a file[cite: 127].
* [cite_start]**Maze Solver (BFS):** Reads a maze configuration from a text file and uses Breadth-First Search to find and visualize the shortest paths to all available exits[cite: 143, 149].
* [cite_start]**Topological Sort & Shortest Paths in DAG:** Implements a non-recursive Depth-First Search (DFS) for topological sorting [cite: 178, 222][cite_start], calculating the shortest paths from a source node to all others in $O(n + m)$ time complexity[cite: 160].
* [cite_start]**Graph Connectivity:** Algorithms to determine and color-code Connected Components in undirected graphs [cite: 227][cite_start], as well as Strongly Connected Components (SCC) in directed graphs, mapping them into a condensation graph[cite: 248, 250].
* [cite_start]**Traveling Salesperson Problem (TSP) Approximation:** Calculates the minimum distances between cities using Floyd-Warshall to generate a complete graph $K_n$[cite: 263]. [cite_start]It then builds a Minimum Spanning Tree (MST) using Prim's or Kruskal's algorithm (with Union-Find) [cite: 269, 270] [cite_start]and performs a preorder traversal to approximate the TSP circuit[cite: 271].
* [cite_start]**Max Flow & Min Cut:** Implements the Ford-Fulkerson algorithm to find the maximum flow in a network[cite: 49]. [cite_start]The application visually renders the residual network after each iteration [cite: 51] [cite_start]and explicitly highlights the edges that form the minimum cut[cite: 53].

## 🛠️ Technologies Used
* **Language:** Modern C++
* **UI/Visualization:** Custom Graphical User Interface (GUI)
* **Concepts:** Graph Theory, Dynamic Programming, Greedy Algorithms, Network Flows

## 🚀 How to Run

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/your-username/Graph-Algorithms-CPP.git](https://github.com/your-username/Graph-Algorithms-CPP.git)
