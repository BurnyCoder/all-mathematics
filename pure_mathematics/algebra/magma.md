# Magma (or Groupoid)

- **Mathematical Definition**: A magma (also known as a groupoid, though that term has other meanings in mathematics) is a set $M$ equipped with a single binary operation $\cdot: M \times M \to M$. This operation must be **closed**, meaning that for any two elements $a, b \in M$, the result $a \cdot b$ is also in $M$. No other properties (like associativity, identity, or inverses) are required.

- **Description**: A magma is the most basic type of algebraic structure. It is simply a set of elements and a rule for combining any two of them. Because the definition is so minimal, the world of magmas is incredibly diverse and includes many structures that are not associative or do not have an identity element. The term "groupoid" was historically used for this concept, but it is now more commonly used for a concept in category theory, so "magma" is often preferred to avoid confusion.

- **Subfields it's part of**:
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra): Magmas are the most general form of algebraic structures with a single binary operation.
    - [Universal Algebra](https://en.wikipedia.org/wiki/Universal_algebra): This field studies algebraic structures in general, and magmas are a primary example.

- **Subfields and concepts it includes**:
    - **Submagma**: A subset of a magma that is closed under the magma's binary operation.
    - **Magma Homomorphism**: A function $f: M \to N$ between two magmas $(M, \cdot)$ and $(N, *)$ such that $f(x \cdot y) = f(x) * f(y)$ for all $x, y \in M$.

- **Applications**:
    - **Combinatorics**: Certain combinatorial structures can be described using magmas.
    - **Loop Theory**: Loops are a type of magma with an identity and inverses, but are not necessarily associative. They have applications in geometry.
    - **Theoretical Computer Science**: Magmas can be used to model various computational processes where the order of operations matters and is not necessarily associative.

- **More Concrete Variants**:
    - **[Semigroup](./semigroup.md)**: A magma where the operation is associative.
    - **[Monoid](./monoid.md)**: An associative magma with an identity element.
    - **[Group](./group.md)**: An associative magma with an identity element and inverses for all elements.
    - **Quasigroup**: A magma where for any $a, b$, the equations $a \cdot x = b$ and $y \cdot a = b$ have unique solutions for $x$ and $y$. This property is related to the existence of "division".
    - **Loop**: A quasigroup with an identity element.
    - **Commutative Magma**: A magma where the operation is commutative ($a \cdot b = b \cdot a$).

- **More General Variants**:
    - There are no standard algebraic structures more general than a magma, as it only requires a set and a closed binary operation. One could consider a set with a partial binary operation, but this is less common in abstract algebra.

- **Related Concepts**:
    - **[Set](../../foundations_of_mathematics/set_theory/set.md)**: A magma is a set with the minimal additional structure of a binary operation.
    - **Binary Operation**: This is the fundamental component of a magma.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Magma_(algebra)](https://en.wikipedia.org/wiki/Magma_(algebra))
