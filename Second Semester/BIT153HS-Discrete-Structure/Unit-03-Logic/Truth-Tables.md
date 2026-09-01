# Truth Tables

## Basic operators

| p | q | ¬p | p∧q | p∨q | p→q | p↔q |
|---|---|---|---|---|---|---|
| T | T | F | T | T | T | T |
| T | F | F | F | T | F | F |
| F | T | T | F | T | T | F |
| F | F | T | F | F | T | T |

## How to solve a truth-table problem

1. List all variables.
2. Create all possible T/F combinations.
3. Calculate each sub-expression from left to right.
4. Find the final column.
5. If final column is all T → tautology.
6. If final column is all F → contradiction.
7. Otherwise → contingency.

## Example

Test `p∨¬p`.

| p | ¬p | p∨¬p |
|---|---|---|
| T | F | T |
| F | T | T |

Therefore, `p∨¬p` is a tautology.
