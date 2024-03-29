# Basic Terminologies in TOC

## Symbol

- A symbol or a character is the smallest building block in a language

- It includes alphabets and punctuation marks

## Alphabets ($\Sigma$)

A finite, non-empty set of symbols

## Strings/Words (`w`)

- A string is a sequence of symbols from some alphabet

- There could be any number of strings for a given language (from 0 to infinity)

- Its length is denoted by `|w|`

## Grammar

- It is a finite set of rules that produces all the valid words of a language

- In general, a grammar contains the following:

    1. **Terminals** `T`: an alphabet

    2. **Non-terminals** `V`: a placeholder/variable

    3. **Production rules** `R`: produces words and sentences

    4. **Start symbol** `S`: a special non-terminal symbol that serves as a starting
    point for generating strings.

## Operations

- `+` represents the union of two sets

  - For ex. (V + T) means the union of V and T

- `|` represents a choice b/w two sets

  - For ex. (V | T) means either V or T

### Closure Representation

- $^+$ is a **positive closure** that represents a set of all strings *except*
the null string ($\epsilon$)

- $^*$ is a **Kleene closure** that represents a set of all strings *including*
null

  - It is also known as the **Kleene star**

- $\Sigma^*$ represents the set of all possible strings from the given alphabet

## Language

- A language is a subset of the $\Sigma^*$ over a given alphabet $\Sigma$

- A language formed over $\Sigma$ can be either finite or infinite

## Closure Properties

- Closure properties on a language are defined as operations/transformations
whose resultant is of the same class

- A language that follows a closure property over some operation, is said to be
**closed** under the said operation
