# Category

- **Mathematical Definition**: A category $\mathcal{C}$ consists of:
    1.  A collection of **objects**, denoted $\text{ob}(\mathcal{C})$.
    2.  A collection of **morphisms** (or arrows), denoted $\text{hom}(\mathcal{C})$. Each morphism $f$ has a source object $A$ and a target object $B$, written $f: A \to B$.
    3.  For every three objects $A, B, C$, a binary operation called **composition** of morphisms, which takes two morphisms $f: A \to B$ and $g: B \to C$ and produces a morphism $g \circ f: A \to C$.
This composition must satisfy two axioms:
    - **Associativity**: If $f: A \to B$, $g: B \to C$, and $h: C \to D$, then $h \circ (g \circ f) = (h \circ g) \circ f$.
    - **Identity**: For every object $X$, there exists an identity morphism $\text{id}_X: X \to X$ such that for any morphism $f: A \to X$ and $g: X \to B$, we have $\text{id}_X \circ f = f$ and $g \circ \text{id}_X = g$.

- **Description**: Category theory is a highly abstract branch of mathematics that formalizes mathematical structures and their relationships in a unified way. It emphasizes the relationships (morphisms) between objects rather than the internal structure of the objects themselves. It has been described as a "general theory of functions" and provides a powerful alternative language for the foundations of mathematics.

- **Subfields it's part of**:
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics): Category theory provides an alternative to set theory as a foundation for mathematics.
    - [Pure Mathematics](https://en.wikipedia.org/wiki/Pure_mathematics) (especially Abstract Algebra, Algebraic Topology, and Homological Algebra): It serves as a unifying language for many fields of pure mathematics.

- **Subfields and concepts it includes**:
    - **Object**: A fundamental unit of a category.
    - **Morphism (Arrow)**: A directed connection between two objects.
    - **Functor**: A structure-preserving map between categories.
    - **Natural Transformation**: A map between two functors.
    - **Limit and Colimit**: General constructions that include products, coproducts, and pullbacks.
    - **Adjoint Functors**: A fundamental relationship between two functors.
    - **Monad**: An endofunctor along with two natural transformations, used extensively in functional programming.

- **Applications**:
    - **Mathematics**: Provides the language for many advanced fields like algebraic geometry, algebraic topology, and homological algebra.
    - **Computer Science**:
        - **Functional Programming**: Concepts like functors, applicative functors, and monads are directly applied in languages like Haskell to handle side effects and structure computations.
        - **Type Theory**: The study of type systems for programming languages.
        - **Database Theory**: Can be used to model database schemas.
    - **Physics**: Used in quantum field theory and string theory to structure and understand physical theories.

- **More Concrete Variants (Examples of Categories)**:
    - **Set**: The category of sets, where objects are sets and morphisms are functions.
    - **Grp**: The category of groups, where objects are groups and morphisms are group homomorphisms.
    - **Top**: The category of topological spaces, where objects are topological spaces and morphisms are continuous functions.
    - **Vect**: The category of vector spaces (over a given field), with linear maps as morphisms.
    - **Poset**: Any partially ordered set can be viewed as a small category.

- **More General Variants**:
    - **Higher Category Theory**: Studies n-categories, where there are morphisms between morphisms (2-morphisms), morphisms between 2-morphisms (3-morphisms), and so on.
    - **Enriched Category Theory**: Generalizes the idea that the collection of morphisms between two objects forms a set, allowing it to be an object in some other category.

- **Related Concepts**:
    - **[Set Theory](../set_theory/set.md)**: The category **Set** is the most common and intuitive example of a category. Category theory can be seen as an alternative or a generalization of set theory for founding mathematics.
    - **Universal Algebra**: Studies algebraic structures in general, and category theory provides a powerful language for this.
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra): Many structures from abstract algebra (groups, rings, fields) form important examples of categories.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Category_theory](https://en.wikipedia.org/wiki/Category_theory)
