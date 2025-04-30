# Algorithms and Data Structures in C++

This repository contains C++ implementations of fundamental algorithms and data structures. It's organized by algorithmic paradigms and includes concise explanations and performance details for each algorithm.

---

##  Table of Contents

- [Sorting Algorithms](#sorting-algorithms)
- [Mathematical & Miscellaneous Algorithms](#mathematical--miscellaneous-algorithms)
- [Divide and Conquer](#divide-and-conquer)
- [Greedy Algorithms](#greedy-algorithms)
- [Dynamic Programming](#dynamic-programming)

---

##  Sorting Algorithms

These algorithms arrange elements in a particular order (ascending/descending).

| Algorithm             | Best Case   | Average Case | Worst Case   | Space       | Stable |
|----------------------|-------------|--------------|--------------|-------------|--------|
| Selection Sort       | O(n²)       | O(n²)        | O(n²)        | O(1)        | ❌     |
| Bubble Sort          | O(n)        | O(n²)        | O(n²)        | O(1)        | ✅     |
| Insertion Sort       | O(n)        | O(n²)        | O(n²)        | O(1)        | ✅     |
| Merge Sort           | O(n log n)  | O(n log n)   | O(n log n)   | O(n)        | ✅     |
| Quick Sort           | O(n log n)  | O(n log n)   | O(n²)        | O(log n)    | ❌     |
| Iterative Quick Sort | O(n log n)  | O(n log n)   | O(n²)        | O(log n)    | ❌     |

**Files**:
- `bubblesort.cpp`
- `insertionsort.cpp`
- `iterativequicksort.cpp`

---

##  Mathematical & Miscellaneous Algorithms

| Algorithm               | Description |
|-------------------------|-------------|
| **Peak Element Finder** | Finds local maxima in 1D & 2D using binary search techniques. |
| **Magic Square** (`magicsquare.cpp`) | A square matrix with constant row, column, and diagonal sums. |
| **Cosine Similarity** (`cosinsimilarity.cpp`) | Measures similarity between two text files treated as vectors. |
| **Jaccard Similarity** (`jaccard.cpp`) | Compares two sets by intersection over union. |

---

##  Divide and Conquer

| Algorithm | Description |
|----------|-------------|
| **Binary Search** (`binarysearch.cpp`) | Efficiently searches sorted arrays in O(log n). |
| **Max-Min Problem** (`maxmin.cpp`) | Finds the max and min values in fewer comparisons. |
| **Strassen's Matrix Multiplication** | Multiplies matrices faster than conventional O(n³) method. |

---

##  Greedy Algorithms

| Algorithm | Description |
|----------|-------------|
| **Activity Selection** (`activitysel.cpp`) | Selects max non-overlapping activities. |
| **Fractional Knapsack** (`knapsack.cpp`) | Picks items to maximize value within weight limits. |
| **Dijkstra's Algorithm** (`dijkstra.cpp`) | Computes shortest paths from source node. |
| **Prim’s Algorithm** | Builds minimum spanning tree. |
| **Kruskal’s Algorithm** (`kruskals.cpp`) | Builds MST using sorted edges and union-find. |

---

##  Dynamic Programming

| Algorithm | Description |
|----------|-------------|
| **Multi-Stage Graph** (`MGP.cpp`) | Solves shortest path problems stage-wise. |
| **Floyd-Warshall** (`allPairdp.cpp`) | Finds shortest paths between all node pairs (O(n³)). |

## ♟ Backtracking

Backtracking is a technique for solving problems incrementally, building candidates and abandoning a path if it fails to satisfy constraints.

| Algorithm   | Description |
|-------------|-------------|
| **N-Queens** (`mqueens.cpp`) | Places N queens on an N×N chessboard so that no two queens threaten each other. Uses recursion and backtracking to explore valid board configurations. |

---


