# Binomial Coefficient

## Mathematical Definition

The **binomial coefficient**, denoted \(\binom{n}{k}\) (read as "n choose k"), is the number of ways to choose an unordered subset of \(k\) elements from a set of \(n\) distinct elements.

For non-negative integers \(n\) and \(k\), the binomial coefficient is defined by the formula:
\[ \binom{n}{k} = \frac{n!}{k!(n-k)!} \]
where \(n!\) (read "n factorial") is the product of all positive integers up to \(n\). This formula is only valid for \(0 \le k \le n\). If \(k > n\), \(\binom{n}{k} = 0\).

For example, the number of ways to choose 2 elements from a set of 4 elements \(\{A, B, C, D\}\) is:
\[ \binom{4}{2} = \frac{4!}{2!(4-2)!} = \frac{24}{2 \cdot 2} = 6 \]
The six possible subsets are \(\{A, B\}, \{A, C\}, \{A, D\}, \{B, C\}, \{B, D\}, \{C, D\}\).

## Description

Binomial coefficients are fundamental objects in combinatorics. They are called "binomial" because they appear as the coefficients in the expansion of powers of a binomial, such as \((x + y)^n\).

## Subfields it's part of

*   [Combinatorics](./)
*   [Algebra](../../../01_Algebra/)
*   [Probability and Statistics](../../../07_Probability_and_Statistics/)

## Subfields and concepts it includes

*   **Binomial Theorem:** This theorem describes the algebraic expansion of powers of a binomial:
    \[ (x+y)^n = \sum_{k=0}^{n} \binom{n}{k} x^{n-k} y^k \]
*   **Pascal's Triangle:** A triangular array of the binomial coefficients. Each number is the sum of the two directly above it. This is based on **Pascal's identity**:
    \[ \binom{n}{k} = \binom{n-1}{k-1} + \binom{n-1}{k} \]
*   **Combinations:** The selection of items from a collection, such that the order of selection does not matter. The number of combinations of \(k\) items from a set of \(n\) is given by the binomial coefficient.
*   **Factorial:** The product of all positive integers up to a given integer.

## Applications

*   **Probability Theory:** The binomial distribution, which describes the number of successes in a sequence of \(n\) independent experiments, uses binomial coefficients in its probability mass function.
*   **Statistics:** Used in statistical tests and in the definition of various probability distributions.
*   **Computer Science:** In algorithm analysis, particularly for counting the number of possible combinations or arrangements.
*   **Algebra:** In the expansion of binomials.
*   **Genetics:** Calculating the probability of inheriting certain combinations of genes.

## More general variants

*   **Multinomial Coefficient:** A generalization of the binomial coefficient used to find the number of ways to partition a set of \(n\) elements into \(k\) distinct subsets of specified sizes. They are the coefficients in the multinomial expansion.
*   **Gaussian Binomial Coefficient (or q-binomial coefficient):** A q-analog of the binomial coefficient, which counts the number of \(k\)-dimensional subspaces of an \(n\)-dimensional vector space over a finite field of order \(q\).

## More concrete variants

*   \(\binom{n}{0} = 1\) (There is one way to choose zero elements: choose the empty set).
*   \(\binom{n}{1} = n\) (There are n ways to choose one element).
*   \(\binom{n}{n} = 1\) (There is one way to choose all n elements).
*   \(\binom{n}{k} = \binom{n}{n-k}\) (The symmetry identity).

## Everything else it relates to

*   **Set Theory:** The binomial coefficient \(\binom{n}{k}\) is the cardinality of the set of all \(k\)-element subsets of a set with cardinality \(n\).
*   **Gamma Function:** The factorial function can be generalized to non-integer arguments using the Gamma function, which allows for a generalization of the binomial coefficient.
*   **Catalan Numbers:** These are a sequence of natural numbers that occur in various counting problems. They can be expressed using binomial coefficients.
*   **Fibonacci Numbers:** There are identities relating Fibonacci numbers to sums of binomial coefficients.
