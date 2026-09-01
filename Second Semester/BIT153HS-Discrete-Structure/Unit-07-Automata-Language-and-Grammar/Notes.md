# Unit 07 – Automata, Language and Grammar

## Official syllabus
- Introduction
- Finite-state automata
- Strings
- Languages
- Regular expressions
- Grammars

## 1. Automata

An automaton is an abstract mathematical model of computation.

A finite automaton consists of:
- Finite set of states
- Input alphabet
- Transition function
- Start state
- Set of accepting/final states

## 2. Finite-state automata

Main types:
- DFA (Deterministic Finite Automaton)
- NFA (Nondeterministic Finite Automaton)

### DFA
For each state and input symbol, exactly one next state is defined.

### NFA
A state/input pair may have zero, one, or multiple possible transitions.

## 3. Strings

A string is a finite sequence of symbols from an alphabet.

Important terms:
- Alphabet `Σ`
- Empty string `ε`
- Length `|w|`
- Concatenation
- Reverse

## 4. Language

A language over alphabet Σ is a set of strings over Σ.

Examples:
`L={0,1,00,11}`

## 5. Regular expressions

Regular expressions describe regular languages.

Common operations:
- Union: `R|S`
- Concatenation: `RS`
- Kleene star: `R*`

## 6. Grammar

A grammar describes how strings in a language can be generated.

A formal grammar is often written as:

`G=(V,T,P,S)`

where:
- V = variables/non-terminals
- T = terminals
- P = productions
- S = start symbol

## Exam focus
1. Components of finite automata
2. DFA vs NFA
3. Strings and language
4. Regular expressions
5. Grammar and production rules
6. Construct/read simple finite automata
