# Unit 05 – Graph and Tree

## Official syllabus
- Graphs
- Euler path and circuit
- Hamiltonian path and circuit
- Trees
- Labeled tree
- Binary search tree
- Minimal spanning tree

## 1. Graph

A graph is represented as `G=(V,E)` where V is the set of vertices and E is the set of edges.

### Important terms
- Vertex
- Edge
- Degree
- Adjacent vertices
- Simple graph
- Multigraph
- Complete graph
- Connected graph
- Subgraph

For an undirected graph:

`sum of degrees = 2|E|`

## 2. Euler path and circuit

- Euler path: uses every edge exactly once.
- Euler circuit: starts and ends at the same vertex and uses every edge exactly once.

For a connected undirected graph:
- Euler circuit exists when every vertex has even degree.
- Euler path but not circuit exists when exactly two vertices have odd degree.

## 3. Hamiltonian path and circuit

- Hamiltonian path visits every vertex exactly once.
- Hamiltonian circuit visits every vertex exactly once and returns to the starting vertex.

## 4. Trees

A tree is a connected undirected graph with no cycles.

For a tree with n vertices:

`|E|=n-1`

Important properties:
- Exactly one simple path between every pair of vertices.
- Removing any edge disconnects a tree.
- Adding one edge creates a cycle.

## 5. Labeled tree

A labeled tree has labels assigned to vertices or edges.

## 6. Binary search tree

For each node:
- Keys in left subtree are smaller.
- Keys in right subtree are larger, under the usual BST convention.

Traversals:
- Preorder: Root, Left, Right
- Inorder: Left, Root, Right
- Postorder: Left, Right, Root

## 7. Minimal spanning tree

A spanning tree connects all vertices with no cycle.

A minimum/minimal spanning tree has minimum total edge weight.

Common algorithms:
- Kruskal's algorithm
- Prim's algorithm

## Exam focus
1. Degree and graph properties
2. Euler path/circuit
3. Hamiltonian path/circuit
4. Tree properties
5. BST traversal
6. Minimum spanning tree
