# First-Order Logic

- **Mathematical Definition**: First-order logic, also known as predicate logic or first-order predicate calculus, is a formal system that extends [propositional logic](./propositional_logic.md). It introduces variables, predicates, and quantifiers. Its syntax involves:
    - **Terms**: Variables ($x, y, ...$), constants, and functions applied to terms (e.g., $f(x)$).
    - **Predicates**: Relations on terms (e.g., $P(x), Q(x, y)$).
    - **Logical Connectives**: From propositional logic ($\land, \lor, \neg, \to, \leftrightarrow$).
    - **Quantifiers**:
        - **Universal Quantifier ($\forall$)**: "For all" or "for every".
        - **Existential Quantifier ($\exists$)**: "There exists" or "for some".
    An example formula is $ \forall x \exists y \, P(x, y) $, meaning "for every x, there exists a y such that the relation P holds between x and y".

- **Description**: First-order logic is significantly more expressive than propositional logic, allowing for the formalization of vast areas of mathematics. It is the standard logic for axiomatizing mathematical theories. It operates on a domain of discourse, which is a set of objects over which the variables range.

- **Subfields it's part of**:
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic): It is the standard and most widely studied system in mathematical logic.
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics): It is the language used to formalize axiomatic systems like set theory (ZFC) and arithmetic (Peano Arithmetic), which serve as foundations for the rest of mathematics.

- **Subfields and concepts it includes**:
    - **Universe of Discourse**: The set of entities over which quantifiers range.
    - **Predicate**: A symbol that represents a property or a relation among objects in the universe of discourse.
    - **Variable**: A symbol that stands for an object from the universe of discourse.
    - **Quantifier**: A symbol that specifies the quantity of elements for which a predicate is true (e.g., all, some).
    - **Structure (or Model)**: An interpretation of the non-logical symbols of a first-order language, consisting of a universe of discourse and an interpretation for each constant, function, and predicate symbol.
    - **First-Order Theory**: A set of sentences in a first-order language (the axioms).

- **Applications**:
    - **Mathematics**: Used to formalize nearly all of modern mathematics. Axiomatic systems like [Peano Arithmetic](https://en.wikipedia.org/wiki/Peano_axioms) for number theory and [ZFC](./../set_theory/zfc.md) for set theory are formulated in first-order logic.
    - **Computer Science**:
        - **Database Theory**: Relational calculus, the basis for query languages like SQL, is a form of first-order logic.
        - **Artificial Intelligence**: Used for knowledge representation and automated reasoning.
        - **Logic Programming**: Languages like Prolog are based on a subset of first-order logic.
        - **Formal Verification**: Used to specify and prove properties of systems.
    - **Philosophy**: Used extensively in analytic philosophy and the philosophy of mathematics.

- **More Concrete Variants**:
    - **First-order theories for specific domains**:
        - **Peano Arithmetic**: For natural numbers.
        - **Zermelo-Fraenkel Set Theory (ZFC)**: For set theory.
        - **Group Theory**: Axioms for groups.
    - **Monadic First-Order Logic**: A fragment where quantification is only allowed over variables that appear in unary predicates.

- **More General Variants**:
    - **Second-Order Logic**: Extends first-order logic by allowing quantification over predicates and functions.
    - **Higher-Order Logic**: Allows quantification over predicates of predicates, and so on.
    - **Infinitary Logic**: Allows for infinitely long conjunctions, disjunctions, and quantifier sequences.
    - **Modal Logic**: Adds operators for necessity and possibility, which can be combined with first-order logic.

- **Related Concepts**:
    - **[Propositional Logic](./propositional_logic.md)**: The foundation upon which first-order logic is built.
    - **Model Theory**: The study of the relationship between formal theories and their models (structures).
    - **Proof Theory**: The study of formal proofs in various logical deduction systems.
    - **[Set Theory](../set_theory/set.md)**: Often provides the semantic foundation for the models of first-order theories.

- **Wikipedia**: [https://en.wikipedia.org/wiki/First-order_logic](https://en.wikipedia.org/wiki/First-order_logic)
