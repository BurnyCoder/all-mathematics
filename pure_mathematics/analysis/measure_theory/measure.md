# Measure

- **Mathematical Definition**: In mathematical analysis, a measure on a set is a systematic way to assign a number to each suitable subset of that set, intuitively interpreted as its size. A measure is a function $\mu$ defined on a $\sigma$-algebra $\Sigma$ over a set $X$ that maps to the extended real number line $[0, \infty]$. It must satisfy the following properties:
    1.  **Non-negativity**: For all $E \in \Sigma$, $\mu(E) \geq 0$.
    2.  **Null Empty Set**: $\mu(\emptyset) = 0$.
    3.  **Countable Additivity (or $\sigma$-additivity)**: For any countable sequence of pairwise disjoint sets $E_1, E_2, E_3, \dots$ in $\Sigma$:
        $$ \mu\left(\bigcup_{i=1}^{\infty} E_i\right) = \sum_{i=1}^{\infty} \mu(E_i) $$
    A set $X$, a $\sigma$-algebra $\Sigma$ on $X$, and a measure $\mu$ on $\Sigma$ together form a **measure space** $(X, \Sigma, \mu)$.

- **Description**: Measure theory provides the foundation for the modern theory of integration, probability theory, and ergodic theory. It generalizes the intuitive notions of length, area, and volume to more abstract and irregular sets. The concept of a measure is what allows us to define the integral of a function over a set in a very general way (the Lebesgue integral).

- **Subfields it's part of**:
    - [Mathematical Analysis](https://en.wikipedia.org/wiki/Mathematical_analysis): Measure theory is a central part of real and functional analysis.
    - [Measure Theory](https://en.wikipedia.org/wiki/Measure_(mathematics)): The central object of study.

- **Subfields and concepts it includes**:
    - **$\sigma$-algebra**: The collection of subsets on which the measure is defined.
    - **Measure Space**: The triple $(X, \Sigma, \mu)$ that provides the context for measure-theoretic concepts.
    - **Countable Additivity**: The key property that distinguishes measures from more elementary notions of size and allows for powerful limit theorems.

- **Applications**:
    - **[Probability Theory](../../applied_mathematics/probability_theory/probability_space.md)**: A probability measure is a measure with a total measure of 1. A probability space is a measure space.
    - **Lebesgue Integration**: Measure theory is the basis for the Lebesgue integral, which is more powerful and has better convergence properties than the Riemann integral.
    - **Financial Mathematics**: Used in the pricing of financial derivatives.
    - **Quantum Mechanics**: Measures are used to describe the distribution of physical quantities.

- **More Concrete Variants**:
    - **Lebesgue Measure**: The standard way of assigning a length, area, or volume to subsets of Euclidean space.
    - **Counting Measure**: Assigns the number of elements in a set as its measure.
    - **Probability Measure**: A measure where the total measure of the entire space is 1.

- **More General Variants**:
    - **Signed Measure**: A generalization that can take negative values.
    - **Complex Measure**: A generalization that can take complex values.
    - **Vector Measure**: A generalization whose values are in a Banach space.

- **Related Concepts**:
    - **[Integral](../integral.md)**: The Lebesgue integral is defined using measures.
    - **[Set Theory](../../foundations_of_mathematics/set_theory/set.md)**: Measure theory is built upon the foundations of set theory.
    - **[Function](../algebra/function.md)**: Measurable functions are the functions that can be integrated in this context.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Measure_(mathematics)](https://en.wikipedia.org/wiki/Measure_(mathematics))
