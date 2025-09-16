# First-Order Logic

## Mathematical Definition

**First-order logic** (also known as predicate logic, quantificational logic, and first-order predicate calculus) is a collection of formal systems used in mathematics, philosophy, linguistics, and computer science. It extends **propositional logic** by allowing quantification over variables.

While propositional logic deals with simple declarative propositions, first-order logic additionally covers predicates and quantification.
*   **Predicates:** Properties or relations among objects. A predicate can be thought of as a function that returns a truth value. For example, "is a prime number" is a predicate, and \(P(x)\) could stand for "x is a prime number".
*   **Variables:** Symbols that represent objects in a certain domain (e.g., \(x, y, z\)).
*   **Quantifiers:** Symbols that specify the quantity of elements in the domain that have a certain property.
    *   **Universal Quantifier (\(\forall\)):** "For all" or "Given any". For example, \(\forall x, P(x)\) means "for all x, P(x) is true".
    *   **Existential Quantifier (\(\exists\)):** "There exists". For example, \(\exists x, P(x)\) means "there exists at least one x for which P(x) is true".
*   **Constants:** Symbols that represent specific objects in the domain.
*   **Functions:** Symbols that map objects to other objects.

A **structure** or **model** in first-order logic consists of a non-empty set (the **domain of discourse**) and an interpretation of the constants, functions, and predicates.

## Description

First-order logic is a much more expressive system than propositional logic. It allows us to reason about objects and their properties and relations. It is the standard formal logic for mathematics and is powerful enough to formalize almost all of mathematics.

## Subfields it's part of

*   [Logic](./)
*   Foundations of Mathematics
*   Model Theory
*   Proof Theory
*   Computer Science (especially Automated Theorem Proving)

## Subfields and concepts it includes

*   **Terms:** Variables, constants, or functions applied to terms.
*   **Atomic Formulas:** A predicate symbol applied to a sequence of terms.
*   **Formulas:** Built from atomic formulas using logical connectives and quantifiers.
*   **Free and Bound Variables:** A variable is bound if it is within the scope of a quantifier. Otherwise, it is free.
*   **Theories:** A set of sentences (formulas with no free variables) in a particular first-order language.
*   **Gödel's Completeness Theorem:** States that a sentence is logically valid if and only if it can be proved from the axioms of the system.
*   **Gödel's Incompleteness Theorems:** Show that any sufficiently strong, consistent formal system (like Peano arithmetic) is necessarily incomplete, meaning there are true statements about the natural numbers that cannot be proved within the system.
*   **Löwenheim–Skolem Theorem:** A key result in model theory that states if a countable first-order theory has an infinite model, then for every infinite cardinal number \(\kappa\), it has a model of size \(\kappa\).

## Applications

*   **Formalizing Mathematics:** Used to formalize theories like set theory (ZFC) and Peano arithmetic.
*   **Computer Science:** Artificial intelligence, database theory (SQL is a form of first-order logic), program verification, and automated theorem proving.
*   **Philosophy:** Used in metaphysics and the philosophy of language.
*   **Linguistics:** Formalizing the semantics of natural language.

## More general variants

*   **Second-Order Logic:** Extends first-order logic by allowing quantification over predicates and functions.
*   **Higher-Order Logic:** Allows quantification over sets of predicates, etc.
*   **Infinitary Logic:** Allows for infinitely long sentences and proofs.
*   **Many-Sorted Logic:** Allows variables to have different "sorts" or "types".

## More concrete variants

*   **Propositional Logic:** Can be seen as a fragment of first-order logic where there are no variables or quantifiers.
*   **Monadic Predicate Calculus:** A fragment of first-order logic where predicates have only one argument.

## Everything else it relates to

*   **Set Theory (ZFC):** The standard axiomatic foundation for mathematics is a first-order theory.
*   **Computability Theory:** The Entscheidungsproblem for first-order logic is undecidable; there is no algorithm that can determine whether an arbitrary first-order sentence is valid. This was proven by Church and Turing.
*   **Model Theory:** The study of the relationship between formal theories and their models.
