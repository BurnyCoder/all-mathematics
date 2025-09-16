# Natural Transformation

## Mathematical Definition

A **natural transformation** is a map between two [functors](./Functor.md) that are acting between the same two [categories](./Category.md). It provides a way to transform one functor into another while respecting the internal structure (the morphisms) of the categories.

Given two parallel functors, \(F, G: C \to D\), a natural transformation \(\eta\) from \(F\) to \(G\), denoted \(\eta: F \Rightarrow G\), is a family of morphisms in \(D\), indexed by the objects of \(C\).

Specifically, for every object \(X\) in \(C\), there is a morphism \(\eta_X: F(X) \to G(X)\) in \(D\). This morphism is called the **component** of \(\eta\) at \(X\).

This family of morphisms must satisfy the **naturality condition**: for every morphism \(f: X \to Y\) in \(C\), the following diagram commutes:
```
      F(f)
F(X) ------> F(Y)
  |           |
η_X |           | η_Y
  v           v
G(X) ------> G(Y)
      G(f)
```
The commutativity of this diagram means that \( \eta_Y \circ F(f) = G(f) \circ \eta_X \).

## Description

If functors are "morphisms between categories", then natural transformations are "morphisms between functors". This concept captures the idea of a "natural" or "canonical" way of transforming one mathematical construction into another. It is one of the most fundamental concepts in category theory.

## Subfields it's part of

*   [Category Theory](./)

## Subfields and concepts it includes

*   **Natural Isomorphism:** A natural transformation \(\eta\) is a natural isomorphism if each of its components \(\eta_X\) is an isomorphism in the category \(D\). Two functors are naturally isomorphic if there is a natural isomorphism between them. This is a very strong notion of "sameness" for functors.
*   **Functor Category:** For categories \(C\) and \(D\), one can form a functor category, denoted \(D^C\) or \(\text{Fun}(C, D)\). The objects of this category are the functors from \(C\) to \(D\), and the morphisms are the natural transformations between these functors.

## Applications

*   **Algebraic Topology:** The relationship between the fundamental group of a space and its first homology group is formalized by a natural transformation.
*   **Algebra:** The map from a vector space to its double dual is a classic example of a natural transformation (and often a natural isomorphism for finite-dimensional spaces).
*   **Functional Programming:** The concept of polymorphism is often described using natural transformations. For example, a function that reverses a list of any type (e.g., `reverse : forall a. List a -> List a`) is a natural transformation.
*   **Unifying Mathematical Concepts:** Many canonical maps in mathematics (e.g., the determinant of a matrix, the abelianization of a group) can be understood as components of a natural transformation.

## Everything else it relates to

*   **Yoneda Lemma:** A foundational result in category theory that describes how any object in a category can be represented by a functor, and that natural transformations between these representable functors are in one-to-one correspondence with the morphisms between the objects. It implies that an object is completely determined by the network of morphisms into and out of it.
*   **Adjoint Functors:** The definition of an adjunction between two functors involves a natural isomorphism.
