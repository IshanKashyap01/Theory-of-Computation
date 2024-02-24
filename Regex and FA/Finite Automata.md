# Finite Automata

- It is the simplest machine to recognize patterns and is used to characterize
a **regular language**

- It is an abstract model of a digital computer that reads an input string and
changes its state based on the current symbol

- Every automaton defines a language i.e. the set of strings it accepts

- Based on the states and set of rules, the input can be either accepted or rejected

- An FA can be either deterministic or non-deterministic

## Elements of Automata

### States (`Q`)

A finite set of configurations/conditions that the machine can be in, at any given
moment during its operation

### Alphabet ($\Sigma$)

A finite set of symbols from which the input strings are formed

### Transition function ($\delta$)

- Describes how the automaton moves b/w states in response to input symbols

- In other words, it maps a state and an input symbol to a new state

- It is represented as $\delta : Q \times{\Sigma} \rightarrow{Q}$

### Initial state (`q`$_0$)

Starting configuration of the machine

### Accepting states (`F`)

The states in which the automaton can end its operation by accepting the given
string

## Properties of Finite Automata

- If the machine encounters a symbol for which it has no states or if it reaches
the end of the string, it will halt

- Therefore, Finite Automata are **always halting** machines

- FAs have **finite states** and can only process a **finite input**
