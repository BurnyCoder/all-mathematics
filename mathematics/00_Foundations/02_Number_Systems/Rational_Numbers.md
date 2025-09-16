# Rational Numbers

## Mathematical Definition

The **rational numbers**, denoted by \(\mathbb{Q}\), are the numbers that can be expressed as a fraction \(p/q\) of two integers, where \(p\) is the numerator and \(q\) is a non-zero denominator.

\[ \mathbb{Q} = \left\{ \frac{p}{q} \mid p \in \mathbb{Z}, q \in \mathbb{Z} \setminus \{0\} \right\} \]

Formally, the rational numbers are constructed from the integers \(\mathbb{Z}\) as the set of equivalence classes of ordered pairs of integers \((p, q)\) with \(q \neq 0\), under the equivalence relation:
\[ (p, q) \sim (r, s) \text{ if and only if } ps = qr \]
Each equivalence class \([(p, q)]\) represents a single rational number.

Addition and multiplication are defined as:
*   \([(p, q)] + [(r, s)] = [(ps + qr, qs)]\)
*   \([(p, q)] \cdot [(r, s)] = [(pr, qs)]\)

A rational number can be expressed as a terminating or repeating decimal.

## Description

The rational numbers extend the integers to include fractions. This ensures that the division of any two rational numbers (with a non-zero divisor) is also a rational number. They are "dense" on the number line, meaning between any two distinct rational numbers, there is another rational number.

## Subfields it's part of

*   [Number Systems](./)
*   [Number Theory](../../../05_Number_Theory/)
*   [Algebra](../../../01_Algebra/)
*   [Analysis](../../../02_Analysis/)

## Subfields and concepts it includes

*   **Fractions and Ratios**
*   **Decimal Representation:** Terminating or repeating decimals.
*   **Field Structure:** The rational numbers with addition and multiplication form the first and simplest example of a **field**.

## Applications

*   **Measurement:** Representing quantities that are not whole units.
*   **Engineering and Science:** Used in calculations and modeling.
*   **Computer Science:** Floating-point numbers are used to approximate rational numbers, although they are technically a different set.
*   **Finance:** Dealing with fractions of currencies, stock prices, etc.

## More general variants

*   [Real Numbers](./Real_Numbers.md): \(\mathbb{R}\)
*   [Complex Numbers](./Complex_Numbers.md): \(\mathbb{C}\)
*   **Field of Fractions:** For any integral domain, one can construct its field of fractions, of which \(\mathbb{Q}\) is the prime example, being the field of fractions of \(\mathbb{Z}\).
*   **p-adic Numbers:** An extension of the rational numbers that is different from the real numbers.

## More concrete variants

*   [Integers](./Integers.md)
*   [Natural Numbers](./Natural_Numbers.md)
*   **Dyadic Rationals:** Rational numbers whose denominator is a power of 2.

## Everything else it relates to

*   **Density:** The set of rational numbers is dense in the set of real numbers.
*   **Countability:** The set of rational numbers is countably infinite.
*   **Diophantine Equations:** Equations where only rational or integer solutions are sought.
*   **Equation Solving:** The extension from integers to rationals is motivated by the desire to solve equations of the form \(ax = b\).
