# Regular Expressions & Languages

- A regular expression represents a regular language

- Conversely, if a language can be represented as a regex, it is a **regular language**

## Operators Used in Regular Expressions

### OR Operator (`+`)

Represents the logical OR and is used as `A + B`

### Concatenation (`.`)

Represents concatenation as either `A . B` or `AB`

### Kleene Plus or Positive Closure ($^+$)

Represented as `A`$^+$, it means that A has to be repeated at least once

### Kleene Star or Kleene Closure (`*`)

- Represented as `A*`, it means that A can be repeated any number of times including
zero

- It can also be written as `A`* = `A`$^+$ $\cup$ `A`$^0$
