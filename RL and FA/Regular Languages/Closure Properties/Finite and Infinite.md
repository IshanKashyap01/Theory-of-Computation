# Closure Properties Based on Finite & Infinite

## Union [❌✅]

The resultant of two *finite* languages *may or may not be finite*. For ex:

1. Consider $L_1 = \{a\}$ and $L_2 = \{b\}$

    - $L_1 \cup L_2 = \{a, b\}$ which is also a finite language

2. Now consider $L_1 = \{a^n | n \ge 0\}$ and $L_2 = \{b^n | n \ge 0\}$

    - $L_1 \cup L_2 = \{a^nb^n | n \ge 0\}$ which is an infinite language

## Intersection [✅❌]

The intersection of two *infinite* languages *may or may not be infinite*. For
ex:

1. Consider $L_1 = \{a^nb^n | n \ge 0\}$ and $L_2 = \{b^nc^n | n \ge 0\}$

    - $L_1 \cap L_2 = \{b^n | n \ge 0\}$ which is infinite

2. Now consider $L_1 = \{a^n | n \ge 0\}$ and $L_2 = \{b^n | n \ge 0\}$

    - $L_1 \cap L_2 = \{\}$ which is finite

## Complement [❌❌]

- Recall that the complement of a set is a set with all elements from the universal
set that aren't in the original set

- This means the complement of a finite language is an infinite language

- Whereas, the complement of an infinite language may or may not be infinite

  - This is because $\infin - \infin$ cannot be determined

- Therefore, the complement for both finite and infinite languages *may or may*
*not be closed*
