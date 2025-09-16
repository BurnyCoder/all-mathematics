# Prime Number

## Mathematical Definition

A **prime number** (or a **prime**) is a [natural number](../../../00_Foundations/02_Number_Systems/Natural_Numbers.md) greater than 1 that has no positive divisors other than 1 and itself. A natural number greater than 1 that is not prime is called a **composite number**.

For example, 5 is prime because the only ways of writing it as a product, \(1 \times 5\) or \(5 \times 1\), involve 5 itself. However, 6 is composite because it is the product of two numbers (\(2 \times 3\)) that are both smaller than 6.

The property of being prime is called **primality**.

## Description

Prime numbers are the fundamental building blocks of the natural numbers in the sense of multiplication. They are a central object of study in number theory.

## Subfields it's part of

*   [Number Theory](./)
*   [Cryptography](../)
*   [Algebra](../../../01_Algebra/)

## Subfields and concepts it includes

*   **Fundamental Theorem of Arithmetic:** Every integer greater than 1 is either a prime number itself or can be represented as the product of prime numbers, and this representation is unique, up to the order of the factors. This is also known as the **unique factorization theorem**.
*   **Sieve of Eratosthenes:** A simple, ancient algorithm for finding all prime numbers up to a specified integer.
*   **Primality Testing:** The problem of determining whether a given number is prime.
*   **Integer Factorization:** The process of breaking down a composite number into its prime factors.
*   **Distribution of Primes:** The study of how prime numbers are distributed among the natural numbers. The **Prime Number Theorem** gives an asymptotic description of how many primes there are up to a given magnitude.

## Applications

*   **Cryptography:** The security of many public-key cryptography algorithms, such as RSA, is based on the computational difficulty of factoring large composite numbers that are the product of two large primes.
*   **Computer Science:** Used in hash tables, pseudorandom number generators, and other algorithms.
*   **Nature:** The life cycles of cicadas are famously prime-numbered (13 or 17 years), which is hypothesized to be a strategy to avoid predators with synchronized life cycles.

## More general variants

*   **Prime Element in a Ring:** In abstract algebra, a prime element of a commutative [ring](../../../01_Algebra/01_Abstract_Algebra/01_Ring_Theory/Ring.md) is a non-zero, non-unit element that satisfies a property analogous to prime numbers: if \(p\) divides a product \(ab\), then \(p\) divides \(a\) or \(p\) divides \(b\).
*   **Irreducible Element:** An element that cannot be factored into non-unit elements. In a unique factorization domain (like the integers), prime and irreducible elements are the same.
*   **Prime Ideal:** A concept in ring theory that generalizes the notion of a prime element.

## More concrete variants

*   **Twin Primes:** Pairs of prime numbers that differ by 2 (e.g., (11, 13)).
*   **Mersenne Primes:** Prime numbers of the form \(2^n - 1\).
*   **Fermat Primes:** Prime numbers of the form \(2^{2^n} + 1\).
*   **Sophie Germain Primes:** A prime \(p\) such that \(2p + 1\) is also prime.

## Everything else it relates to

*   **Riemann Hypothesis:** A famous unsolved conjecture in mathematics that is deeply connected to the distribution of prime numbers.
*   **Euclid's Theorem on the Infinitude of Primes:** The classic proof that there are infinitely many prime numbers.
*   **Goldbach Conjecture:** An unsolved conjecture stating that every even integer greater than 2 is the sum of two primes.
*   **Modular Arithmetic:** Plays a crucial role in primality testing algorithms like the Fermat primality test and the Miller-Rabin primality test.
