# Integers

## Mathematical Definition

The **integers**, denoted by \(\mathbb{Z}\), are the set of whole numbers, including the natural numbers (with 0), and their additive inverses (the negative integers).

\[ \mathbb{Z} = \{..., -3, -2, -1, 0, 1, 2, 3, ...\} \]

Formally, the integers can be constructed from the natural numbers \(\mathbb{N}\) as the set of equivalence classes of ordered pairs of natural numbers \((a, b)\), under the equivalence relation:
\[ (a, b) \sim (c, d) \text{ if and only if } a + d = b + c \]
The intuitive meaning of \((a, b)\) is \(a - b\). For example, the integer -2 is represented by the equivalence class of pairs like \((0, 2), (1, 3), (2, 4)\), etc.

Addition and multiplication of integers are defined as follows:
*   \([(a, b)] + [(c, d)] = [(a + c, b + d)]\)
*   \([(a, b)] \cdot [(c, d)] = [(ac + bd, ad + bc)]\)

## Description

The integers extend the natural numbers by including negative numbers. This allows for the representation of quantities that can have a direction or be "less than zero", and it ensures that the subtraction of any two integers is also an integer.

## Subfields it's part of

*   [Number Systems](./)
*   [Number Theory](../../../05_Number_Theory/)
*   [Algebra](../../../01_Algebra/)

## Subfields and concepts it includes

*   **Positive and Negative Numbers**
*   **Absolute Value:** \(|x|\) is the non-negative value of \(x\) without regard to its sign.
*   **Divisibility:** An integer \(a\) is divisible by a non-zero integer \(b\) if there exists an integer \(c\) such that \(a = bc\).
*   **Greatest Common Divisor (GCD) and Least Common Multiple (LCM)**
*   **Modular Arithmetic:** A system of arithmetic for integers, where numbers "wrap around" upon reaching a certain value—the modulus.
*   **Ring Structure:** The set of integers with the operations of addition and multiplication forms a fundamental example of a **ring**.

## Applications

*   **Representing Debt or Deficits:** In finance and accounting.
*   **Physics:** Representing charge, temperature (e.g., Celsius or Fahrenheit scales), and coordinates in space.
*   **Computer Science:** Integer data types are fundamental in programming.
*   **Cryptography:** Modular arithmetic over the integers is central to many cryptographic algorithms.

## More general variants

*   [Rational Numbers](./Rational_Numbers.md): \(\mathbb{Q}\)
*   [Real Numbers](./Real_Numbers.md): \(\mathbb{R}\)
*   **Gaussian Integers:** Complex numbers of the form \(a + bi\), where \(a\) and \(b\) are integers.
*   **Algebraic Integers:** Roots of monic polynomials with integer coefficients.
*   **p-adic Integers**

## More concrete variants

*   [Natural Numbers](./Natural_Numbers.md)
*   **Even and Odd Integers**

## Everything else it relates to

*   **Group Theory:** The integers under addition \((\mathbb{Z}, +)\) form a simple but important example of an infinite cyclic **group**.
*   **Order Theory:** The integers form a totally ordered set.
*   **Equation Solving:** The extension from natural numbers to integers is motivated by the desire to solve equations of the form \(a + x = b\).
