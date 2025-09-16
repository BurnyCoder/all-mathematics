# Modular Arithmetic

## Mathematical Definition

**Modular arithmetic** is a system of arithmetic for [integers](../../../00_Foundations/02_Number_Systems/Integers.md), where numbers "wrap around" when reaching a certain value—the **modulus**.

Two integers \(a\) and \(b\) are said to be **congruent modulo n** if they have the same remainder when divided by the positive integer \(n\). This relationship is written as:
\[ a \equiv b \pmod{n} \]
This is equivalent to saying that their difference \(a - b\) is an integer multiple of \(n\).

For example:
\[ 38 \equiv 14 \pmod{12} \]
because both 38 and 14 have the same remainder, 2, when divided by 12. Also, their difference, \(38 - 14 = 24\), is a multiple of 12.

Modular arithmetic can be performed on the set of integers. The operations of addition and multiplication are defined as follows:
If \(a_1 \equiv b_1 \pmod{n}\) and \(a_2 \equiv b_2 \pmod{n}\), then:
*   \(a_1 + a_2 \equiv b_1 + b_2 \pmod{n}\)
*   \(a_1 \cdot a_2 \equiv b_1 \cdot b_2 \pmod{n}\)

This system of arithmetic is often performed on the set of least non-negative remainders modulo n, which is \(\{0, 1, 2, ..., n-1\}\). This set, equipped with the operations of addition and multiplication modulo n, forms a **ring**, denoted \(\mathbb{Z}/n\mathbb{Z}\) or \(\mathbb{Z}_n\).

## Description

Modular arithmetic is often called "clock arithmetic". If the time is 9:00 now, then 4 hours later it will be 1:00. A simple addition would result in \(9 + 4 = 13\), but clocks "wrap around" every 12 hours. In the language of modular arithmetic, we would say that \(13 \equiv 1 \pmod{12}\). It is a system of arithmetic that deals with remainders.

## Subfields it's part of

*   [Number Theory](./)
*   [Abstract Algebra](../../../01_Algebra/)
*   [Cryptography](../)

## Subfields and concepts it includes

*   **Congruence Relation:** An equivalence relation that is compatible with the operations of addition and multiplication.
*   **Residue Classes:** The set of all integers that have the same remainder when divided by \(n\).
*   **Chinese Remainder Theorem:** A theorem that gives a unique solution to a system of simultaneous congruences with coprime moduli.
*   **Fermat's Little Theorem:** If \(p\) is a [prime number](./Prime_Number.md), then for any integer \(a\), the number \(a^p - a\) is an integer multiple of \(p\). In the notation of modular arithmetic, this is \(a^p \equiv a \pmod{p}\).
*   **Euler's Totient Theorem:** A generalization of Fermat's Little Theorem.
*   **Primitive Roots Modulo n:** A number \(g\) is a primitive root modulo n if every number coprime to n is congruent to a power of \(g\) modulo n.
*   **Multiplicative Inverse:** An integer \(a\) has a multiplicative inverse modulo n if there exists an integer \(x\) such that \(ax \equiv 1 \pmod{n}\). This inverse exists if and only if \(a\) and \(n\) are coprime.

## Applications

*   **Cryptography:** Modular arithmetic is the foundation of many public-key cryptographic systems, including RSA and Diffie-Hellman key exchange. It is also used in elliptic curve cryptography.
*   **Computer Science:** Used in hash functions, pseudorandom number generators, and to check for errors in identification numbers (e.g., checksums).
*   **Error-Correcting Codes:** Used in codes like the Reed-Solomon code.
*   **Music:** Used to describe the 12-tone system in music theory.
*   **Date and Time Calculations:** As in the clock example.

## More general variants

*   The concept of congruence can be generalized to other algebraic structures, such as rings and groups. The construction of a **quotient ring** or **quotient group** is a direct generalization of the ring \(\mathbb{Z}_n\).

## More concrete variants

*   **Binary arithmetic** is essentially arithmetic modulo 2.

## Everything else it relates to

*   **Group Theory:** The set of integers coprime to \(n\) forms a group under multiplication modulo \(n\), denoted \((\mathbb{Z}/n\mathbb{Z})^\times\).
*   **Ring Theory:** The set \(\mathbb{Z}_n\) with addition and multiplication modulo n is a commutative [ring](../../../01_Algebra/01_Abstract_Algebra/01_Ring_Theory/Ring.md).
*   **Field Theory:** \(\mathbb{Z}_n\) is a [field](../../../01_Algebra/01_Abstract_Algebra/02_Field_Theory/Field.md) if and only if \(n\) is a prime number. These finite fields are fundamental in many applications.
*   **Division Algorithm:** The basis for the concept of remainders.
