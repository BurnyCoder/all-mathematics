# Eigenvectors and Eigenvalues

- **Mathematical Definition**: Let \\(T: V \to V\\) be a [linear transformation](./linear_transformation.md) on a [vector space](./vector_space.md) \\(V\\). A non-zero vector \\(\mathbf{v} \in V\\) is an **eigenvector** of \\(T\\) if there exists a scalar \\(\lambda\\) such that:
  \\( T(\mathbf{v}) = \lambda\mathbf{v} \\)
  The scalar \\(\lambda\\) is called the **eigenvalue** corresponding to the eigenvector \\(\mathbf{v}\\). For a finite-dimensional vector space, \\(T\\) can be represented by a square [matrix](./matrix.md) \\(A\\), and the equation becomes:
  \\( A\mathbf{v} = \lambda\mathbf{v} \\)

- **Description**: Eigenvectors are the special vectors of a linear transformation that are not knocked off their span by the transformation; their direction is only stretched or shrunk by a factor, the eigenvalue. Finding the eigenvectors and eigenvalues of a transformation is often a crucial step in understanding its properties. It is like finding the "axes" of the transformation.

- **Subfields it's part of**:
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra)
    - [Spectral Theory](https://en.wikipedia.org/wiki/Spectral_theory)

- **Subfields and concepts it includes**:
    - **Characteristic Polynomial**: A polynomial whose roots are the eigenvalues of a matrix.
    - **Eigenspace**: The set of all eigenvectors corresponding to a particular eigenvalue, together with the zero vector.
    - **Diagonalization**: The process of finding a basis of eigenvectors for a vector space, which allows the transformation to be represented by a simple diagonal matrix.
    - **Spectral Theorem**: A theorem that provides conditions under which a linear transformation can be diagonalized.

- **Applications**:
    - **Quantum Mechanics**: The Hamiltonian operator acts on state vectors, and its eigenvalues represent the possible energy levels of the system.
    - **Mechanical Engineering**: Used in the analysis of vibrations and the stability of structures. The eigenvalues correspond to the natural frequencies of vibration.
    - **Machine Learning**: Principal Component Analysis (PCA), a widely used dimensionality reduction technique, is found by computing the eigenvectors of the covariance matrix of the data.
    - **Google's PageRank Algorithm**: The PageRank of a webpage is the entry in the dominant eigenvector of the web's link matrix.
    - **Facial Recognition**: Eigenfaces, a method for facial recognition, uses eigenvectors of a set of face images.

- **More Concrete Variants**:
    - Eigenvectors and eigenvalues can be real or complex numbers.

- **More General Variants**:
    - **Spectral Theory**: A generalization of the concepts of eigenvalues and eigenvectors to operators on infinite-dimensional spaces.

- **Related Concepts**:
    - **[Linear Transformation](./linear_transformation.md)**: Eigenvectors and eigenvalues characterize linear transformations.
    - **[Matrix](./matrix.md)**: The standard computational approach to finding eigenvalues and eigenvectors involves matrices.
    - **Determinant**: The characteristic polynomial is found using the determinant.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors](https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors)
