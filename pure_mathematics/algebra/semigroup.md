# Semigroup

- **Mathematical Definition**: A semigroup is a set $S$ equipped with a binary operation $\cdot: S \times S \to S$ that satisfies the **associativity** axiom:
    - For all $a, b, c \in S$, $(a \cdot b) \cdot c = a \cdot (b \cdot c)$.

- **Description**: A semigroup is one of the simplest algebraic structures. It is a set with a binary operation that is associative. Unlike a group or a monoid, a semigroup is not required to have an identity element or inverse elements. This makes it a very general concept, capturing the essence of associative operations found in many contexts.

- **Subfields it's part of**:
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra): Semigroup theory is a branch of abstract algebra.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science): Semigroups are foundational in automata theory and formal languages.

- **Subfields and concepts it includes**:
    - **Subsemigroup**: A subset of a semigroup that is closed under the semigroup operation.
    - **Semigroup Homomorphism**: A function between two semigroups that preserves the semigroup operation.
    - **Ideal**: A special type of subsemigroup that absorbs multiplication from the larger semigroup.
    - **Green's relations**: A set of five equivalence relations that are fundamental to the structural analysis of semigroups.

- **Applications**:
    - **Computer Science**:
        - **Automata Theory**: The set of states of an automaton can be given a semigroup structure, where the operation is the composition of state transitions.
        - **Formal Languages**: The set of non-empty strings over an alphabet forms a semigroup under concatenation.
        - **Concurrency Theory**: Semigroups are used to model concurrent processes.
    - **Probability Theory**: The convolution of probability distributions is an associative operation, giving rise to semigroup structures.
    - **Partial Differential Equations**: Semigroups are used to study the evolution of systems described by PDEs.

- **More Concrete Variants**:
    - **[Monoid](./monoid.md)**: A semigroup with an identity element.
    - **[Group](./group.md)**: A semigroup with an identity element and where every element has an inverse.
    - **Commutative Semigroup**: A semigroup where the binary operation is commutative ($a \cdot b = b \cdot a$). Example: The positive integers under addition.
    - **Free Semigroup**: The semigroup of all non-empty finite strings over a given alphabet.
    - **Transformation Semigroup**: A set of functions from a set to itself, with the operation of function composition.

- **More General Variants**:
    - **[Magma (or Groupoid)](./magma.md)**: A set with a closed binary operation (drops the associativity axiom). Every semigroup is a magma.

- **Related Concepts**:
    - **[Set](../../foundations_of_mathematics/set_theory/set.md)**: A semigroup is a set with additional structure.
    - **Associativity**: This is the defining property of a semigroup.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Semigroup](https://en.wikipedia.org/wiki/Semigroup)
