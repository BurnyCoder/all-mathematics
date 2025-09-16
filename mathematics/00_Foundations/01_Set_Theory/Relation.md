# Relation

## Mathematical Definition

In set theory, a **binary relation** from a [set](./Set.md) \(A\) to a set \(B\) is a subset of the Cartesian product \(A \times B\). In other words, a relation is a set of ordered pairs \((a, b)\) consisting of elements \(a \in A\) and \(b \in B\).

If \((a, b)\) is in a relation \(R\), we write \(aRb\) or \(R(a, b)\) and say that "a is related to b by R".

The set \(A\) is called the **domain** or **set of departure** of the relation, and the set \(B\) is called the **codomain** or **set of destination**.

A relation on a single set \(A\) is a subset of \(A \times A\).

## Description

A relation describes a connection or relationship between elements of sets. The concept is a very general way of expressing connections among objects. A [function](./Function.md) is a special kind of relation where each element in the domain is related to exactly one element in the codomain.

## Subfields it's part of

*   [Set Theory](./)
*   Foundations of Mathematics
*   Graph Theory
*   Order Theory

## Subfields and concepts it includes

Relations on a set \(A\) can have various properties:
*   **Reflexive:** For all \(a \in A\), \(aRa\). (Every element is related to itself).
*   **Symmetric:** If \(aRb\), then \(bRa\). (The relationship is mutual).
*   **Antisymmetric:** If \(aRb\) and \(bRa\), then \(a = b\).
*   **Asymmetric:** If \(aRb\), then not \(bRa\).
*   **Transitive:** If \(aRb\) and \(bRc\), then \(aRc\). (The relationship can be chained).
*   **Total (or Connex):** For all \(a, b \in A\), \(aRb\) or \(bRa\). (Any two elements are related).

Based on these properties, we can define important types of relations:
*   **Equivalence Relation:** A relation that is reflexive, symmetric, and transitive. It partitions a set into **equivalence classes**.
*   **Partial Order:** A relation that is reflexive, antisymmetric, and transitive. It models concepts like "less than or equal to" or "subset of". A set with a partial order is called a **poset**.
*   **Total Order (or Linear Order):** A partial order that is also total. The elements of the set can be thought of as being arranged in a line.

## Applications

*   **Computer Science:** Relational databases are built on the mathematical theory of relations. Directed graphs are a visual representation of relations on a set.
*   **Order Theory:** The study of orders on sets.
*   **Defining Functions:** A function is a relation with specific properties.
*   **Modular Arithmetic:** Congruence modulo n is an equivalence relation on the integers.
*   **Equivalence Classes:** Used throughout mathematics to group together objects that are "the same" in some respect (e.g., in the construction of integers from natural numbers, or rationals from integers).

## More general variants

*   **Finitary Relation:** A relation among \(n\) sets, which is a subset of the Cartesian product \(A_1 \times A_2 \times \cdots \times A_n\).

## More concrete variants

*   The "less than or equal to" relation (\(\le\)) on the real numbers is a total order.
*   The "divides" relation on the natural numbers is a partial order.
*   The relation "is a subset of" (\(\subseteq\)) on a power set is a partial order.
*   Geometric congruence ("is congruent to") is an equivalence relation.

## Everything else it relates to

*   **Cartesian Product:** The foundation for the definition of a relation.
*   **Graph Theory:** A directed graph is a direct visualization of a binary relation on a set.
*   **Lattice Theory:** A lattice is a partially ordered set with special properties.
*   **Category Theory:** A category can be seen as a generalization of a pre-ordered set (a set with a reflexive and transitive relation).
