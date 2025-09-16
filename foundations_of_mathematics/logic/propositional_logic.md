# Propositional Logic

- **Mathematical Definition**: Propositional logic, also known as propositional calculus or sentential calculus, is a branch of logic that studies propositions and the relationships between them. A proposition is a statement that can be either true or false. These propositions are connected using logical connectives. The syntax involves propositional variables (e.g., $P, Q$) and logical connectives (e.g., $\land, \lor, \neg, \to, \leftrightarrow$). For example, $ P \land Q $ represents "P and Q". The semantics are given by truth assignments and evaluated using truth tables.

- **Description**: It is the simplest form of formal logic and provides a foundation for more expressive logics like first-order logic. It deals with the logical relationships between propositions at a wholesale level, without analyzing the internal structure of the propositions themselves.

- **Subfields it's part of**:
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic)
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics)

- **Subfields and concepts it includes**:
    - **Proposition**: A declarative sentence that is either true or false.
    - **Logical Connectives**:
        - **Conjunction (AND, $\land$)**: True only if both propositions are true.
        - **Disjunction (OR, $\lor$)**: True if at least one proposition is true.
        - **Negation (NOT, $\neg$)**: Reverses the truth value of a proposition.
        - **Material Conditional (IMPLIES, $\to$)**: False only when the first proposition is true and the second is false.
        - **Biconditional (IFF, $\leftrightarrow$)**: True only if both propositions have the same truth value.
    - **Truth Table**: A mathematical table used to determine the truth value of a compound proposition.
    - **Logical Equivalence**: Two statements are logically equivalent if they have the same truth table.
    - **Tautology**: A proposition that is true for every possible truth assignment.
    - **Contradiction**: A proposition that is false for every possible truth assignment.
    - **Satisfiability**: A proposition is satisfiable if there is at least one truth assignment that makes it true.
    - **Deductive Systems**: Systems of formal proofs, like natural deduction or Hilbert systems, for deriving theorems from axioms.

- **Applications**:
    - **Computer Science**:
        - **Digital Circuit Design**: Logic gates (AND, OR, NOT) are direct implementations of logical connectives.
        - **Programming**: Boolean logic is fundamental to control flow (if-statements, while loops).
        - **Artificial Intelligence**: Used in automated reasoning and knowledge representation.
        - **Formal Verification**: Proving the correctness of software and hardware.
    - **Philosophy**: Analyzing arguments and in formal epistemology.
    - **Linguistics**: Modeling the logical structure of natural language.

- **More Concrete Variants**:
    - Specific axiomatic systems for propositional calculus, such as Hilbert-style systems or systems of natural deduction.

- **More General Variants**:
    - **[First-Order Logic (Predicate Logic)](./first_order_logic.md)**: Extends propositional logic by introducing quantifiers ($\forall, \exists$) and predicates.
    - **Higher-Order Logic**: Allows quantification over predicates and functions.
    - **Modal Logic**: Introduces operators for necessity and possibility.
    - **Temporal Logic**: Introduces operators for reasoning about time.
    - **Intuitionistic Logic**: A logic that differs from classical logic in its definition of truth, rejecting the law of the excluded middle.

- **Related Concepts**:
    - **[Boolean Algebra](../pure_mathematics/algebra/boolean_algebra.md)**: The underlying mathematical structure for propositional logic.
    - **[Set Theory](../set_theory/set.md)**: The semantics of propositional logic can be modeled using sets (e.g., the set of models where a formula is true).

- **Wikipedia**: [https://en.wikipedia.org/wiki/Propositional_calculus](https://en.wikipedia.org/wiki/Propositional_calculus)
