# Context-Free Grammar

- Context-free grammars represents context-free languages

- CFG production is in the form: $V \rightarrow (V + T)^*$

- All regular languages are context-free languages but not vice versa ($RL \subset CFG$)

- For example:

    $S \rightarrow{SSA\ |\ \epsilon} \\ A \rightarrow{bd^*Ae^+Sb\ |\ (a + b + c)^+}$

- They are called context-free because the LHS has only one non-terminal

- In other words, the value(s) of the non-terminal variables are always the same
regardless of the context
