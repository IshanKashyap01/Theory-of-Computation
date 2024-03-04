# Recursive Languages

- A langauage `L` is recursive, if there exists a turing machine `M` such that
for any string `w`:

    1. If $w \in L$, then `M` halts and accepts `w`

    2. If  $w \notin L$, then `M` halts and rejects `w`

- In other words, a language is recursive if a turing machine can decide whether
a string belongs to it or not in a finite amount of time

- They are also called **decidable languages** as there exists a procedure through
which we can always decide whether a string belongs to it or not
