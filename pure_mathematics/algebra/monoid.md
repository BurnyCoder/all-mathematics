# Monoid

- **Mathematical Definition**: A monoid is a set $M$ equipped with a binary operation $\cdot: M \times M \to M$ that satisfies two axioms:
    1.  **Associativity**: For all $a, b, c \in M$, $(a \cdot b) \cdot c = a \cdot (b \cdot c)$.
    2.  **Identity Element**: There exists an element $e \in M$ such that for every element $a \in M$, $e \cdot a = a \cdot e = a$.

- **Description**: A monoid is a fundamental algebraic structure that is more general than a group but more specific than a semigroup. It consists of a set with an associative operation and an identity element. This structure is common in many areas of mathematics and computer science, representing systems where operations can be combined associatively and where there's a "do-nothing" or "empty" operation.

- **Subfields it's part of**:
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra): Monoids are a basic object of study in abstract algebra.
    - [Category Theory](https://en.wikipedia.org/wiki/Category_theory): A monoid can be seen as a category with a single object.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science): Monoids are important in formal language theory (e.g., strings with concatenation) and functional programming.

- **Subfields and concepts it includes**:
    - **Submonoid**: A subset of a monoid that is itself a monoid under the same operation.
    - **Monoid Homomorphism**: A function between two monoids that preserves the monoid operation and the identity element.
    - **Commutative Monoid**: A monoid where the binary operation is commutative ($a \cdot b = b \cdot a$).

- **Applications**:
    - **Computer Science**:
        - **Formal Languages**: The set of all strings over an alphabet forms a monoid under string concatenation, with the empty string as the identity. This is fundamental to automata theory.
        - **Functional Programming**: Monoids are used as a design pattern for combining computations, particularly in parallel and distributed systems (e.g., MapReduce). The "mappend" operation is the monoid operation, and "mempty" is the identity.
        - **Data Structures**: The concept of a "fold" or "reduce" operation on lists and other data structures is essentially a monoid operation.
    - **Category Theory**: The set of endomorphisms of an object in a category forms a monoid.

- **More Concrete Variants**:
    - **Free Monoid**: The monoid of all finite strings over a given alphabet.
    - **Commutative Monoid**: Example: The natural numbers (including 0) under addition form a commutative monoid. The natural numbers (including 1) under multiplication also form a commutative monoid.

- **More General Variants**:
    - **[Semigroup](./semigroup.md)**: A set with an associative binary operation (drops the identity axiom). Every monoid is a semigroup.
    - **[Magma (or Groupoid)](./magma.md)**: A set with a closed binary operation (drops associativity and identity).

- **Related Concepts**:
    - **[Group](./group.md)**: A monoid where every element has an inverse. Every group is a monoid.
    - **[Ring](./ring.md)**: A set with two binary operations, forming a commutative group under addition and a monoid under multiplication.
    - **[Set](../../foundations_of_mathematics/set_theory/set.md)**: A monoid is a set with additional structure.
    - **[Category](../../foundations_of_mathematics/category_theory/category.md)**: A monoid can be defined as a category with a single object.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Monoid](https://en.wikipedia.org/wiki/Monoid)
