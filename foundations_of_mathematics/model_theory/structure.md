# Structure (Model Theory)

- **Mathematical Definition**: In model theory, a structure (or model) for a formal language \\(\mathcal{L}\\) is an interpretation of that language. It consists of a non-empty set \\(M\\), called the **domain** or **universe**, and an interpretation function \\(I\\) that assigns meaning to the non-logical symbols of \\(\mathcal{L}\\). Specifically:
    - To each constant symbol \\(c\\) of \\(\mathcal{L}\\), \\(I\\) assigns an element \\(c^M \in M\\).
    - To each \\(n\\)-ary function symbol \\(f\\) of \\(\mathcal{L}\\), \\(I\\) assigns an \\(n\\)-ary function \\(f^M: M^n \to M\\).
    - To each \\(n\\)-ary predicate symbol \\(P\\) of \\(\mathcal{L}\\), \\(I\\) assigns an \\(n\\)-ary relation \\(P^M \subseteq M^n\\).
A sentence \\(\phi\\) in the language \\(\mathcal{L}\\) is said to be **true in the structure** \\(\mathcal{M}\\) (written \\(\mathcal{M} \models \phi\\)) if the interpretation satisfies the sentence.

- **Description**: A structure is a concrete mathematical object that realizes the abstract syntax of a formal language. Model theory is the study of the relationship between formal theories (sets of sentences in a formal language) and their models (the structures in which those sentences are true). It provides a way to study formal systems by looking at the mathematical objects they describe. For example, the set of natural numbers with the operations of addition and multiplication is a model of the theory of Peano Arithmetic.

- **Subfields it's part of**:
    - [Model Theory](https://en.wikipedia.org/wiki/Model_theory)
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic)
    - [Universal Algebra](https://en.wikipedia.org/wiki/Universal_algebra)

- **Subfields and concepts it includes**:
    - **Formal Language**: The syntax for which a structure provides semantics.
    - **Theory**: A set of sentences. A model of a theory is a structure in which all sentences of the theory are true.
    - **Satisfiability**: A theory is satisfiable if it has at least one model.
    - **Compactness Theorem**: A fundamental theorem stating that a set of first-order sentences has a model if and only if every finite subset has a model.
    - **Löwenheim–Skolem Theorem**: A theorem about the cardinality of models.

- **Applications**:
    - **Algebra**: Proving results about algebraic structures like groups and fields. For example, the Ax-Grothendieck theorem can be proven using model-theoretic arguments.
    - **Algebraic Geometry**: Model theory has been applied to study Diophantine geometry.
    - **Computer Science**: Used in database theory, formal verification, and the study of programming language semantics.

- **More Concrete Variants (Examples of Structures)**:
    - **Groups**: A group is a model for the language of group theory.
    - **Rings**: A ring is a model for the language of ring theory.
    - **The Natural Numbers \\((\mathbb{N}, +, \cdot, 0, 1)\\)**: This is the intended model for the language of Peano Arithmetic.

- **More General Variants**:
    - **Categorical Model Theory**: Explores the relationship between model theory and category theory.

- **Related Concepts**:
    - **[First-Order Logic](../logic/first_order_logic.md)**: Model theory is primarily concerned with the models of first-order logic.
    - **[ZFC Set Theory](../set_theory/zfc.md)**: Any universe of sets that satisfies the axioms of ZFC is a model of ZFC.
    - **Proof Theory**: The other main branch of mathematical logic, which studies formal proofs, whereas model theory studies truth in mathematical structures.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Structure_(mathematical_logic)](https://en.wikipedia.org/wiki/Structure_(mathematical_logic))
