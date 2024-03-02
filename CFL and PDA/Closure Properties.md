# Closure Properties of Context-Free Languages

| Language | Union   | Intersection | Complement      | Concatenation | Kleene Star |
|----------|---------|--------------|-----------------|---------------|-------------|
| DCFL     | Closed  | Closed       | Closed          | Closed        | Closed      |
| CFL      | Closed  | Not always   | Not always      | Closed        | Closed      |

<!-- markdownlint-disable MD024-->
## Union

- Consider any CFLs (either DCFL or CFL) `L`$_1$ and `L`$_2$

- Their union would be $L = ${ $L_1 + L_2$ }, which is also the same type of CFL

## Intersection

- As DCFLs are a subset of CFLs, their could be two CFLs such that their intersection
is a DCFL

- For ex. { $a^mb^nc^k |\ n = k \text{ or } n = m$ } and { $a^mb^nd^k |\ n = k \text{ or } n = m$ }
