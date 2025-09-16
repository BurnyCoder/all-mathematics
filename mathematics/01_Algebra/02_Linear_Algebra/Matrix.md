# Matrix

## Mathematical Definition

A **matrix** is a rectangular array or table of numbers, symbols, or expressions, arranged in rows and columns. Matrices are most commonly written in box brackets.

An \(m \times n\) matrix (read "m by n matrix") has \(m\) rows and \(n\) columns. The individual items in a matrix are called its **elements** or **entries**. The entry in the \(i\)-th row and \(j\)-th column of a matrix \(A\) is denoted by \(a_{ij}\) or \(A[i, j]\).

Example of a \(2 \times 3\) matrix:
\[ A = \begin{bmatrix} 1 & 9 & -13 \\ 20 & 5 & -6 \end{bmatrix} \]

Matrices can be added, subtracted, and multiplied under certain conditions.
*   **Matrix Addition:** Two matrices can be added if they have the same dimensions. The sum is a new matrix where each element is the sum of the corresponding elements of the original matrices.
*   **Scalar Multiplication:** A matrix can be multiplied by a scalar (a number from its base field). The product is a new matrix where each element is multiplied by the scalar.
*   **Matrix Multiplication:** The product of two matrices \(A\) and \(B\) is defined only if the number of columns in \(A\) is equal to the number of rows in \(B\). Matrix multiplication is generally not commutative (\(AB \neq BA\)).

## Description

Matrices are a fundamental tool in linear algebra used to represent and study **linear transformations** between vector spaces. They also provide a convenient way to represent and solve systems of linear equations.

## Subfields it's part of

*   [Linear Algebra](./)
*   [Numerical Analysis](../../../08_Applied_Mathematics/01_Numerical_Analysis/)
*   Graph Theory

## Subfields and concepts it includes

*   **Square Matrix:** A matrix with the same number of rows and columns (\(m = n\)).
*   **Identity Matrix (\(I\)):** A square matrix with ones on the main diagonal and zeros elsewhere. It is the identity element for matrix multiplication.
*   **Inverse Matrix (\(A^{-1}\)):** For a square matrix \(A\), its inverse is a matrix that, when multiplied by \(A\), yields the identity matrix. A matrix is **invertible** or **non-singular** if its inverse exists.
*   **Transpose (\(A^T\)):** A matrix obtained by swapping the rows and columns of another matrix.
*   **Determinant (\(\det(A)\)):** A scalar value that can be computed from the elements of a square matrix. A matrix is invertible if and only if its determinant is non-zero.
*   **Trace (\(\text{tr}(A)\)):** The sum of the elements on the main diagonal of a square matrix.
*   **Eigenvalues and Eigenvectors:** An eigenvector of a square matrix is a non-zero vector that, when the matrix is multiplied by it, yields a scalar multiple of itself. The scalar is the eigenvalue.
*   **Matrix Decomposition:** Factoring a matrix into a product of other matrices (e.g., LU decomposition, QR decomposition, singular value decomposition).

## Applications

*   **Solving Systems of Linear Equations:** Matrices provide a compact way to represent and solve systems of linear equations.
*   **Computer Graphics:** Used extensively to represent geometric transformations like rotation, scaling, and translation of objects in 3D space.
*   **Physics:** Used in classical mechanics, quantum mechanics (e.g., state vectors, spin matrices), optics, and electromagnetism.
*   **Graph Theory:** The **adjacency matrix** of a graph represents the connections between its vertices.
*   **Data Science and Machine Learning:** Data sets are often represented as matrices. Covariance matrices are used in statistics. Neural networks are essentially a series of matrix operations.
*   **Economics:** Used in input-output models to describe the relationships between different sectors of an economy.
*   **Cryptography:** Used in certain encryption algorithms.

## More general variants

*   **Tensor:** A generalization of scalars (rank 0), vectors (rank 1), and matrices (rank 2) to higher ranks.
*   **Matrix over a Ring:** Matrices can be defined with elements from a [ring](../../01_Abstract_Algebra/01_Ring_Theory/Ring.md) instead of a field.

## More concrete variants

*   **Row and Column Vectors:** Matrices with only one row or one column.
*   **Diagonal Matrix:** A matrix where all off-diagonal elements are zero.
*   **Symmetric Matrix:** A square matrix that is equal to its transpose (\(A = A^T\)).
*   **Orthogonal Matrix:** A square matrix whose transpose is its inverse. The columns (and rows) are orthogonal unit vectors.
*   **Hermitian Matrix:** The complex analog of a symmetric matrix.

## Everything else it relates to

*   **Linear Transformation:** Every linear transformation between finite-dimensional [vector spaces](./Vector_Space.md) can be represented by a matrix. The composition of linear transformations corresponds to matrix multiplication.
*   **Determinant:** A key property of a square matrix that determines its invertibility and provides geometric information (scaling factor of the transformation).
*   **Systems of Equations:** Matrices are the primary tool for representing and solving linear systems.
*   **Ring Theory:** The set of all \(n \times n\) square matrices over a field forms a non-commutative ring under matrix addition and multiplication.
