# Combinations and Permutations

- **Mathematical Definition**:
    - **Permutation**: A permutation is an arrangement of members of a set into a sequence or linear order. The number of permutations of $k$ elements taken from a set of $n$ distinct elements is denoted by $P(n, k)$ or $_nP_k$ and is calculated as:
      $$ P(n, k) = \frac{n!}{(n-k)!} $$
      This counts the number of ways to arrange $k$ items from $n$ available items where the order of selection matters.
    - **Combination**: A combination is a selection of items from a collection, such that the order of selection does not matter. The number of combinations of $k$ elements from a set of $n$ elements is denoted by $C(n, k)$, $_nC_k$, or $\binom{n}{k}$ (the binomial coefficient), and is calculated as:
      $$ C(n, k) = \binom{n}{k} = \frac{n!}{k!(n-k)!} $$

- **Description**: Permutations and combinations are the two fundamental concepts in combinatorics, the branch of mathematics concerned with counting. Permutations are about ordered arrangements, while combinations are about unordered selections. Understanding the difference is key to solving many counting problems.

- **Subfields it's part of**:
    - [Combinatorics](https://en.wikipedia.org/wiki/Combinatorics)
    - [Discrete Mathematics](https://en.wikipedia.org/wiki/Discrete_mathematics)
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory)

- **Subfields and concepts it includes**:
    - **Factorial**: The product of all positive integers up to a given integer.
    - **Binomial Coefficient**: The coefficients of the terms in the expansion of $(x+y)^n$.
    - **Binomial Theorem**: A theorem that describes the algebraic expansion of powers of a binomial.

- **Applications**:
    - **Probability and Statistics**: Used to calculate the number of possible outcomes in an experiment, forming the basis for computing probabilities.
    - **Computer Science**: Used in the analysis of algorithms, cryptography, and in areas like network topology.
    - **Statistical Mechanics**: Used to count the number of possible states of a system.
    - **Genetics**: Used to count the number of ways genes can be combined.

- **More Concrete Variants**:
    - **Permutations with Repetition**: Arrangements where elements can be used more than once.
    - **Combinations with Repetition**: Selections where elements can be chosen more than once.
    - **Circular Permutations**: Arrangements of objects in a circle.

- **More General Variants**:
    - **Multiset Permutations/Combinations**: Counting arrangements and selections from a multiset (a set with repeated elements).
    - **Enumerative Combinatorics**: The broader field of counting combinatorial objects.

- **Related Concepts**:
    - **[Probability Space](../../../applied_mathematics/probability_theory/probability_space.md)**: Combinatorics are often used to define the size of the sample space and event spaces in discrete probability.
    - **[Set](../../../foundations_of_mathematics/set_theory/set.md)**: The objects being counted are elements of sets.
    - **Pascal's Triangle**: A triangular array of the binomial coefficients.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Permutation](https://en.wikipedia.org/wiki/Permutation), [https://en.wikipedia.org/wiki/Combination](https://en.wikipedia.org/wiki/Combination)
