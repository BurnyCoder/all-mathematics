# Field

## Mathematical Definition

A **field** is a [set](../../../../../00_Found-ations/01_Set_Theory/Set.md) \(F\) together with two operations, addition (+) and multiplication (·), such that the following axioms hold:

1.  **\( (F, +) \) is an abelian group:**
    *   The set \(F\) is closed under addition.
    *   Addition is associative and commutative.
    *   There is an additive identity element, 0.
    *   Every element \(a\) has an additive inverse, \(-a\).

2.  **\( (F \setminus \{0\}, \cdot) \) is an abelian group:**
    *   The set of non-zero elements, \(F \setminus \{0\}\), is closed under multiplication.
    *   Multiplication is associative and commutative.
    *   There is a multiplicative identity element, 1 (where \(1 \neq 0\)).
    *   Every non-zero element \(a\) has a multiplicative inverse, \(a^{-1}\).

3.  **Distributive Law:**
    *   Multiplication distributes over addition: \(a \cdot (b + c) = (a \cdot b) + (a \cdot c)\) for all \(a, b, c \in F\).

In essence, a field is a non-trivial **commutative ring** in which every non-zero element has a multiplicative inverse.

## Description

A field is an algebraic structure where one can perform addition, subtraction, multiplication, and division (by non-zero elements). The four basic arithmetic operations behave as they do for rational and real numbers. Fields are the fundamental objects of study in field theory and are widely used in many areas of mathematics.

## Subfields it's part of

*   [Field Theory](./)
*   [Abstract Algebra](../)
*   [Number Theory](../../../../05_Number_Theory/)
*   [Galois Theory](../)
*   [Algebraic Geometry](../../../../03_Geometry/02_Algebraic_Geometry/)

## Subfields and concepts it includes

*   **Subfield:** A subset of a field that is itself a field under the same operations.
*   **Field Extension:** A field \(L\) is an extension of a field \(K\) if \(K\) is a subfield of \(L\). This is a central concept in Galois theory.
*   **Characteristic of a Field:** The smallest positive integer \(n\) such that adding the multiplicative identity to itself \(n\) times equals the additive identity (i.e., \(1 + 1 + ... + 1 = 0\)). If no such \(n\) exists, the characteristic is 0. The characteristic must be either 0 or a prime number.
*   **Finite Field (or Galois Field):** A field with a finite number of elements. The number of elements must be a power of a prime, \(p^n\).
*   **Algebraically Closed Field:** A field in which every non-constant polynomial has a root. The [complex numbers](../../../../../00_Foundations/02_Number_Systems/Complex_Numbers.md) are the canonical example.
*   **Field Homomorphism:** A function between two fields that preserves both addition and multiplication.

## Applications

*   **Galois Theory:** Uses field extensions to study the roots of polynomial equations and prove the impossibility of certain geometric constructions (like squaring the circle) and the insolvability of the quintic equation by radicals.
*   **Number Theory:** The study of algebraic number fields (finite extensions of \(\mathbb{Q}\)) is a central part of algebraic number theory.
*   **Coding Theory and Cryptography:** Finite fields are used extensively in error-correcting codes and cryptography (e.g., AES, elliptic curve cryptography).
*   **Linear Algebra:** The scalars in a vector space are required to come from a field.
*   **Quantum Physics:** Quantum mechanics is formulated over the field of complex numbers.

## More general variants

*   **Division Ring (or Skew Field):** A ring where every non-zero element has a multiplicative inverse, but multiplication is not necessarily commutative. The quaternions are a key example.
*   [Ring](../01_Ring_Theory/Ring.md): A field is a specific type of ring.

## More concrete variants

*   **The Field of Rational Numbers \((\mathbb{Q})\)**
*   **The Field of Real Numbers \((\mathbb{R})\)**
*   **The Field of Complex Numbers \((\mathbb{C})\)**
*   **Finite Fields \(\mathbb{F}_p\) (or \(\mathbb{Z}/p\mathbb{Z}\)):** The integers modulo a prime \(p\).
*   **Field of rational functions \(F(x)\)**

## Everything else it relates to

*   **Vector Spaces:** The definition of a vector space requires a base field of scalars.
*   **Polynomials:** The properties of polynomial rings are deeply connected to the properties of the underlying field of coefficients. The roots of polynomials lead to the study of field extensions.
*   **Geometry:** Fields are fundamental to algebraic geometry, where points are defined by coordinates from a field.
