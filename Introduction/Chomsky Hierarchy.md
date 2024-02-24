# Chomsky Hierarchy in Theory of Computation

- It is a classification system for formal grammars

- It classifies them into four types based on their *generative powers* or *expressive*
*capabilities*

- It provides a framework for:

    1. Understanding the relative power and complexity of different types of formal
    languages and grammars

    2. Their relationships to various computational models

## Type 0 Grammar

- Recognized by **Turing machines**, it is also known as **unrestricted grammar**

- Type 0 grammars generate **Recursively Enumerable Languages**

- Grammar production is in the form: $S \rightarrow (V + T)^* V (V + T)^*$

- There must be at least one variable on the LHS of the productions

- That is, there are no restrictions on production

## Type 1 Grammar

- Accepted by **Linear Bound Automata**, it is also known as **Context-Sensitive**
**Grammar**

- Type 1 grammars generate **Context-Sensitive Languages**

- It is a **subset** of Type 0 grammar

- In a production $\alpha \rightarrow \beta$, $|\alpha| <= |\beta|$

- That is, the number of symbols on the LHS must not exceed the number of symbols
on the RHS

## Type 2 Grammar

- Accepted by **Push Down Automata**, it is also known as **Context-Free Grammar**

- Type 2 grammars generate **Context-Free Languages**

- It is a subset of Type 1 grammar

- In a production $\alpha \rightarrow \beta$, $|\alpha| = 1$

- That is, there can only be one symbol on the LHS

## Type 3 Grammar

- Accepted by **Finite Automata**, it is also known as **Regular Grammar**

- Type 3 grammars generate **Regular Languages**

- It is a subset of Type 2 grammar

- Its production can be either in the form:

    1. $V \rightarrow VT^* | T^*$ known as *left regular grammar* or,
  
    2. $V \rightarrow T^\*V | T^\*$ known as *right regular grammar*
