# Finite Automata

## DFA

A DFA can be represented as:

`M=(Q,Σ,δ,q0,F)`

where:
- Q = finite states
- Σ = input alphabet
- δ = transition function
- q0 = initial state
- F = final states

## How to read a DFA

1. Start at the initial state.
2. Read the input from left to right.
3. Follow the transition for each symbol.
4. After the complete string is read:
   - final state → accepted
   - non-final state → rejected

## NFA

An NFA may have multiple possible transitions for the same state and symbol.

## DFA vs NFA

| DFA | NFA |
|---|---|
| Exactly one transition for each state/input pair | Zero, one or many transitions possible |
| One active path | Multiple possible paths |
| Easier to execute directly | Often convenient for construction |

## Typical exam tasks

- Identify states and alphabet.
- Complete a transition table.
- Determine whether a string is accepted.
- Draw a state diagram.
- Construct a simple finite automaton for a specified language.
