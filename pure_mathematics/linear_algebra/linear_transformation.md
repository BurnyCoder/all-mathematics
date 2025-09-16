# Linear Transformation

- **Mathematical Definition**: A linear transformation (or linear map) is a function between two [vector spaces](./vector_space.md) $V$ and $W$ over the same [field](../algebra/field.md) $F$ that preserves the operations of vector addition and scalar multiplication. A function $T: V \to W$ is a linear transformation if for any two vectors $\mathbf{u}, \mathbf{v} \in V$ and any scalar $c \in F$, the following two conditions are satisfied:
    1.  **Additivity**: $T(\mathbf{u} + \mathbf{v}) = T(\mathbf{u}) + T(\mathbf{v})$
    2.  **Homogeneity of degree 1**: $T(c\mathbf{u}) = cT(\mathbf{u})$

- **Description**: Linear transformations are the most important functions in linear algebra. They represent transformations of space that preserve lines and the origin. Examples include rotations, reflections, scaling, and shearing. In finite-dimensional vector spaces, every linear transformation can be represented by a **matrix**.

- **Subfields it's part of**:
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra)
    - [Abstract Algebra](https://en.wikipedia.org/wiki/Abstract_algebra)

- **Subfields and concepts it includes**:
    - **Kernel (or Null Space)**: The set of all vectors in the domain that are mapped to the zero vector.
    - **Image (or Range)**: The set of all possible output vectors in the codomain.
    - **Rank-Nullity Theorem**: A fundamental theorem that relates the dimensions of the kernel and image of a linear transformation.
    - **Eigenvector and Eigenvalue**: An eigenvector of a linear transformation is a non-zero vector that changes at most by a scalar factor (the eigenvalue) when that linear transformation is applied to it.

- **Applications**:
    - **Computer Graphics**: Used to transform 3D models (rotation, scaling, projection onto a 2D screen).
    - **Machine Learning**: Many machine learning models, including layers in neural networks, are linear transformations.
    - **Physics**: Used in quantum mechanics to represent operators (observables) and in classical mechanics to describe transformations of coordinate systems.
    - **Engineering**: Used in signal processing (e.g., Fourier transform) and control systems.

- **More Concrete Variants**:
    - **Rotation Matrix**: A matrix representing a rotation in Euclidean space.
    - **Projection**: A transformation that maps a space onto a subspace.
    - **Linear Functional**: A linear transformation from a vector space to its field of scalars.

- **More General Variants**:
    - **Affine Transformation**: A transformation that is a combination of a linear transformation and a translation. It does not necessarily preserve the origin.
    - **Morphism in Category Theory**: A linear transformation is a morphism in the category of vector spaces (**Vect**).

- **Related Concepts**:
    - **[Vector Space](./vector_space.md)**: The domain and codomain of a linear transformation are vector spaces.
    - **Matrix**: A matrix provides a concrete representation of a linear transformation between finite-dimensional vector spaces.
    - **Eigenvalues and Eigenvectors**: Special vectors and scalars that characterize the behavior of a linear transformation.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Linear_map](https://en.wikipedia.org/wiki/Linear_map)
