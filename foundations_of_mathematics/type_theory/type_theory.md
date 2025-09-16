# Type Theory

- **Mathematical Definition**: Type theory is a formal system, or a class of formalisms, in which every "term" has a "type" and operations are restricted to terms of a certain type. In type theory, types can be seen as propositions and terms as proofs of those propositions. This correspondence is known as the **Curry-Howard correspondence**. For example, a term $f$ of type $A \to B$ is a function that takes a term of type $A$ and produces a term of type $B$. This can be interpreted as a proof that the proposition $A$ implies the proposition $B$.

- **Description**: Type theory is an alternative foundational framework for mathematics to set theory. It was initially developed by Bertrand Russell and Alfred North Whitehead in their *Principia Mathematica* to avoid Russell's paradox. Instead of having a universal collection of "sets", type theory posits a hierarchy of types, where each object belongs to a specific type. This prevents the self-referential paradoxes that arise in naive set theory. Modern type theories, especially Martin-Löf type theory, are used as the basis for proof assistants and have deep connections to computer science.

- **Subfields it's part of**:
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic)
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics)
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science) (Type systems in programming languages)

- **Subfields and concepts it includes**:
    - **Type**: A collection of objects that share a certain property.
    - **Term**: An inhabitant of a type.
    - **Judgement**: A statement in the formal system, such as "$t : A$" (the term $t$ has type $A$).
    - **Curry-Howard Correspondence**: The direct relationship between formal logical systems and computational systems.
    - **Dependent Type**: A type that depends on a value.
    - **Homotopy Type Theory (HoTT)**: A modern branch of type theory that connects it to homotopy theory, providing a new foundation for mathematics.

- **Applications**:
    - **Proof Assistants**: Systems like Coq, Agda, and Lean are based on type theory and are used to formalize mathematical proofs and verify the correctness of software.
    - **Programming Languages**: The type systems of many functional programming languages (like Haskell and ML) are based on ideas from type theory.
    - **Foundations of Mathematics**: Provides an alternative to ZFC set theory.

- **More Concrete Variants**:
    - **Simple Type Theory**: The original form of type theory.
    - **Martin-Löf Type Theory (MLTT)**: An intuitionistic type theory that is the basis for many modern proof assistants.
    - **Calculus of Constructions**: A higher-order typed lambda calculus that is the basis for the Coq proof assistant.

- **More General Variants**:
    - **Homotopy Type Theory**: A generalization that uses ideas from topology to enrich type theory.

- **Related Concepts**:
    - **[Set Theory](../set_theory/set.md)**: Type theory is an alternative foundational system to set theory.
    - **[Propositional Logic](../logic/propositional_logic.md)**: The Curry-Howard correspondence connects types to propositions.
    - **[Category Theory](../category_theory/category.md)**: There are deep connections between type theory and category theory (e.g., cartesian closed categories are the models of simply typed lambda calculus).

- **Wikipedia**: [https://en.wikipedia.org/wiki/Type_theory](https://en.wikipedia.org/wiki/Type_theory)
