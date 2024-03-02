# Introduction to Regular Languages

- An RL can be represented by a regular expression/grammar and recognized by a
Finite Automata

- Therefore, a non-regular language can neither be expressed by a regex/RG, nor
recognized by an FA

- For ex. { $a^mb^n | m, n \ge 0$ } is an RL as:

  - `m` and `n` are independent of each other, and

  - The language can be represented as a regex like $(a + b)^*$

- However, { $a^mb^n | m, n \ne 0$ } is not an RL as:

  - `m` and `n` are co-dependents of each other,

  - The language *cannot* be represented by a *regex/RG*

  - An FA cannot be built for it as FAs cannot have *infinite states*
