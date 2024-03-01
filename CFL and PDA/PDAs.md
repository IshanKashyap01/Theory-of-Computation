# Pushdown Automata (PDA)

- A PDA is an automaton that extends the capabilities of an FA by adding a stack

- PDAs are used to recognize *context-free languages* but can also recognize RLs

- For instance, for the language {$a^nb^n | n \ge 0$}:

  - The PDA can push all the `a`s into the stack

  - Then for every `b`, it will pop an `a` to check for equality b/w `a`s and `b`s

## Elements of a PDA

PDAs have the same elements as an FA plus two additional elements for the stack

### Stack Alphabet ($\Gamma$)

Set of all symbols pushed into the stack

### Initial Symbol (`Z`$_0$)

Placed on the stack before the process begins, it is often used to mark the
start/end of the input string

## Properties of Pushdown Automata

- PDAs, like FAs, are **always halting** machines

- PDAs also have **finite states** and can only process a **finite input**

- PDAs, like FAs, can be either deterministic or non-deterministic

- Similarly, every DPDA is also an NPDA i.e. $DPDA \subset NPDA$
