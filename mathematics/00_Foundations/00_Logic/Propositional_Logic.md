# Propositional Logic

## Mathematical Definition

**Propositional logic** (also known as propositional calculus or sentential calculus) is the branch of logic that studies ways of joining and/or modifying entire propositions, statements or sentences to form more complicated propositions, statements or sentences, as well as the logical relationships and properties that are derived from these methods of combining or altering statements.

It is based on **propositions**, which are declarative sentences that can be classified as either **true** or **false**.

The fundamental components of propositional logic are:
*   **Propositional Variables:** Symbols representing propositions (e.g., \(P, Q, R\)).
*   **Logical Connectives:** Operators that combine propositions.
    *   **Negation (NOT):** \(\neg P\) (It is not the case that P)
    *   **Conjunction (AND):** \(P \land Q\) (P and Q)
    *   **Disjunction (OR):** \(P \lor Q\) (P or Q)
    *   **Implication (IF...THEN):** \(P \to Q\) (If P, then Q)
    *   **Biconditional (IF AND ONLY IF):** \(P \leftrightarrow Q\) (P if and only if Q)
*   **Well-formed formulas (WFFs):** Syntactically correct expressions or formulas built from propositional variables and connectives.

The meaning of these connectives is defined by **truth tables**, which show the truth value of a compound proposition for every possible combination of truth values of its components.

## Description

Propositional logic is the simplest form of formal logic. It provides a framework for analyzing the structure of arguments and determining their validity. It is not concerned with the internal structure of propositions, but only with how they can be combined to form new ones.

## Subfields it's part of

*   [Logic](./)
*   Foundations of Mathematics
*   Computer Science
*   Philosophy

## Subfields and concepts it includes

*   **Truth Tables:** A method for determining the truth value of a logical expression.
*   **Tautology:** A proposition that is true for all possible truth values of its components (e.g., \(P \lor \neg P\)).
*   **Contradiction:** A proposition that is false for all possible truth values (e.g., \(P \land \neg P\)).
*   **Contingency:** A proposition that is neither a tautology nor a contradiction.
*   **Logical Equivalence:** Two propositions are logically equivalent if they have the same truth table (e.g., \(P \to Q\) is equivalent to \(\neg P \lor Q\)).
*   **Inference Rules:** Rules for deriving new true statements from existing ones (e.g., *Modus Ponens*: from \(P \to Q\) and \(P\), you can infer \(Q\)).
*   **Arguments and Validity:** An argument is a sequence of propositions, and it is valid if the conclusion must be true whenever the premises are true.
*   **Soundness and Completeness:** A logical system is **sound** if all its theorems are tautologies, and **complete** if all tautologies are theorems. Propositional logic is both sound and complete.

## Applications

*   **Computer Science:** Designing digital logic circuits, formal verification of software and hardware, artificial intelligence.
*   **Philosophy:** Analyzing philosophical arguments.
*   **Mathematics:** As a foundation for more complex logical systems and for proving theorems.
*   **Linguistics:** Analyzing the structure of language.

## More general variants

*   [First-Order Logic](./First-Order_Logic.md) (Predicate Logic): Extends propositional logic by introducing quantifiers (\(\forall, \exists\)) and predicates.
*   **Modal Logic:** Deals with modalities like possibility and necessity.
*   **Temporal Logic:** Deals with propositions qualified in terms of time.
*   **Intuitionistic Logic:** A constructive logic where the law of excluded middle (\(P \lor \neg P\)) does not hold.

## More concrete variants

*   **Boolean Algebra:** An algebraic structure that is isomorphic to propositional logic.

## Everything else it relates to

*   **Set Theory:** The operations of union and intersection in set theory are analogous to the logical connectives of disjunction and conjunction.
*   **Digital Circuits:** The behavior of logic gates (AND, OR, NOT) directly corresponds to the logical connectives.
*   **Computability Theory:** The Entscheidungsproblem (decision problem) for propositional logic is decidable, meaning there is an algorithm to determine if any given proposition is a tautology.
