# Closure Properties For Regular Languages

## Union [✅]

- The union of two regexes $\alpha$ and $\beta$ will be $(\alpha + \beta)$ which
is also a regex

- Therefore, the union of two RLs is *always* an RL

## Intersection [✅]

- Similarly, the intersection of a left and a right RG will only contain productions
with no variables on RHS

- Whereas, for the same type, the intersection would also be the same type of RL

- Therefore, the intersection of two RLs is *always* an RL

## Complement [✅]

- Suppose we have a Finite Automaton accepting a regular language $L$

- If we flip the accepting and non-accepting states, the automaton will accept
every input that isn't a string in $L$

- In other words, we have built an automaton that accepts $\bar L$

- Therefore, the complement of an RL is *always* an RL
