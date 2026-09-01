# Unit 04 – Relation and Digraphs

## Official syllabus
- Product sets and partitions
- Relations and digraphs
- Paths in relations and digraphs
- Properties of relations
- Equivalent relations
- Manipulation of relations
- Transitive closure
- Warshall's algorithm

## 1. Cartesian/product set

The Cartesian product `A×B` is the set of ordered pairs `(a,b)` where `a∈A` and `b∈B`.

If `|A|=m` and `|B|=n`, then `|A×B|=mn`.

## 2. Partition

A partition divides a set into nonempty, pairwise disjoint subsets whose union is the whole set.

## 3. Relation

A relation R from A to B is a subset of `A×B`.

For a relation on A:
`R⊆A×A`.

## 4. Properties of relations

- Reflexive: `(a,a)∈R` for every a.
- Irreflexive: `(a,a)∉R` for every a.
- Symmetric: `(a,b)∈R ⇒ (b,a)∈R`.
- Antisymmetric: `(a,b),(b,a)∈R ⇒ a=b`.
- Transitive: `(a,b),(b,c)∈R ⇒ (a,c)∈R`.

## 5. Equivalence relation

A relation is an equivalence relation if it is:
- Reflexive
- Symmetric
- Transitive

Equivalence relations produce equivalence classes and partitions.

## 6. Digraph

A directed graph represents relations using directed edges.

- Vertex = element
- Directed edge `a→b` = `(a,b)∈R`

## 7. Paths

A path is a sequence of vertices connected by directed edges.

Understand:
- Path
- Circuit
- Reachability

## 8. Manipulation of relations

Important operations:
- Union
- Intersection
- Difference
- Inverse relation
- Composition

## 9. Transitive closure

The transitive closure of R is the smallest transitive relation containing R.

## 10. Warshall's algorithm

Warshall's algorithm finds the transitive closure of a relation represented by a Boolean adjacency matrix.

Basic idea:
For `k=1,...,n`, update:

`a_ij = a_ij OR (a_ik AND a_kj)`

## Exam focus
1. Relation properties
2. Equivalence relation
3. Digraph representation
4. Relation operations
5. Transitive closure
6. Warshall's algorithm
