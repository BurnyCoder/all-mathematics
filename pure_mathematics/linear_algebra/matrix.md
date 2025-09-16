# Matrix

- **Mathematical Definition**: A matrix is a rectangular array of numbers, symbols, or expressions, arranged in rows and columns. For example, the dimensions of the matrix below are 2 × 3 (read "two by three"), because there are two rows and three columns:
  \\( \begin{bmatrix} 1 & 9 & -13 \\ 20 & 5 & -6 \end{bmatrix} \\)
  Matrices of the same size can be added or subtracted element by element. The rule for **matrix multiplication**, however, is that two matrices can be multiplied only if the number of columns in the first matrix equals the number of rows in the second matrix.

- **Description**: Matrices are one of the most fundamental tools in linear algebra. They are used to represent and manipulate data in a compact form, solve systems of linear equations, and, most importantly, represent [linear transformations](./linear_transformation.md) between finite-dimensional vector spaces. Many of their properties, such as the determinant and eigenvalues, reveal deep information about the linear transformation they represent.

- **Subfields it's part of**:
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra)
    - [Pure Mathematics](https://en.wikipedia.org/wiki/Pure_mathematics)

- **Subfields and concepts it includes**:
    - **Matrix Operations**: Addition, scalar multiplication, and matrix multiplication.
    - **Transpose**: An operator which flips a matrix over its diagonal.
    - **Determinant**: A scalar value that can be computed from the elements of a square matrix and encodes certain properties of the linear transformation.
    - **Inverse**: A matrix that, when multiplied by the original matrix, yields the identity matrix.
    - **Eigenvalues and Eigenvectors**: As applied to square matrices, these reveal the scaling factors and directions of the transformation.
    - **Matrix Decomposition**: Factoring a matrix into a product of matrices (e.g., LU decomposition, QR decomposition, eigendecomposition).

- **Applications**:
    - **Computer Graphics**: Used extensively to represent transformations like rotation, scaling, and translation of 3D objects.
    - **Physics**: Used in quantum mechanics (state vectors, operators), optics, and electronics.
    - **Computer Science**: Representing graphs (adjacency matrix), solving systems of equations, and in machine learning (e.g., weight matrices in neural networks).
    - **Statistics**: Used in statistical analysis, for example, to represent covariance matrices.
    - **Engineering**: Solving systems of linear equations that arise in circuit analysis, mechanical systems, and more.

- **More Concrete Variants**:
    - **Square Matrix**: A matrix with the same number of rows and columns.
    - **Identity Matrix**: A square matrix with ones on the main diagonal and zeros elsewhere.
    - **Symmetric Matrix**: A square matrix that is equal to its transpose.
    - **Diagonal Matrix**: A matrix in which the entries outside the main diagonal are all zero.

- **More General Variants**:
    - **Tensor**: A generalization of matrices to higher dimensions.

- **Related Concepts**:
    - **[Linear Transformation](./linear_transformation.md)**: Every matrix represents a linear transformation, and every linear transformation between finite-dimensional vector spaces can be represented by a matrix.
    - **[Vector Space](./vector_space.md)**: Matrices operate on vectors.
    - **System of Linear Equations**: A set of linear equations can be compactly represented and solved using matrices.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Matrix_(mathematics)](https://en.wikipedia.org/wiki/Matrix_(mathematics))
