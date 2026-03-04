# Graph BFS Traversal (C++)

## Overview
This project demonstrates **Graph representation using adjacency lists** and implements **Breadth First Search (BFS) traversal** in C++.

The graph is undirected and uses dynamic memory allocation for storing adjacency lists.

## Features
- Graph representation using adjacency list.
- BFS traversal using queue data structure.
- Visited node tracking using vector boolean array.

## Data Structure Used

### Graph Class
Stores:
- `V` → Number of vertices.
- `l` → Array of adjacency lists using `list<int>`.

### Node Class
Note: The `Node` class is declared but not used in this implementation.

## Functions

### Graph(int V)
Constructor that:
- Initializes number of vertices.
- Allocates memory for adjacency list array.

### addEdge(int u, int v)
Adds an undirected edge between:
- Vertex `u` and vertex `v`.

Both directions are added to maintain an undirected graph.

### bfs()
Performs **Breadth First Search traversal**:
- Uses queue for traversal order.
- Uses vector<bool> to track visited nodes.
- Starts traversal from vertex 0.

## How to Compile and Run

### Compile
```bash
g++ main.cpp -o graph
Run
./graph
Example Graph

Edges added in main():
0 — 1
1 — 2
2 — 3
1 — 3
2 — 4

BFS Traversal Output Example
0 1 2 3 4

Concepts Covered
Graph Data Structures
Adjacency List Representation
Breadth First Search Algorithm
Queue Data Structure
Dynamic Memory Allocation

Possible Improvements
Add Depth First Search (DFS).
Allow user input for graph creation.
Add weighted graph support.

Author
Created for learning Data Structures and Algorithms in C++.
