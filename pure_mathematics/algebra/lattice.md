# Lattice

- **Mathematical Definition**: A lattice is a partially ordered set $(L, \preceq)$ in which every pair of elements $a, b \in L$ has a unique **supremum** (also called the least upper bound or join, denoted $a \lor b$) and a unique **infimum** (also called the greatest lower bound or meet, denoted $a \land b$).

    An equivalent algebraic definition is a set $L$ with two binary operations, join ($\lor$) and meet ($\land$), that are commutative, associative, and satisfy the absorption laws:
    1.  **Commutative laws**: $a \lor b = b \lor a$ and $a \land b = b \land a$.
    2.  **Associative laws**: $(a \lor b) \lor c = a \lor (b \lor c)$ and $(a \land b) \land c = a \land (b \land c)$.
    3.  **Absorption laws**: $a \lor (a \land b) = a$ and $a \land (a \lor b) = a$.

- **Description**: Lattices are algebraic structures that capture the essence of order. They formalize the idea of having a "least upper bound" and a "greatest lower bound" for any pair of elements. This structure appears in many different areas of mathematics and computer science, from set theory (collections of sets ordered by inclusion) to logic (sentences ordered by implication). The study of lattices and order theory provides a bridge between algebra and order.

- **Subfields it's part of**:
    - [Order Theory](https://en.wikipedia.org/wiki/Order_theory): Lattices are a central object of study in order theory.
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra): Lattices are considered an algebraic structure, studied in lattice theory.
    - [Universal Algebra](https://en.wikipedia.org/wiki/Universal_algebra): Lattices are a fundamental example of an algebraic structure.

- **Subfields and concepts it includes**:
    - **Sublattice**: A subset of a lattice that is itself a lattice with the same meet and join operations.
    - **Lattice Homomorphism**: A function between two lattices that preserves the meet and join operations.
    - **Complete Lattice**: A lattice in which *all* subsets (not just pairs) have a meet and a join.
    - **Distributive Lattice**: A lattice where the meet and join operations distribute over each other.
    - **Modular Lattice**: A lattice satisfying a weaker condition than distributivity.

- **Applications**:
    - **Computer Science**:
        - **Formal Concept Analysis**: Used for data analysis and knowledge representation.
        - **Type Theory**: Lattices are used to model type hierarchies.
        - **Concurrency Theory**: Modeling the state space of concurrent systems.
        - **Boolean Logic**: Boolean algebras are a special kind of lattice.
    - **Set Theory**: The power set of a given set, ordered by inclusion, forms a lattice where join is union and meet is intersection.
    - **Logic**: The set of logical propositions forms a lattice where join is disjunction ($\lor$) and meet is conjunction ($\land$).
    - **Quantum Mechanics**: The lattice of closed subspaces of a Hilbert space is used in the formulation of quantum logic.

- **More Concrete Variants**:
    - **[Boolean Algebra](./boolean_algebra.md)**: A complemented distributive lattice. This is the structure underlying classical propositional logic.
    - **Total Order**: A lattice where for any two elements $a, b$, either $a \preceq b$ or $b \preceq a$.
    - **Heyting Algebra**: A distributive lattice that is the algebraic model for intuitionistic logic.

- **More General Variants**:
    - **Semilattice**: A partially ordered set where only one of the operations (meet or join) is guaranteed to exist for all pairs.
    - **Partially Ordered Set (Poset)**: The underlying structure for a lattice, but not every pair of elements needs to have a meet or join.

- **Related Concepts**:
    - **[Set Theory](../../foundations_of_mathematics/set_theory/set.md)**: The power set of a set is a classic example of a lattice.
    - **[Propositional Logic](../../foundations_of_mathematics/logic/propositional_logic.md)**: Logical connectives form a lattice structure.
    - **[Group](./group.md)**: The set of subgroups of a group forms a complete lattice.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Lattice_(order)](https://en.wikipedia.org/wiki/Lattice_(order))
