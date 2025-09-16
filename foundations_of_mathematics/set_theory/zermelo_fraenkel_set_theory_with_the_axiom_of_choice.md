# Zermelo–Fraenkel Set Theory with the Axiom of Choice (ZFC)

- **Mathematical Definition**: ZFC is the standard axiomatic system in set theory, forming the most common foundation of modern mathematics. It is a first-order theory whose objects of discourse are sets. ZFC is an abbreviation for Zermelo–Fraenkel set theory combined with the Axiom of Choice. The theory consists of nine or ten axioms (depending on the formulation) that describe the properties of sets. These axioms are:
    1.  **Axiom of Extensionality**: Two sets are equal if they have the same members.
    2.  **Axiom of Regularity (or Foundation)**: Every non-empty set $A$ contains an element $x$ such that $A$ and $x$ are disjoint sets. This prevents sets from containing themselves and forbids infinite descending membership chains.
    3.  **Axiom Schema of Specification (or Separation)**: For any set $A$ and any property $P$, there is a subset of $A$ containing precisely those elements $x$ in $A$ that satisfy $P$.
    4.  **Axiom of Pairing**: For any two sets, there exists a set that contains exactly those two sets.
    5.  **Axiom of Union**: For any set of sets, there exists a set containing all the elements that are in at least one of the sets in the original set.
    6.  **Axiom Schema of Replacement**: For any set $A$ and any function $f$, the image of $A$ under $f$ is also a set.
    7.  **Axiom of Infinity**: There exists a set $X$ such that $\emptyset$ is in $X$ and whenever $y$ is in $X$, so is $y \cup \{y\}$. This asserts the existence of at least one infinite set.
    8.  **Axiom of Power Set**: For any set, its power set (the set of all its subsets) exists.
    9.  **Axiom of Choice**: For any collection of non-empty sets, it is possible to make a selection of exactly one element from each set.

- **Description**: ZFC was developed to provide a rigorous and paradox-free foundation for mathematics, avoiding issues like [Russell's Paradox](https://en.wikipedia.org/wiki/Russell%27s_paradox) that arose in naive set theory. It is powerful enough to construct nearly all the objects and prove nearly all the theorems in contemporary mathematics.

- **Subfields it's part of**:
    - [Set Theory](https://en.wikipedia.org/wiki/Set_theory): ZFC is the standard axiomatic framework for modern set theory.
    - [Axiomatic Set Theory](https://en.wikipedia.org/wiki/Axiomatic_set_theory): It is the canonical example of an axiomatic set theory, designed to avoid the paradoxes of naive set theory.
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics): It serves as the most common foundation for the entirety of modern mathematics.

- **Subfields and concepts it includes**:
    - All the axioms listed above.
    - **Construction of the Natural Numbers**: The axioms allow for the formal construction of the natural numbers and other number systems.
    - **Ordinal and Cardinal Numbers**: Transfinite numbers are defined and studied within ZFC.

- **Applications**:
    - **Mathematics**: It is the de facto standard foundation for almost all of modern mathematics.
    - **Metamathematics**: The consistency and independence of its axioms (e.g., the Continuum Hypothesis) are major topics of study.

- **More Concrete Variants**:
    - **ZF**: Zermelo-Fraenkel set theory without the Axiom of Choice.

- **More General Variants**:
    - **Von Neumann–Bernays–Gödel set theory (NBG)**: A conservative extension of ZFC that allows for classes as well as sets.
    - **Morse–Kelley set theory (MK)**: A stronger extension of ZFC than NBG.

- **Related Concepts**:
    - **[Set](./set.md)**: ZFC is the axiomatic theory of sets.
    - **[First-Order Logic](../logic/first_order_logic.md)**: ZFC is formulated as a theory in first-order logic.
    - **[Gödel's Incompleteness Theorems](../logic/godels_incompleteness_theorems.md)**: These theorems imply that if ZFC is consistent, then its consistency cannot be proven within ZFC itself.
    - **Continuum Hypothesis**: A famous statement in set theory that is independent of ZFC (it can neither be proved nor disproved from the axioms).

- **Wikipedia**: [https://en.wikipedia.org/wiki/Zermelo%E2%80%93Fraenkel_set_theory](https://en.wikipedia.org/wiki/Zermelo%E2%80%93Fraenkel_set_theory)
