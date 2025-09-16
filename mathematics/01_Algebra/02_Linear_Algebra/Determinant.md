# Determinant

## Mathematical Definition

The **determinant** is a scalar value that is a function of the entries of a square [matrix](./Matrix.md). For a square matrix \(A\), the determinant is denoted \(\det(A)\), \(\det A\), or \(|A|\).

The definition of the determinant is inductive.
*   For a \(1 \times 1\) matrix, the determinant is the number itself:
    \[ \det([a]) = a \]
*   For a \(2 \times 2\) matrix, the determinant is:
    \[ \det \begin{pmatrix} a & b \\ c & d \end{pmatrix} = ad - bc \]
*   For an \(n \times n\) matrix, the determinant can be defined using the **Leibniz formula** or the **Laplace expansion**.

The **Leibniz formula** is a sum over all permutations of the matrix columns:
\[ \det(A) = \sum_{\sigma \in S_n} \text{sgn}(\sigma) \prod_{i=1}^{n} a_{i, \sigma(i)} \]
where \(S_n\) is the set of all permutations of \(\{1, 2, ..., n\}\) and \(\text{sgn}(\sigma)\) is the sign of the permutation.

The **Laplace expansion** (or cofactor expansion) expresses the determinant of a matrix in terms of the determinants of smaller sub-matrices. For any row \(i\), the expansion is:
\[ \det(A) = \sum_{j=1}^{n} (-1)^{i+j} a_{ij} M_{ij} \]
where \(M_{ij}\) is the determinant of the sub-matrix obtained by removing the \(i\)-th row and \(j\)-th column.

## Description

The determinant is a number associated with a square matrix that has many important algebraic and geometric properties. Geometrically, the absolute value of the determinant of a real matrix can be interpreted as the **scaling factor** of the linear transformation described by the matrix. It represents the volume of the parallelepiped spanned by the column vectors of the matrix. The sign of the determinant indicates whether the transformation preserves or reverses the orientation of space.

A key property is that a matrix is **invertible** if and only if its determinant is non-zero.

## Subfields it's part of

*   [Linear Algebra](./)
*   [Calculus](../../../02_Analysis/00_Calculus/) (in the change of variables formula for multiple integrals)

## Subfields and concepts it includes

*   **Minor:** The determinant of a smaller square matrix, cut down from a larger one by removing one or more of its rows and columns.
*   **Cofactor:** A signed minor.
*   **Adjugate Matrix:** The transpose of the cofactor matrix.
*   **Cramer's Rule:** A formula for the solution of a system of linear equations in terms of determinants.
*   **Characteristic Polynomial:** The determinant \(\det(A - \lambda I)\) is a polynomial in \(\lambda\), whose roots are the eigenvalues of the matrix \(A\).

## Applications

*   **Invertibility of Matrices:** A matrix has an inverse if and only if its determinant is non-zero. This is fundamental in solving systems of linear equations.
*   **Geometry:** The determinant is used to calculate the area of a parallelogram (in \(\mathbb{R}^2\)) and the volume of a parallelepiped (in \(\mathbb{R}^3\)) formed by the matrix's column vectors.
*   **Calculus:** The **Jacobian determinant** is used in the change of variables rule for multiple integrals.
*   **Eigenvalue Problems:** Determinants are used to find the eigenvalues of a matrix via the characteristic equation.
*   **Solving Systems of Linear Equations:** Cramer's rule uses determinants to find the solution.

## More general variants

*   The concept of a determinant can be extended to matrices with entries from a commutative ring.
*   In exterior algebra, the determinant of a linear transformation of an n-dimensional vector space is the scalar by which the transformation acts on the top exterior power.

## More concrete variants

*   Determinant of a \(2 \times 2\) or \(3 \times 3\) matrix.

## Everything else it relates to

*   **Eigenvalues:** The eigenvalues of a matrix are the roots of its characteristic polynomial, which is defined using a determinant.
*   **Linear Independence:** The determinant of a matrix is non-zero if and only if its column vectors (and row vectors) are linearly independent.
*   **Volume and Orientation:** The determinant provides a measure of how a linear transformation scales volume and whether it preserves orientation.
*   **Matrix Inverse:** The formula for the inverse of a matrix involves the determinant and the adjugate matrix: \(A^{-1} = \frac{1}{\det(A)} \text{adj}(A)\).
