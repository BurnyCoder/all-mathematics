# Limit

## Mathematical Definition

In mathematics, a **limit** is the value that a [function](../../../../00_Foundations/01_Set_Theory/Function.md) or sequence "approaches" as the input or index approaches some value. Limits are essential to calculus and mathematical analysis and are used to define continuity, derivatives, and integrals.

### Limit of a Function

The limit of a function \(f(x)\) as \(x\) approaches a value \(c\) is denoted as:
\[ \lim_{x \to c} f(x) = L \]
This means that the value of \(f(x)\) can be made arbitrarily close to \(L\) by making \(x\) sufficiently close to \(c\).

The formal definition, known as the **(ε, δ)-definition**, is as follows:
For every real number \(\varepsilon > 0\), there exists a real number \(\delta > 0\) such that for all \(x\) in the domain of \(f\), if \(0 < |x - c| < \delta\), then \(|f(x) - L| < \varepsilon\).

### Limit of a Sequence

The limit of a sequence \((a_n)\) is denoted as:
\[ \lim_{n \to \infty} a_n = L \]
This means that the terms of the sequence get arbitrarily close to \(L\) as \(n\) becomes very large.

The formal definition is:
For every real number \(\varepsilon > 0\), there exists a natural number \(N\) such that for all \(n > N\), \(|a_n - L| < \varepsilon\).

## Description

The concept of a limit captures the idea of "getting closer and closer" to a certain value without necessarily reaching it. It is the fundamental building block of calculus, allowing us to study the behavior of functions at a point and the instantaneous rate of change.

## Subfields it's part of

*   [Calculus](./)
*   [Real Analysis](../01_Real_Analysis/)
*   [Mathematical Analysis](../)
*   [Topology](../../../04_Topology/)

## Subfields and concepts it includes

*   **One-Sided Limits:** The limit of a function as it approaches a point from either the left or the right.
*   **Limits at Infinity:** The value a function approaches as its input grows or shrinks without bound.
*   **Infinite Limits:** A situation where the value of a function grows or shrinks without bound as it approaches a certain point.
*   **L'Hôpital's Rule:** A method for evaluating limits of indeterminate forms like 0/0 or ∞/∞.
*   **Squeeze Theorem:** A theorem used to confirm the limit of a function by comparing it with two other functions whose limits are known.
*   **Limit Laws:** Rules for finding the limit of the sum, difference, product, and quotient of functions.

## Applications

*   **Derivatives:** The derivative of a function at a point is defined as the limit of the average rate of change. It represents the instantaneous rate of change.
*   **Integrals:** The definite integral is defined as the limit of Riemann sums. It represents the accumulated area under a curve.
*   **Continuity:** A function is continuous at a point if the limit of the function at that point exists and is equal to the function's value at that point.
*   **Asymptotes:** Limits are used to define the vertical and horizontal asymptotes of a function's graph.
*   **Series:** The sum of an infinite series is defined as the limit of its sequence of partial sums.
*   **Physics:** Used to describe instantaneous velocity and acceleration.
*   **Economics:** Used in marginal analysis (e.g., marginal cost, marginal revenue).

## More general variants

*   **Limit in a Metric Space:** The (ε, δ)-definition can be generalized to functions between metric spaces.
*   **Limit in a Topological Space:** The concept of a limit can be defined in even more general topological spaces using the idea of nets or filters.
*   **Categorical Limit:** In category theory, the limit is a very general construction that includes many other mathematical concepts as special cases.

## More concrete variants

*   **Limit of a Sequence of Numbers**
*   **Limit of a Function of a Real Variable**

## Everything else it relates to

*   **Real Numbers:** The completeness of the real numbers is what guarantees that every Cauchy sequence of real numbers has a limit.
*   **Zeno's Paradoxes:** These ancient paradoxes about motion, such as Achilles and the Tortoise, touch upon the idea of limits and infinite processes.
*   **Infinity:** The concept of a limit provides a rigorous way to handle processes that involve infinity.
*   **Continuum:** The notion of a continuous function, which is central to topology and analysis, is defined in terms of limits.
