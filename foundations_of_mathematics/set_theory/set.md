# Set

- **Mathematical Definition**: A set is a collection of distinct objects, considered as an object in its own right. Sets are usually denoted by curly braces, e.g., $ A = \{1, 2, 3\} $. The fundamental relation is membership, $ x \in A $, which means $x$ is an element of set $A$. The axiom of extensionality states that two sets are equal if and only if they have the same elements.

- **Description**: The concept of a set is one of the most fundamental in modern mathematics. The study of sets is known as set theory. Naive set theory, which treats sets as any collection of objects, can lead to paradoxes such as [Russell's Paradox](https://en.wikipedia.org/wiki/Russell%27s_paradox). This led to the development of axiomatic set theory, such as [Zermelo–Fraenkel set theory with the axiom of choice (ZFC)](./zfc.md), which provides a more rigorous foundation.

- **Subfields it's part of**:
    - [Set Theory](https://en.wikipedia.org/wiki/Set_theory)
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics)

- **Subfields and concepts it includes**:
    - **Element/Member**: An object belonging to a set.
    - **Subset**: A set $A$ is a subset of a set $B$, denoted $ A \subseteq B $, if every element of $A$ is also an element of $B$.
    - **Power Set**: The set of all subsets of a set.
    - **Cardinality**: The number of elements in a set.
    - **Set Operations**:
        - **Union ($ \cup $)**: The set of all elements that are in at least one of the sets. $ A \cup B = \{x \mid x \in A \text{ or } x \in B\} $.
        - **Intersection ($ \cap $)**: The set of all elements that are in both sets. $ A \cap B = \{x \mid x \in A \text{ and } x \in B\} $.
        - **Complement**: The set of all elements in a universal set $U$ that are not in a given set $A$.
        - **Difference ($ \setminus $)**: The set of elements that are in one set but not the other. $ A \setminus B = \{x \mid x \in A \text{ and } x \notin B\} $.
    - **Cartesian Product ($ \times $)**: The set of all ordered pairs $(a, b)$ where $a \in A$ and $b \in B$.

- **Applications**:
    - **Mathematics**: Forms the basic language and foundation for nearly all fields of mathematics. Relations, functions, numbers, and various mathematical structures are defined in terms of sets.
    - **Computer Science**: Used to model and implement data structures (like hash sets), design algorithms, in database theory (relational algebra), and formal language theory.
    - **Philosophy and Logic**: Used in formal logic and in discussions on the nature of mathematical objects.

- **More Concrete Variants**:
    - **Finite Set**: A set with a finite number of elements.
    - **Infinite Set**: A set that is not finite.
        - **Countably Infinite Set**: An infinite set that can be put into a one-to-one correspondence with the natural numbers.
        - **Uncountably Infinite Set**: An infinite set that cannot.
    - **Empty Set ($ \emptyset $ or $ \{\} $)**: The unique set containing no elements.
    - **Singleton Set**: A set with exactly one element.

- **More General Variants**:
    - **Class**: In set theory, a collection of sets that can be defined by a property of its members. Not all classes are sets (e.g., the class of all sets).
    - **Multiset (or Bag)**: A collection where elements can appear more than once.
    - **Fuzzy Set**: A set where elements have a degree of membership, typically a real number in $[0, 1]$.

- **Related Concepts**:
    - **[Function](../pure_mathematics/algebra/function.md)**: A rule that assigns each element of a set (the domain) to exactly one element of another set (the codomain).
    - **[Relation](../pure_mathematics/algebra/relation.md)**: A set of ordered pairs, which is a subset of the Cartesian product of two or more sets.
    - **[Category Theory](../foundations_of_mathematics/category_theory/category.md)**: A more abstract and general framework for mathematics that deals with objects and morphisms (arrows) between them, where sets are a primary example of a category.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Set_(mathematics)](https://en.wikipedia.org/wiki/Set_(mathematics))
