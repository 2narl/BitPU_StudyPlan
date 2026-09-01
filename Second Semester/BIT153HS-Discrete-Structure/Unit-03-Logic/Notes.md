# Unit 03 – Logic

## Official syllabus
- Proposition and logical operation
- Conditional statement
- Proof techniques
- Mathematical induction

## 1. Proposition

A proposition is a declarative statement that is either true or false, but not both.

Example:
"2+3=5" is a proposition.

Questions and commands are normally not propositions.

## 2. Logical operations

For propositions p and q:

- Negation: `¬p`
- AND: `p∧q`
- OR: `p∨q`
- XOR: `p⊕q`
- Implication: `p→q`
- Biconditional: `p↔q`

## 3. Tautology, contradiction and contingency

- Tautology: always true.
- Contradiction: always false.
- Contingency: sometimes true and sometimes false.

## 4. Logical equivalence

Two propositions are logically equivalent when they have the same truth value for every possible combination of inputs.

Notation:
`p ≡ q`

Important laws:
- Identity
- Domination
- Idempotent
- Double negation
- De Morgan's laws
- Commutative
- Associative
- Distributive

## 5. Conditional statement

`p→q` is read as "if p, then q".

It is false only when p is true and q is false.

Related statements:
- Converse: `q→p`
- Inverse: `¬p→¬q`
- Contrapositive: `¬q→¬p`

A conditional and its contrapositive are logically equivalent.

## 6. Valid arguments

An argument is valid if the conclusion logically follows from the premises.

Important forms:

**Modus Ponens**
`p→q, p ∴ q`

**Modus Tollens**
`p→q, ¬q ∴ ¬p`

Invalid forms:
- Affirming the consequent: `p→q, q ∴ p`
- Denying the antecedent: `p→q, ¬p ∴ ¬q`

## 7. Proof techniques

Important methods:
- Direct proof
- Proof by contrapositive
- Proof by contradiction
- Proof by cases
- Exhaustive proof where appropriate

## 8. Mathematical induction

To prove a statement `P(n)` for all positive integers:

### Step 1: Base case
Show `P(1)` is true.

### Step 2: Inductive hypothesis
Assume `P(k)` is true.

### Step 3: Inductive step
Show `P(k+1)` is true.

### Step 4: Conclusion
Therefore, `P(n)` is true for all required positive integers.

## Exam focus
1. Truth tables
2. Logical equivalence
3. Conditional, converse, inverse and contrapositive
4. Valid arguments
5. Proof techniques
6. Mathematical induction
