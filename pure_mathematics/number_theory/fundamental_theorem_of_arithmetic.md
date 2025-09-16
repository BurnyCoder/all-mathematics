# Fundamental Theorem of Arithmetic

- **Mathematical Definition**: The fundamental theorem of arithmetic, also called the unique factorization theorem, states that every integer greater than 1 either is a prime number itself or can be represented as a product of prime numbers, and that, moreover, this representation is unique, up to the order of the factors.
  For any integer \\(n > 1\\), there is a unique expression:
  \\( n = p_1^{a_1} p_2^{a_2} \cdots p_k^{a_k} \\)
  where \\(p_1 < p_2 < \dots < p_k\\) are prime numbers and \\(a_i\\) are positive integers.

- **Description**: This theorem is one of the most important results in elementary number theory. It establishes that prime numbers are the basic building blocks of all positive integers. The theorem has two parts: first, that such a factorization exists, and second, that it is unique. This uniqueness is crucial for many proofs and algorithms in number theory.

- **Subfields it's part of**:
    - [Number Theory](https://en.wikipedia.org/wiki/Number_theory)
    - [Pure Mathematics](https://en.wikipedia.org/wiki/Pure_mathematics)

- **Subfields and concepts it includes**:
    - **Integer**: The numbers \\(\dots, -2, -1, 0, 1, 2, \dots\\).
    - **Prime Number**: A natural number greater than 1 that has no positive divisors other than 1 and itself.
    - **Prime Factorization**: The process of finding the prime numbers that multiply together to make the original number.

- **Applications**:
    - **Cryptography**: The difficulty of factoring very large numbers into their prime factors is the basis for the security of many public-key cryptography systems, such as RSA.
    - **Mathematics**: Used in many proofs throughout number theory, for example, to prove the irrationality of \\(\sqrt{2}\\).
    - **Computer Science**: Algorithms for finding greatest common divisors (GCD) and least common multiples (LCM) rely on prime factorization.

- **More Concrete Variants**:
    - This is a fundamental theorem, so it does not have more concrete variants.

- **More General Variants**:
    - **Unique Factorization Domains (UFDs)**: In abstract algebra, the concept is generalized to other [rings](../algebra/ring.md). A UFD is an integral domain in which every non-zero, non-unit element can be written as a product of prime elements, uniquely up to order and units. The integers \\(\mathbb{Z}\\) are an example of a UFD.

- **Related Concepts**:
    - **[Prime Number](./prime_number.md)**: The fundamental building block described by the theorem.
    - **Euclidean Algorithm**: An efficient method for computing the greatest common divisor of two integers, which does not require factorization.
    - **[Ring Theory](../algebra/ring.md)**: The study of rings generalizes the properties of integers, including the concept of unique factorization.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Fundamental_theorem_of_arithmetic](https://en.wikipedia.org/wiki/Fundamental_theorem_of_arithmetic)
