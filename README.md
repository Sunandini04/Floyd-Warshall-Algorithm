# Floyd-Warshall Algorithm

## Overview

The Floyd-Warshall Algorithm is a fundamental algorithm in computer science used to find the shortest paths between all pairs of vertices in a weighted graph. This algorithm is efficient for graphs with negative weights and can handle negative cycles by detecting them. It is widely used in network routing, urban traffic planning, and various applications involving shortest path computations.

## Problem Definition

### Given:

- An adjacency matrix `a` representing the weights of the edges between vertices in a weighted graph.
- The number of vertices `n`.

### Objective:

- Compute the shortest distances between all pairs of vertices.
- Update the adjacency matrix to reflect these shortest distances.



## Input Format

The input consists of:

- **Adjacency Matrix `a`**: A 2D array where `a[i][j]` represents the weight of the edge between vertex `i` and vertex `j`. If there is no edge, the value is set to a large number (infinity).
- **Number of Vertices `n`**: An integer representing the total number of vertices in the graph.


## Output Format

The output will be:

- **Resultant Adjacency Matrix**: A 2D array where `a[i][j]` represents the shortest distance from vertex `i` to vertex `j`.

