# Deterministic & Non-Deterministic Finite Automata

## Deterministic Finite Automata (DFA)

An FA is characterized as a DFA if and only if:

1. For every input character, the machine has *only one* state

2. It *cannot* change its state without any input character

## Non-Deterministic Finite Automata (NFA)

- An NFA is similar to a DFA except for the following features:

    1. It can change states without any input character

    2. It can transmit to any number of states for a particular input

- Hence, its transition function becomes:

  - $\delta : Q \times { (\Sigma \cup \{\epsilon\}) } \rightarrow { 2^Q }$

- Therefore, we can mathematically conclude that **every DFA is an NFA**

- However, these features do not add any power to the NFAs in comparison to DFAs

- *If even a single path for an input string leads to a final state, then the string*
*is considered accepted*
