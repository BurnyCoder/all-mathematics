# Category

## Mathematical Definition

A **category** \(C\) consists of the following three components:

1.  A class of **objects**, denoted \(\text{ob}(C)\).
2.  A class of **morphisms** (also called arrows or maps), denoted \(\text{hom}(C)\). Each morphism \(f\) has a **source object** \(A \in \text{ob}(C)\) and a **target object** \(B \in \text{ob}(C)\). We write this as \(f: A \to B\). The class of all morphisms from \(A\) to \(B\) is denoted \(\text{hom}(A, B)\).
3.  A binary operation called **composition of morphisms**, denoted \(\circ\). For any three objects \(A, B, C\), composition is a map \(\circ: \text{hom}(B, C) \times \text{hom}(A, B) \to \text{hom}(A, C)\). For morphisms \(f: A \to B\) and \(g: B \to C\), their composition is written as \(g \circ f: A \to C\).

This structure must satisfy two axioms:

1.  **Associativity:** For any morphisms \(f: A \to B\), \(g: B \to C\), and \(h: C \to D\), the following holds:
    \[ h \circ (g \circ f) = (h \circ g) \circ f \]
2.  **Identity:** For every object \(X\), there exists a morphism \(\text{id}_X: X \to X\), called the **identity morphism** for \(X\), such that for every morphism \(f: A \to X\) and every morphism \(g: X \to B\), the following holds:
    \[ \text{id}_X \circ f = f \quad \text{and} \quad g \circ \text{id}_X = g \]

## Description

Category theory is a high-level abstraction in mathematics that formalizes mathematical structures and the relationships between them. It is a "theory of everything" for mathematics. A category can be thought of as a collection of objects and the structure-preserving maps between them. Instead of focusing on the internal elements of the objects, category theory emphasizes the relationships (morphisms) between them.

## Subfields it's part of

*   [Category Theory](./)
*   Foundations of Mathematics
*   [Abstract Algebra](../../01_Algebra/01_Abstract_Algebra/)
*   [Topology](../../04_Topology/) (specifically Algebraic Topology)

## Subfields and concepts it includes

*   **Functor:** A structure-preserving map between categories. It maps objects to objects and morphisms to morphisms.
*   **Natural Transformation:** A map between two functors.
*   **Universal Property:** A property that characterizes the result of some construction up to a unique isomorphism. Examples include products, coproducts, limits, and colimits.
*   **Duality:** For any category \(C\), its dual or opposite category \(C^{op}\) is formed by reversing all the morphisms. Any statement or theorem about \(C\) has a dual statement about \(C^{op}\).
*   **Adjoint Functors:** A pair of functors that are in a special, symmetric relationship with each other.
*   **Monad:** A monoid in the category of endofunctors. Monads are used to model computational effects in functional programming and to describe algebraic structures.

## Applications

*   **Algebraic Topology:** Category theory provides the natural language for describing fundamental concepts like the fundamental group and homology groups, which are functors.
*   **Abstract Algebra:** Many algebraic structures, such as groups, rings, and vector spaces, can be seen as objects in specific categories. Category theory unifies the study of these structures by formalizing concepts like homomorphisms.
*   **Computer Science:**
    *   **Functional Programming:** Type systems and control structures (like monads for handling side effects) are based on category theory.
    *   **Type Theory:** The correspondence between logic and computation is often expressed in the language of category theory.
*   **Logic:** The structure of proofs in deductive systems can be described by categories.
*   **Physics:** Used in topological quantum field theory.

## More general variants

*   **Higher Category Theory:** Studies n-categories, where there can be morphisms between morphisms (2-morphisms), morphisms between 2-morphisms (3-morphisms), and so on.
*   **Enriched Category:** A category where the hom-sets are not just sets, but objects in some other category.

## More concrete variants

Many mathematical structures form categories:
*   **Set:** The category of [sets](../../00_Foundations/01_Set_Theory/Set.md), where objects are sets and morphisms are [functions](../../00_Foundations/01_Set_Theory/Function.md).
*   **Grp:** The category of [groups](../../01_Algebra/01_Abstract_Algebra/00_Group_Theory/Group.md), where objects are groups and morphisms are group homomorphisms.
*   **Ring:** The category of [rings](../../01_Algebra/01_Abstract_Algebra/01_Ring_Theory/Ring.md), where objects are rings and morphisms are ring homomorphisms.
*   **Vect:** The category of [vector spaces](../../01_Algebra/02_Linear_Algebra/Vector_Space.md) over a given field, where objects are vector spaces and morphisms are linear transformations.
*   **Top:** The category of [topological spaces](../../04_Topology/Topological_Space.md), where objects are topological spaces and morphisms are continuous functions.
*   **Poset:** Any partially ordered set can be viewed as a category where objects are the elements of the set and there is a unique morphism from \(a\) to \(b\) if and only if \(a \le b\).

## Everything else it relates to

*   **Universal Algebra:** Both fields study algebraic structures, but category theory is more general as it focuses on the morphisms.
*   **Set Theory:** Traditionally, category theory is built upon set theory (or class theory), but there are alternative foundations for mathematics based on category theory itself.
