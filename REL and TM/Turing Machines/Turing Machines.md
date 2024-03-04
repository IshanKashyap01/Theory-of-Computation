# Turing Machines

- Turing machines are the most powerful machines that recognize **recursively**
**enumerable languages**

- A turing machine is a finite automaton that can read, write and erase symbols
from an infinitely long, one-dimensional tape

- Therefore, unlike PDAs and FAs, turing machines' input tape is of infinite length

## Working of a Turing Machine

- They may use the input tape itself as the work tape or have them read-only and
write on a separate work tape instead

- They can traverse on either direction of the tape(s)

- They also have a variation that uses two stacks for computation rather than a
work tape

## Elements of a Turing Machine

Turing machines have the same elements/components as a finite automata with two
additional elements:

### Tape Alphabet ($\tau$)

- Set of symbols that can written on the input tape

- It is the superset of $\Sigma$ as it also includes the blank symbol

### Blank Symbol (`B`)

Represents a blank input cell on the input tape; every non-input cell is marked
blank

## Types of Turing Machines

- Turing machines can also be either deterministic or non-deterministic

- Just like finite automata, DTM and NTM have the same expressive power

- Their transition functions are given as follows:

  - $\delta_{DTM}: Q \times{\tau} \rightarrow Q \times{\tau} \times${$L, R$}

  - $\delta_{NTM}: Q \times{\tau} \rightarrow 2^{Q \times{\tau} \times\{L, R\}}$
