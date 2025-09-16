# Ring

## Mathematical Definition

A **ring** is an algebraic structure consisting of a [set](../../../../../00_Foundations/01_Set_Theory/Set.md) \(R\) equipped with two binary operations, usually called addition (+) and multiplication (·), satisfying the following axioms:

1.  **\( (R, +) \) is an abelian group:**
    *   **Closure under addition:** For all \(a, b \in R\), \(a + b \in R\).
    *   **Associativity of addition:** For all \(a, b, c \in R\), \((a + b) + c = a + (b + c)\).
    *   **Additive identity:** There exists an element 0 in \(R\) such that for all \(a \in R\), \(a + 0 = 0 + a = a\).
    *   **Additive inverse:** For each \(a \in R\), there exists \(-a \in R\) such that \(a + (-a) = (-a) + a = 0\).
    *   **Commutativity of addition:** For all \(a, b \in R\), \(a + b = b + a\).

2.  **\( (R, \cdot) \) is a monoid (in modern definitions):**
    *   **Closure under multiplication:** For all \(a, b \in R\), \(a \cdot b \in R\).
    *   **Associativity of multiplication:** For all \(a, b, c \in R\), \((a \cdot b) \cdot c = a \cdot (b \cdot c)\).
    *   **Multiplicative identity:** There exists an element 1 in \(R\) such that for all \(a \in R\), \(a \cdot 1 = 1 \cdot a = a\). (Note: Some older definitions define a "rng" without a multiplicative identity).

3.  **Multiplication distributes over addition:**
    *   For all \(a, b, c \in R\), \(a \cdot (b + c) = (a \cdot b) + (a \cdot c)\) (left distributivity).
    *   For all \(a, b, c \in R\), \((b + c) \cdot a = (b \cdot a) + (c \cdot a)\) (right distributivity).

## Description

A ring is a set with two operations that generalize the arithmetic of the [integers](../../../../../00_Foundations/02_Number_Systems/Integers.md). It is a more complex structure than a [group](../00_Group_Theory/Group.md) because it involves two interacting operations.

## Subfields it's part of

*   [Ring Theory](./)
*   [Abstract Algebra](../)
*   [Number Theory](../../../../05_Number_Theory/)
*   [Algebraic Geometry](../../../../03_Geometry/02_Algebraic_Geometry/)

## Subfields and concepts it includes

*   **Commutative Ring:** A ring where multiplication is commutative (\(a \cdot b = b \cdot a\)).
*   **Integral Domain:** A non-trivial commutative ring in which the product of any two non-zero elements is non-zero.
*   **Field:** A non-trivial commutative ring where every non-zero element has a multiplicative inverse.
*   **Subring:** A subset of a ring that is itself a ring with the same operations.
*   **Ideal:** A special type of subring that plays a role similar to that of normal subgroups in group theory. Ideals are used to construct **quotient rings**.
*   **Ring Homomorphism:** A function between two rings that preserves both the addition and multiplication operations.
*   **Units:** The elements of a ring that have a multiplicative inverse.
*   **Zero Divisors:** A non-zero element \(a\) is a zero divisor if there exists a non-zero element \(b\) such that \(a \cdot b = 0\).

## Applications

*   **Number Theory:** The integers \(\mathbb{Z}\) form a prototypical ring. The study of modular arithmetic involves the rings of integers modulo n, \(\mathbb{Z}_n\).
*   **Algebraic Geometry:** Studies geometric objects (algebraic varieties) that are defined by the zeros of polynomial rings.
*   **Polynomial Rings:** The set of polynomials with coefficients in a ring forms another ring, which is fundamental in many areas of algebra.
*   **Linear Algebra:** The set of all \(n \times n\) matrices over a field forms a ring (the matrix ring).
*   **Functional Analysis:** Rings of continuous functions are studied.
*   **Coding Theory:** Finite rings and fields are used in error-correcting codes.

## More general variants

*   **Semiring:** Similar to a ring, but the set under addition is only required to be a monoid, not a group (no additive inverses).
*   **Near-ring:** A structure that satisfies all the ring axioms except for commutativity of addition and one of the distributive laws.

## More concrete variants

*   **The Ring of Integers \((\mathbb{Z}, +, \cdot)\)**
*   **The Ring of Integers Modulo n \((\mathbb{Z}_n, +, \cdot)\)**
*   **Ring of Polynomials \(R[x]\)**
*   **Matrix Ring \(M_n(R)\)**
*   **Division Ring (or Skew Field):** A ring where every non-zero element has a multiplicative inverse (multiplication is not necessarily commutative).

## Everything else it relates to

*   **Group Theory:** A ring is an abelian group under addition. The set of units in a ring forms a group under multiplication.
*   **Field Theory:** Fields are a specific, important class of rings.
*   **Module Theory:** A module is a generalization of a vector space where the scalars come from a ring instead of a field.
