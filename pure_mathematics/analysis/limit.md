# Limit (Calculus)

- **Mathematical Definition**: In calculus, the limit of a function is the value that the function "approaches" as the input "approaches" some value. The formal definition, known as the **(ε, δ)-definition**, is as follows:
  Let $f$ be a function defined on a subset $D \subseteq \mathbb{R}$, and let $c$ be a limit point of $D$. The limit of $f(x)$ as $x$ approaches $c$ is $L$, written
$$ \lim_{x \to c} f(x) = L $$
  if for every $\epsilon > 0$, there exists a $\delta > 0$ such that for all $x \in D$, if $0 < |x - c| < \delta$, then $|f(x) - L| < \epsilon$.

- **Description**: The concept of a limit is the foundational idea upon which all of calculus is built. It formalizes the notion of "getting arbitrarily close" to a point. Limits are used to define the two other fundamental concepts of calculus: the derivative (as the limit of the slope of secant lines) and the integral (as the limit of Riemann sums).

- **Subfields it's part of**:
    - [Calculus](https://en.wikipedia.org/wiki/Calculus)
    - [Mathematical Analysis](https://en.wikipedia.org/wiki/Mathematical_analysis)

- **Subfields and concepts it includes**:
    - **(ε, δ)-definition**: The formal, rigorous definition of a limit.
    - **One-Sided Limits**: The limit as the input approaches a point from either the left or the right.
    - **Limits at Infinity**: The value a function approaches as the input grows without bound.
    - **L'Hôpital's Rule**: A method for evaluating limits of indeterminate forms (e.g., 0/0 or ∞/∞).
    - **Continuity**: A function is continuous at a point if the limit at that point exists and is equal to the function's value at that point.

- **Applications**:
    - **Mathematics**: Used to define derivatives and integrals. Essential for studying the behavior of functions and sequences.
    - **Physics and Engineering**: Calculating instantaneous velocity and acceleration, modeling continuous change in physical systems.
    - **Economics**: Used in marginal analysis (e.g., marginal cost, marginal revenue).
    - **Computer Science**: Analyzing the rate of growth of algorithms (as part of Big O notation).

- **More Concrete Variants**:
    - **Limit of a Sequence**: The value that the terms of a sequence tend to.
    - **Limit of a Function of a Real Variable**: The definition described above.

- **More General Variants**:
    - **Limits in Topological Spaces**: The concept of a limit can be generalized to functions between [topological spaces](../topology/topological_space.md) using neighborhoods instead of the $\epsilon-\delta$ definition.
    - **Limits in Category Theory**: The concepts of limits and colimits in [category theory](../../foundations_of_mathematics/category_theory/category.md) are a vast generalization of limits in analysis.

- **Related Concepts**:
    - **Derivative**: Defined as the limit of the average rate of change.
    - **Integral**: Defined as the limit of a sum of areas of rectangles.
    - **[Topological Space](../topology/topological_space.md)**: Provides a general setting for defining limits.
    - **Asymptote**: A line that a curve approaches as it heads towards infinity. The behavior of the function near the asymptote is described by a limit.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Limit_(mathematics)](https://en.wikipedia.org/wiki/Limit_(mathematics))
