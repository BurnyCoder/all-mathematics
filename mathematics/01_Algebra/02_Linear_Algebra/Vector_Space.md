# Vector Space

## Mathematical Definition

A **vector space** (or linear space) over a [field](../../01_Abstract_Algebra/02_Field_Theory/Field.md) \(F\) is a [set](../../../../00_Foundations/01_Set_Theory/Set.md) \(V\) of objects called **vectors**, equipped with two operations:

1.  **Vector Addition:** An operation that takes two vectors \(\mathbf{u}, \mathbf{v} \in V\) and produces another vector \(\mathbf{u} + \mathbf{v} \in V\).
2.  **Scalar Multiplication:** An operation that takes a **scalar** \(c \in F\) and a vector \(\mathbf{v} \in V\) and produces another vector \(c\mathbf{v} \in V\).

These operations must satisfy the following eight axioms for all \(\mathbf{u}, \mathbf{v}, \mathbf{w} \in V\) and all scalars \(a, b \in F\):

1.  **\( (V, +) \) is an abelian group:**
    *   **Associativity of vector addition:** \((\mathbf{u} + \mathbf{v}) + \mathbf{w} = \mathbf{u} + (\mathbf{v} + \mathbf{w})\).
    *   **Commutativity of vector addition:** \(\mathbf{u} + \mathbf{v} = \mathbf{v} + \mathbf{u}\).
    *   **Identity element of vector addition:** There exists an element \(\mathbf{0} \in V\), called the **zero vector**, such that \(\mathbf{v} + \mathbf{0} = \mathbf{v}\) for all \(\mathbf{v} \in V\).
    *   **Inverse elements of vector addition:** For every \(\mathbf{v} \in V\), there exists an element \(-\mathbf{v} \in V\), called the **additive inverse** of \(\mathbf{v}\), such that \(\mathbf{v} + (-\mathbf{v}) = \mathbf{0}\).

2.  **Compatibility of scalar multiplication with field multiplication:**
    *   \(a(b\mathbf{v}) = (ab)\mathbf{v}\).

3.  **Distributivity:**
    *   **Distributivity of scalar multiplication with respect to vector addition:** \(a(\mathbf{u} + \mathbf{v}) = a\mathbf{u} + a\mathbf{v}\).
    *   **Distributivity of scalar multiplication with respect to field addition:** \((a + b)\mathbf{v} = a\mathbf{v} + b\mathbf{v}\).

4.  **Identity element of scalar multiplication:**
    *   \(1\mathbf{v} = \mathbf{v}\), where 1 is the multiplicative identity in \(F\).

## Description

A vector space is a collection of vectors that can be added together and scaled (multiplied) by numbers from a field. It is the fundamental algebraic structure of linear algebra. The concept of a vector space abstracts the properties of geometric vectors in 2D and 3D space.

## Subfields it's part of

*   [Linear Algebra](./)
*   [Functional Analysis](../../../02_Analysis/03_Functional_Analysis/)
*   Virtually all fields of science and engineering.

## Subfields and concepts it includes

*   **Linear Subspace:** A subset of a vector space that is itself a vector space.
*   **Linear Combination:** A sum of scaled vectors.
*   **Spanning Set:** A set of vectors whose linear combinations can produce every vector in the space.
*   **Linear Independence:** A set of vectors is linearly independent if none of them can be written as a linear combination of the others.
*   **Basis:** A linearly independent spanning set. The number of vectors in a basis is the **dimension** of the vector space.
*   **Linear Transformation (or Linear Map):** A [function](../../../../00_Foundations/01_Set_Theory/Function.md) between two vector spaces that preserves the operations of vector addition and scalar multiplication.
*   **Eigenvectors and Eigenvalues:** Special vectors that are only scaled by a linear transformation.
*   **Inner Product Space:** A vector space with an additional structure called an inner product, which allows for the definition of length and angle.

## Applications

*   **Physics and Engineering:** Used to model physical quantities that have both magnitude and direction, such as force, velocity, and electromagnetic fields. Quantum mechanics is formulated in the language of vector spaces (specifically, Hilbert spaces).
*   **Computer Graphics:** Vectors and matrices are used for transformations (rotation, scaling, translation) of 3D models.
*   **Data Science and Machine Learning:** Data sets are often represented as vectors in a high-dimensional vector space. Techniques like Principal Component Analysis (PCA) rely on linear algebra.
*   **Solving Systems of Linear Equations:** Linear algebra provides the framework and tools for solving such systems.
*   **Differential Equations:** The set of solutions to a linear homogeneous differential equation forms a vector space.

## More general variants

*   **Module:** A generalization of a vector space where the scalars come from a [ring](../../01_Abstract_Algebra/01_Ring_Theory/Ring.md) instead of a field.
*   **Topological Vector Space:** A vector space that is also a topological space, with the operations being continuous.
*   **Vector Bundle:** A family of vector spaces parameterized by another space.

## More concrete variants

*   **Euclidean Space \(\mathbb{R}^n\):** The space of n-tuples of real numbers.
*   **Complex Coordinate Space \(\mathbb{C}^n\):** The space of n-tuples of complex numbers.
*   **Function Spaces:** Vector spaces where the vectors are functions (e.g., the space of continuous functions on an interval).
*   **Polynomial Spaces:** Vector spaces where the vectors are polynomials.
*   **Matrix Spaces:** The set of all \(m \times n\) matrices over a field \(F\) forms a vector space.

## Everything else it relates to

*   **Matrices:** Linear transformations between finite-dimensional vector spaces can be represented by matrices.
*   **Tensors:** A generalization of scalars, vectors, and matrices.
*   **Geometry:** Vector spaces are the building blocks of Euclidean and other geometries. Affine spaces and projective spaces are built from vector spaces.
*   **Fourier Analysis:** The study of representing functions as sums of trigonometric functions, which takes place in infinite-dimensional vector spaces.
