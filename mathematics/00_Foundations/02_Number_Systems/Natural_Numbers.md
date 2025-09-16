# Natural Numbers

## Mathematical Definition

The **natural numbers**, denoted by \(\mathbb{N}\), are the set of positive integers \(\{1, 2, 3, ...\}\). In some contexts, particularly in computer science and set theory, the natural numbers are defined to include 0, i.e., \(\{0, 1, 2, 3, ...\}\). For clarity, this set is sometimes denoted \(\mathbb{N}_0\) or \(\mathbb{N} \cup \{0\}\). In this document, we will use the definition that includes 0.

The natural numbers are formally defined by the **Peano Axioms**:
1.  0 is a natural number.
2.  Every natural number \(n\) has a successor, denoted \(S(n)\), which is also a natural number.
3.  0 is not the successor of any natural number.
4.  If \(S(n) = S(m)\), then \(n = m\). (Distinct natural numbers have distinct successors).
5.  **Axiom of Induction:** If a property is possessed by 0 and also by the successor of every natural number that possesses it, then it is possessed by all natural numbers.

In set theory, a common construction (the von Neumann ordinals) defines the natural numbers as sets:
*   \(0 = \emptyset = \{\}\)
*   \(1 = \{0\} = \{\emptyset\}\)
*   \(2 = \{0, 1\} = \{\emptyset, \{\emptyset\}\}\)
*   \(3 = \{0, 1, 2\} = \{\emptyset, \{\emptyset\}, \{\emptyset, \{\emptyset\}\}\}\)
In general, \(n+1 = n \cup \{n\}\).

## Description

The natural numbers are the numbers used for counting and ordering. They are the most basic and intuitive type of number.

## Subfields it's part of

*   [Number Systems](./)
*   [Number Theory](../../../05_Number_Theory/)
*   [Combinatorics](../../../06_Combinatorics/)

## Subfields and concepts it includes

*   **Successor Function:** The function \(S(n) = n+1\).
*   **Addition and Multiplication:** These operations can be defined recursively using the successor function.
*   **Ordering:** The natural numbers are well-ordered.
*   **Prime Numbers:** A natural number greater than 1 that has no positive divisors other than 1 and itself.
*   **Mathematical Induction:** A powerful proof technique based on the fifth Peano axiom.

## Applications

*   **Counting:** The most basic application.
*   **Discrete Mathematics:** The foundation of many topics in discrete mathematics.
*   **Computer Science:** Used for array indexing, iteration, and in algorithms. The study of computability is based on natural numbers.
*   **Cryptography:** Prime factorization of large natural numbers is the basis for many modern cryptographic systems.

## More general variants

*   [Integers](./Integers.md): \(\mathbb{Z}\)
*   [Rational Numbers](./Rational_Numbers.md): \(\mathbb{Q}\)
*   [Real Numbers](./Real_Numbers.md): \(\mathbb{R}\)
*   [Complex Numbers](./Complex_Numbers.md): \(\mathbb{C}\)
*   **Ordinal Numbers:** A generalization of the ordering aspect of natural numbers.
*   **Cardinal Numbers:** A generalization of the "size" aspect of natural numbers.

## More concrete variants

*   **Even and Odd Numbers**
*   **Prime and Composite Numbers**
*   **Perfect Numbers**

## Everything else it relates to

*   **Set Theory:** The modern definition of natural numbers is in terms of sets.
*   **Peano Axioms:** The formal axiomatic foundation for the natural numbers.
*   **Computability Theory:** The theory of which problems can be solved by algorithms is based on the natural numbers.
