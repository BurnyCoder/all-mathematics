# σ-algebra

- **Mathematical Definition**: A σ-algebra (also known as a sigma-field) on a set $X$ is a collection $\Sigma$ of subsets of $X$ that is closed under countable set operations. To be a σ-algebra, $\Sigma$ must satisfy three properties:
    1.  **Contains the whole set**: $X$ is in $\Sigma$.
    2.  **Closed under complementation**: If a set $A$ is in $\Sigma$, then its complement, $X \setminus A$, is also in $\Sigma$.
    3.  **Closed under countable unions**: If $A_1, A_2, A_3, \dots$ is a countable sequence of sets in $\Sigma$, then their union, $\bigcup_{i=1}^{\infty} A_i$, is also in $\Sigma$.
    From these axioms, it follows that a σ-algebra is also closed under countable intersections (by De Morgan's laws). A pair $(X, \Sigma)$ consisting of a set and a σ-algebra on it is called a **measurable space**.

- **Description**: A σ-algebra provides the structural framework for measure theory. It defines which subsets of a given set are considered "measurable"—that is, the sets to which we can assign a size or probability. By requiring closure under countable operations, the σ-algebra ensures that we can perform limiting processes, which is crucial for both integration and probability theory.

- **Subfields it's part of**:
    - [Measure Theory](https://en.wikipedia.org/wiki/Measure_theory): The σ-algebra is the domain on which a measure is defined.
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory): It defines the set of all possible events in a probability space.
    - [Set Theory](https://en.wikipedia.org/wiki/Set_theory): It is a special collection of subsets with specific closure properties.

- **Subfields and concepts it includes**:
    - **Closure under complement**: A key property ensuring that if an event is measurable, the event 'not happening' is also measurable.
    - **Closure under countable unions**: This property is crucial for dealing with limits and infinite sequences of events.

- **Applications**:
    - **[Measure Theory](./measure.md)**: It is the domain of definition for any measure. A measure space is a triple $(X, \Sigma, \mu)$ where $\Sigma$ is a σ-algebra.
    - **[Probability Theory](../../../applied_mathematics/probability_theory/probability_space.md)**: In a probability space, the σ-algebra represents the set of all events for which probabilities can be defined.
    - **Stochastic Processes**: Used to define filtrations, which are sequences of σ-algebras that model the accumulation of information over time.

- **More Concrete Variants**:
    - **Borel σ-algebra**: The smallest σ-algebra on a topological space (like the real numbers) that contains all open sets. This is the standard σ-algebra used in most of analysis and probability.
    - **Power Set**: The collection of all subsets of a set $X$, denoted $\mathcal{P}(X)$, is the largest possible σ-algebra on $X$.
    - **Trivial σ-algebra**: The smallest possible σ-algebra on any set $X$, which is $\{\emptyset, X\}$.

- **More General Variants**:
    - **Algebra of sets**: A collection of subsets closed under finite unions and complementation. Every σ-algebra is an algebra, but not every algebra is a σ-algebra.
    - **$\delta$-ring**: A collection of sets closed under countable intersections and set-theoretic difference.

- **Related Concepts**:
    - **[Measure](./measure.md)**: A measure is a function defined on a σ-algebra.
    - **[Topological Space](../../topology/topological_space.md)**: The Borel σ-algebra provides a fundamental link between topology and measure theory.
    - **[Set](../../../foundations_of_mathematics/set_theory/set.md)**: A σ-algebra is a special collection of subsets of a set.

- **Wikipedia**: [https://en.wikipedia.org/wiki/%CE%A3-algebra](https://en.wikipedia.org/wiki/%CE%A3-algebra)
