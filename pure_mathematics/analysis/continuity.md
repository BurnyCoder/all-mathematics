# Continuity

- **Mathematical Definition**: In mathematics, a continuous function is a function for which, intuitively, "small" changes in the input result in "small" changes in the output.

    - **Epsilon-Delta Definition**: A function $f: D \to \mathbb{R}$ (where $D \subseteq \mathbb{R}$) is continuous at a point $c \in D$ if for every number $\epsilon > 0$, there exists a number $\delta > 0$ such that for all $x \in D$, if $|x-c| < \delta$, then $|f(x)-f(c)| < \epsilon$.
    
    - **Sequential Definition**: A function $f$ is continuous at $c$ if for every sequence $(x_n)$ in $D$ that converges to $c$, the sequence $(f(x_n))$ converges to $f(c)$.

    - **Topological Definition**: A function $f: X \to Y$ between two topological spaces is continuous if for every open set $V$ in $Y$, the preimage $f^{-1}(V)$ is an open set in $X$.

- **Description**: Continuity is a central concept in topology and analysis. It formalizes the intuitive idea of a function having no "jumps," "holes," or "breaks." The epsilon-delta definition precisely captures the idea of keeping the output of a function within a certain tolerance by restricting its input to a small enough neighborhood. The topological definition is the most general and abstract.

- **Subfields it's part of**:
    - [Real Analysis](https://en.wikipedia.org/wiki/Real_analysis): A fundamental property of functions of real variables.
    - [Complex Analysis](https://en.wikipedia.org/wiki/Complex_analysis): Holomorphic functions are a special class of continuous functions.
    - [Topology](https://en.wikipedia.org/wiki/Topology): Continuity is a central concept, defined in terms of open sets, that generalizes the concept from analysis.
    - [Functional Analysis](https://en.wikipedia.org/wiki/Functional_analysis): Studies continuous linear operators on function spaces.

- **Subfields and concepts it includes**:
    - **Uniform Continuity**: A stronger form of continuity where the choice of $\delta$ does not depend on the point $c$.
    - **Lipschitz Continuity**: An even stronger form of continuity that bounds the rate at which the function's output can change.
    - **Differentiability**: A differentiable function is always continuous, but the converse is not true (e.g., the Weierstrass function).
    - **Homeomorphism**: A continuous function between topological spaces that has a continuous inverse function.

- **Applications**:
    - **Physics**: Physical processes are almost always modeled by continuous functions, as physical quantities (like position, velocity, energy) are assumed to change continuously over time.
    - **Engineering**: Control systems, signal processing, and numerical simulations all rely on the properties of continuous functions.
    - **Economics**: Many economic models assume continuity of utility functions and production functions.
    - **Computer Graphics**: Used for smooth rendering of curves and surfaces.

- **More Concrete Variants**:
    - **Polynomial functions**: Continuous everywhere.
    - **Trigonometric functions (sin, cos)**: Continuous everywhere.
    - **Exponential and Logarithmic functions**: Continuous on their domains.

- **More General Variants**:
    - **Semicontinuity**: A weaker form of continuity from either above or below.
    - **Continuity in Metric Spaces**: The epsilon-delta definition can be generalized to functions between any two metric spaces.

- **Related Concepts**:
    - **[Limit](./limit.md)**: The definition of continuity is based on the concept of a limit. A function $f$ is continuous at $c$ if $\lim_{x \to c} f(x) = f(c)$.
    - **[Topological Space](../topology/topological_space.md)**: The most general setting for defining continuity.
    - **[Derivative](./derivative.md)**: Differentiability implies continuity.
    - **[Integral](./integral.md)**: The integral of a function is a "smoother," more continuous version of the function. The Fundamental Theorem of Calculus connects differentiation and integration.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Continuous_function](https://en.wikipedia.org/wiki/Continuous_function)
