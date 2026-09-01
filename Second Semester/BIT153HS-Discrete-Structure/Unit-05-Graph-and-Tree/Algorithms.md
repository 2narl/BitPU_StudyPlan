# Graph Algorithms

## 1. Kruskal's Algorithm

Used to find a minimum spanning tree.

Steps:
1. Sort edges by increasing weight.
2. Select the smallest edge.
3. Add it if it does not form a cycle.
4. Continue until `n-1` edges are selected.

## 2. Prim's Algorithm

Steps:
1. Start with any vertex.
2. Select the minimum-weight edge connecting the current tree to a new vertex.
3. Add the new vertex and edge.
4. Repeat until all vertices are included.

## 3. BST traversal

### Inorder
Left → Root → Right

### Preorder
Root → Left → Right

### Postorder
Left → Right → Root

For a standard BST, inorder traversal gives keys in sorted order.
