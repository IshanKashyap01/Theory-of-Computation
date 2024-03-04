# Properties of Turing Machines

- Due to their infinte tapes, turing machines **may or may not halt**

- TMs are capable of simulating any algorithm that can be defined in a step-by-step
manner

  - This property is known as **computational universality**

- A decision problem is decidable if there exist a turing machine that can solve
it

## Closure Properties

| Property | Union | Intersection | Complement | Concatenation | Kleene Star | Difference |
|----------|-------|--------------|------------|---------------|-------------|------------|
| DTM      | Yes   | Yes          | No         | Yes           | Yes         | No         |
| TM       | Yes   | Yes          | No         | Yes           | Yes         | No         |
