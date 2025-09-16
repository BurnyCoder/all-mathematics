# Vector Space

- **Mathematical Definition**: A vector space over a field $F$ is a set $V$ equipped with two operations:
    1.  **Vector Addition**: $+: V \times V \to V$
    2.  **Scalar Multiplication**: $\cdot: F \times V \to V$
These operations must satisfy the following axioms for all vectors $\mathbf{u}, \mathbf{v}, \mathbf{w} \in V$ and scalars $a, b \in F$:
    - $(V, +)$ is an abelian group (associativity, commutativity, additive identity $\mathbf{0}$, and additive inverse $-\mathbf{v}$).
    - **Compatibility** of scalar multiplication with field multiplication: $a(b\mathbf{v}) = (ab)\mathbf{v}$.
    - **Identity element** of scalar multiplication: $1\mathbf{v} = \mathbf{v}$, where $1$ is the multiplicative identity in $F$.
    - **Distributivity** of scalar multiplication with respect to vector addition: $a(\mathbf{u}+\mathbf{v}) = a\mathbf{u} + a\mathbf{v}$.
    - **Distributivity** of scalar multiplication with respect to field addition: $(a+b)\mathbf{v} = a\mathbf{v} + b\mathbf{v}$.

- **Description**: Vector spaces are the fundamental objects of study in linear algebra. They are an abstract algebraic structure that formalizes and generalizes the concept of geometric vectors. Elements of a vector space are called vectors, and the elements of the underlying field are called scalars. Vector spaces allow for the rigorous study of concepts like length, angle, and orientation in arbitrary dimensions.

- **Subfields it's part of**:
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra)
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra)
    - [Functional Analysis](https://en.wikipedia.org/wiki/Functional_analysis)

- **Subfields and concepts it includes**:
    - **Vector**: An element of a vector space.
    - **Scalar**: An element of the underlying field.
    - **Basis**: A set of linearly independent vectors that span the entire space.
    - **Dimension**: The number of vectors in a basis for the vector space.
    - **Linear Transformation (or Linear Map)**: A function between two vector spaces that preserves the operations of vector addition and scalar multiplication.
    - **Subspace**: A subset of a vector space that is itself a vector space.
    - **Span**: The set of all linear combinations of a set of vectors.
    - **Linear Independence**: A property of a set of vectors, meaning none of them can be written as a linear combination of the others.

- **Applications**:
    - **Physics and Engineering**: Used to model physical quantities like forces, velocities, and electromagnetic fields. Essential in classical mechanics, quantum mechanics, and general relativity.
    - **Computer Graphics**: Central to representing positions, orientations, and transformations of 3D objects.
    - **Machine Learning**: Datasets are often represented as vectors in high-dimensional vector spaces (feature vectors).
    - **Optimization**: Solving systems of linear equations and linear programming problems.
    - **Differential Equations**: The solutions to a linear homogeneous differential equation form a vector space.

- **More Concrete Variants**:
    - **Euclidean Space ($\mathbb{R}^n$)**: The space of n-tuples of real numbers.
    - **Complex Vector Space ($\mathbb{C}^n$)**: The space of n-tuples of complex numbers.
    - **Function Spaces**: Vector spaces where the vectors are functions, such as the space of all continuous functions on an interval.
    - **Polynomial Spaces**: Vector spaces where the vectors are polynomials up to a certain degree.

- **More General Variants**:
    - **Module**: The same structure as a vector space, but the scalars are from a [ring](./ring.md) instead of a [field](./field.md).
    - **Banach Space**: A complete normed vector space.
    - **Hilbert Space**: A complete inner product space, generalizing Euclidean space.

- **Related Concepts**:
    - **[Field](./field.md)**: The set of scalars for a vector space must be a field.
    - **Linear Transformation**: The structure-preserving map between vector spaces.
    - **Matrix**: A rectangular array of numbers that is commonly used to represent a linear transformation between finite-dimensional vector spaces.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Vector_space](https://en.wikipedia.org/wiki/Vector_space)
