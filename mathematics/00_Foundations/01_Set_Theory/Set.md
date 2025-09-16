# Set

## Mathematical Definition

A **set** is a well-defined collection of distinct objects, which are called its **elements** or **members**. The elements of a set can be any kind of mathematical object: numbers, symbols, points in space, lines, other geometrical shapes, variables, or even other sets. A set is usually denoted by a capital letter, such as \(A\), \(B\), or \(C\).

There are two common ways to describe, or specify the members of, a set: roster notation and set-builder notation.

*   **Roster Notation:** This involves writing the elements of the set between curly braces \(\{\}\), separated by commas.
    *   Example: \(A = \{1, 2, 3, 4\}\)
    *   Example: \(B = \{\text{red}, \text{white}, \text{blue}\}\)
*   **Set-Builder Notation:** This is a notation for describing a set by stating the properties that its members must satisfy.
    *   Example: \(C = \{x \mid x \text{ is a natural number and } x < 5\}\). This reads as "C is the set of all x such that x is a natural number and x is less than 5". This is equivalent to the set \(A\) above.

The fundamental relationship between an object and a set is **membership**. If an object \(x\) is a member of a set \(A\), we write \(x \in A\). If \(x\) is not a member of \(A\), we write \(x \notin A\).

Modern mathematics is built on the foundation of **axiomatic set theory**, most commonly the Zermelo-Fraenkel axioms with the axiom of choice (ZFC).

## Description

A set is an unordered collection of unique items. The concept of a set is one of the most fundamental in mathematics. The study of sets and their properties is the object of set theory.

## Subfields it's part of

*   [Set Theory](../../../00_Foundations/01_Set_Theory)
*   Foundations of Mathematics
*   Logic
*   Virtually all fields of mathematics.

## Subfields and concepts it includes

*   **Element/Member:** An object belonging to a set.
*   **Subset and Superset:** A set \(A\) is a **subset** of a set \(B\), denoted \(A \subseteq B\), if every element of \(A\) is also an element of \(B\). \(B\) is then a **superset** of \(A\), denoted \(B \supseteq A\).
*   **Proper Subset:** If \(A \subseteq B\) and \(A \neq B\), then \(A\) is a **proper subset** of \(B\), written \(A \subset B\).
*   **Empty Set:** The unique set with no elements, denoted by \(\emptyset\) or \(\{\}\).
*   **Power Set:** The set of all subsets of a set \(A\), denoted \(P(A)\) or \(2^A\).
*   **Cardinality:** The number of elements of a set. The cardinality of \(A\) is denoted \(|A|\) or \(card(A)\).
*   **Set Operations:**
    *   **Union:** \(A \cup B = \{x \mid x \in A \text{ or } x \in B\}\). The set of elements that are in \(A\), or \(B\), or both.
    *   **Intersection:** \(A \cap B = \{x \mid x \in A \text{ and } x \in B\}\). The set of elements that are in both \(A\) and \(B\).
    *   **Difference:** \(A \setminus B = \{x \mid x \in A \text{ and } x \notin B\}\). The set of elements that are in \(A\) but not in \(B\).
    *   **Symmetric Difference:** \(A \Delta B = (A \setminus B) \cup (B \setminus A)\). The set of elements in either of the sets, but not in their intersection.
    *   **Cartesian Product:** \(A \times B = \{(a, b) \mid a \in A \text{ and } b \in B\}\). The set of all ordered pairs where the first element is from \(A\) and the second from \(B\).

## Applications

*   **Defining Mathematical Structures:** Most mathematical structures, such as [groups](../.../01_Algebra/00_Group_Theory/Group.md), rings, fields, vector spaces, and topological spaces, are defined as sets with certain properties (axioms).
*   **Computer Science:** Used to model data. Relational databases are based on the relational model, which uses sets. Hash sets are a common data structure.
*   **Defining Numbers:** Standard constructions of number systems, like the [Natural Numbers](../02_Number_Systems/Natural_Numbers.md), are based on sets (e.g., von Neumann ordinals).
*   **Probability Theory:** The sample space in a probability experiment is a set of all possible outcomes. Events are subsets of the sample space.
*   **Logic and Formal Systems:** Used in the semantics of formal languages.

## More general variants

*   **Class:** In set theory, a collection of sets that can be defined by a property shared by its members. A class that is not a set is a **proper class**.
*   **Multiset (or Bag):** A generalization of a set that allows for multiple instances of its elements.
*   **Fuzzy Set:** A generalization of a set whose elements have degrees of membership.
*   **Category:** In category theory, a collection of "objects" and "morphisms" between them. The objects can be seen as a generalization of sets.

## More concrete variants

*   **Finite Set:** A set with a finite number of elements.
*   **Infinite Set:** A set that is not finite.
    *   **Countably Infinite Set:** An infinite set that can be put into one-to-one correspondence with the natural numbers.
    *   **Uncountably Infinite Set:** An infinite set that cannot be put into one-to-one correspondence with the natural numbers.
*   **Specific sets of numbers:**
    *   \(\mathbb{N}\): The set of [Natural Numbers](../02_Number_Systems/Natural_Numbers.md).
    *   \(\mathbb{Z}\): The set of [Integers](../02_Number_Systems/Integers.md).
    *   \(\mathbb{Q}\): The set of [Rational Numbers](../02_Number_Systems/Rational_Numbers.md).
    *   \(\mathbb{R}\): The set of [Real Numbers](../02_Number_Systems/Real_Numbers.md).
    *   \(\mathbb{C}\): The set of [Complex Numbers](../02_Number_Systems/Complex_Numbers.md).
*   **Singleton Set:** A set with exactly one element.

## Everything else it relates to

*   **Relations and Functions:** A binary relation between two sets \(A\) and \(B\) is a subset of \(A \times B\). A [function](./Function.md) from \(A\) to \(B\) is a specific kind of relation.
*   **Paradoxes:** Naive set theory led to paradoxes, such as Russell's paradox, which necessitated the development of axiomatic set theory.
*   **Infinity:** Set theory provides a rigorous framework for studying the concept of infinity and different sizes of infinite sets.
*   **Combinatorics:** Often involves counting the number of elements in sets or forming subsets with specific properties.
