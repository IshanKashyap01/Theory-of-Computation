# Recursively Enumerable Languages

- A langauage `L` is recursively enumerable, if there exists a turing machine
`M` such that for any string `w`:

    1. If $w \in L$, then `M` halts and accepts `w`

    2. If  $w \notin L$, then `M` either halts or loops indefinitely

- They are a superset of recursive languages

| Property            | Union | Intersection | Complement | Concatenation | Kleene Star | Difference |
|---------------------|-------|--------------|------------|---------------|-------------|------------|
| Recursive Languages | Yes   | No           | No         | Yes           | Yes         | No         |
| RE Languages        | Yes   | No           | No         | Yes           | Yes         | No         |
