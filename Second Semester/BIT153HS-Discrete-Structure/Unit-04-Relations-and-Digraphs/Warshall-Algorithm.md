# Warshall's Algorithm

## Purpose

Warshall's algorithm is used to find the **transitive closure** of a directed relation/graph.

## Input

A Boolean adjacency matrix `A`.

## Update rule

For each intermediate vertex `k`:

`a_ij^(k) = a_ij^(k-1) OR [a_ik^(k-1) AND a_kj^(k-1)]`

In simple form:

`new = old OR (through-k)`

## Steps

1. Write the adjacency matrix.
2. Take vertex 1 as an intermediate vertex.
3. Update all entries using vertex 1.
4. Repeat for vertex 2.
5. Continue until vertex n.
6. The final matrix represents the transitive closure.

## Exam tip

Show every intermediate matrix clearly. Do not jump directly to the final answer.

## Complexity

For n vertices, Warshall's algorithm takes approximately:

`O(n^3)`.
