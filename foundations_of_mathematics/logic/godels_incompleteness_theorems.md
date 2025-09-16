# Gödel's Incompleteness Theorems

- **Mathematical Definition**: Gödel's incompleteness theorems are two theorems of mathematical logic that demonstrate the inherent limitations of every formal axiomatic system capable of modeling basic arithmetic.
    1.  **First Incompleteness Theorem**: Any consistent formal system $F$ within which a certain amount of elementary arithmetic can be carried out is **incomplete**; i.e., there are statements of the language of $F$ which can neither be proved nor disproved in $F$.
    2.  **Second Incompleteness Theorem**: For any consistent formal system $F$ containing basic arithmetic, the consistency of $F$ cannot be proved within $F$ itself.

- **Description**: Proved by Kurt Gödel in 1931, these theorems were a landmark in 20th-century mathematics. They showed that the ambition of finding a complete and consistent set of axioms for all of mathematics (known as Hilbert's program) was impossible. The first theorem states that in any sufficiently powerful axiomatic system, there will always be true statements that are unprovable. The second theorem states that such a system cannot prove its own consistency.

- **Subfields it's part of**:
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic): These are landmark theorems in mathematical logic, specifically in the area of metamathematics.
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics): The theorems revealed fundamental limitations of the axiomatic method and had a profound impact on the philosophy of mathematics.

- **Subfields and concepts it includes**:
    - **Formal System**: An axiomatic system consisting of a language, a set of axioms, and a set of inference rules.
    - **Consistency**: A property of a formal system, meaning that it does not contain any contradictions.
    - **Completeness**: A property of a formal system, meaning that for any statement in the language, either the statement or its negation can be proven.
    - **Gödel Numbering**: A technique used in the proof to assign a unique natural number to every statement and proof in the formal system, thereby turning questions about logic into questions about number theory.

- **Applications**:
    - **Philosophy of Mathematics**: The theorems had a profound impact on the philosophy of mathematics, challenging the Platonist and formalist views.
    - **Computer Science**: The theorems are closely related to the **Halting Problem** in computability theory. They imply that there can be no algorithm that can determine the truth or falsity of all mathematical statements.
    - **Logic**: The theorems are a central result in metamathematics.

- **More Concrete Variants**:
    - The theorems apply to specific formal systems like **Peano Arithmetic** and **ZFC set theory**. For these systems, it is known that there are specific true statements (like the consistency of the system itself) that cannot be proven within the system.

- **More General Variants**:
    - The theorems apply to any formal system that is powerful enough to express the basic axioms of arithmetic.

- **Related Concepts**:
    - **[Turing Machine](../computability_theory/turing_machine.md)**: The undecidability of the Halting Problem is the computational equivalent of the First Incompleteness Theorem.
    - **[First-Order Logic](./first_order_logic.md)**: The theorems apply to formal systems based on first-order logic.
    - **Axiomatic System**: The object of study of the theorems.

- **Wikipedia**: [https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems](https://en.wikipedia.org/wiki/G%C3%B6del%27s_incompleteness_theorems)
