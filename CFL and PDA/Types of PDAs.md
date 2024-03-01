# Types of Pushdown Automata

- Unlike FA, some CFL problems can *only* be solved by NPDAs and not DPDAs

- For example, {$ww^R | w \in$ {$a, b$}*} cannot be recognized by a DPDA as it
requires more than one decision for a symbol

## Deterministic Pushdown Automata

- For any given combination of the current state, top of the stack, and input symbol,
there is at most one valid transition

- Its transition function is given by:

    $\delta: Q \times{\Sigma} \times{\Gamma} \rightarrow{Q \times{\Gamma}^*}$

## Non-Deterministic Pushdown Automata

- For any given combination of the current state, top of the stack, and input symbol,
there can be any number of valid transitions

- Its transition function is given by:

    $\delta: Q \times{\Sigma_\epsilon} \times{\Gamma} \rightarrow{2^{Q \times{\Gamma}^*}}$
