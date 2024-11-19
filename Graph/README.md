# Graph Data Structure Implementation in Python
This repository contains a Python implementation of a Graph using an adjacency list. The program focuses on solving fundamental graph problems, including:
  -Finding all possible paths between two nodes.
  -Determining the shortest path between two nodes using DFS.
## Key Features:
1. ### Graph Representation:
   - The graph is represented as a dictionary, where keys are nodes and values are lists of connected nodes.
2. ### Find All Routes:
   -Recursively finds all possible paths from a starting node to a destination node.
3. ### Shortest Path Calculation:
   -Uses the length of paths to determine the shortest route between two nodes.
## Example:
### Input Graph:
```
    routes = [
         ('Mumbai', 'Dhaka'),
         ('Dhaka', 'Mymensingh'),
         ('Khulna', 'Dhaka'),
         ('Rajshahi', 'Dhaka'),
         ('Rajshahi', 'Khulna'),
         ('Sylhet', 'Dhaka')
    ]
```
## Functionality:
  - All paths from Rajshahi to Mymensingh:
      -Rajshahi ➡️ Khulna ➡️ Dhaka ➡️ Mymensingh
      -Rajshahi ➡️ Dhaka ➡️ Mymensingh
  - Shortest path: Rajshahi ➡️ Dhaka ➡️ Mymensingh.
## Applications:
This implementation is suitable for learning and understanding graph algorithms and can be applied to:
  -Route planning.
  -Data flow analysis.
  -Network optimization.
Feel free to contribute or share feedback! 😊
