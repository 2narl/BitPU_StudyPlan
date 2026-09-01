# Unit 02 – Function and Counting

## Official syllabus
- Functions
- Function for computer science
- Permutation
- Combination
- Pigeonhole principle
- Recurrence relation

## 1. Functions

A function `f:A→B` assigns every element of A exactly one element of B.

- Domain: A
- Codomain: B
- Range: actual output values

### Types
- One-to-one (injective)
- Onto (surjective)
- Bijective
- Many-to-one

### Composition
`(f∘g)(x)=f(g(x))`

### Inverse
A function has an inverse function when it is bijective.

## 2. Functions for computer science

Important functions include:
- Floor: `⌊x⌋`
- Ceiling: `⌈x⌉`
- Exponential functions
- Boolean functions

## 3. Permutation

Permutation is an arrangement where order matters.

`nPr = n!/(n-r)!`

## 4. Combination

Combination is a selection where order does not matter.

`nCr = n!/[r!(n-r)!]`

Relation:
`nPr = nCr × r!`

## 5. Pigeonhole Principle

If more than n objects are placed into n boxes, at least one box contains at least two objects.

Generalized form:
If N objects are distributed among k boxes, at least one box contains at least `ceil(N/k)` objects.

## 6. Recurrence relation

A recurrence relation defines a sequence using previous terms.

Example:
`a_n=a_(n-1)+2`

Common solving approaches:
- Iteration/substitution
- Recognizing a pattern
- Characteristic equation for suitable linear recurrences

## Exam focus
1. Function types and composition
2. Permutation vs combination
3. Basic and generalized pigeonhole principle
4. Recurrence relation problems
