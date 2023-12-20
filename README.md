# Dijkstra's Algorithm Implementation

## Overview

This Python script implements Dijkstra's algorithm for finding the shortest paths in a weighted graph. The graph is represented using an adjacency matrix.

## Getting Started

### Requirements
- Python 3.x

### Installation
- Clone the repository or download the script.

### Usage
1. Import the `Graph` class and the `dijkstra` function into your project.
2. Create a `Graph` object, add edges using the `add_edge` method.
3. Call the `dijkstra` function with the graph object and the start vertex.

```python
from queue import PriorityQueue

class Graph:
    # ... (class implementation)

g = Graph(9)
# Add edges to the graph
# ...

# Call Dijkstra's algorithm
D = dijkstra(g, 0)
print(D)
