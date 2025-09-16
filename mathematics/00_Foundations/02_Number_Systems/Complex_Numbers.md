# Complex Numbers

## Mathematical Definition

The **complex numbers**, denoted by \(\mathbb{C}\), are the set of numbers of the form \(a + bi\), where \(a\) and \(b\) are [real numbers](./Real_Numbers.md) and \(i\) is the **imaginary unit**, defined by the property \(i^2 = -1\).

\[ \mathbb{C} = \{a + bi \mid a, b \in \mathbb{R}\} \]

*   The real number \(a\) is called the **real part** of the complex number.
*   The real number \(b\) is called the **imaginary part** of the complex number.

A complex number can be viewed as an ordered pair of real numbers \((a, b)\), which corresponds to a point in the **complex plane**.

Addition and multiplication of complex numbers are defined as:
*   \((a + bi) + (c + di) = (a + c) + (b + d)i\)
*   \((a + bi) \cdot (c + di) = (ac - bd) + (ad + bc)i\)

## Description

Complex numbers extend the real numbers by introducing the imaginary unit \(i\). This allows for solutions to polynomial equations that have no real solutions, such as \(x^2 + 1 = 0\). The set of complex numbers is an **algebraically closed field**, a property stated by the **Fundamental Theorem of Algebra**.

## Subfields it's part of

*   [Number Systems](./)
*   [Algebra](../../../01_Algebra/)
*   [Complex Analysis](../../../02_Analysis/02_Complex_Analysis/)
*   [Geometry](../../../03_Geometry/)

## Subfields and concepts it includes

*   **Real and Imaginary Parts**
*   **Complex Plane (or Argand Diagram)**
*   **Modulus (or Absolute Value):** \(|a + bi| = \sqrt{a^2 + b^2}\). This is the distance from the origin to the point \((a, b)\) in the complex plane.
*   **Complex Conjugate:** The conjugate of \(a + bi\) is \(a - bi\).
*   **Polar Form:** A complex number can be written in polar form \(r(\cos \theta + i \sin \theta)\), where \(r\) is the modulus and \(\theta\) is the argument (angle).
*   **Euler's Formula:** \(e^{i\theta} = \cos \theta + i \sin \theta\). This connects the exponential function with trigonometric functions.
*   **Field Structure:** The complex numbers form an algebraically closed field.

## Applications

*   **Engineering and Physics:** Essential in electrical engineering (analyzing AC circuits), quantum mechanics, fluid dynamics, and signal processing.
*   **Mathematics:** Fundamental in many areas, especially complex analysis, number theory, and algebraic geometry. The study of fractals (like the Mandelbrot set) is based on complex numbers.
*   **Solving Polynomial Equations:** The Fundamental Theorem of Algebra guarantees that any non-constant single-variable polynomial with complex coefficients has at least one complex root.
*   **Geometry:** Used to describe transformations in the plane.

## More general variants

*   **Quaternions (\(\mathbb{H}\)):** An extension of complex numbers with three imaginary units. They are not commutative.
*   **Octonions (\(\mathbb{O}\)):** An extension of quaternions. They are not associative.
*   **Clifford Algebras:** A further generalization.

## More concrete variants

*   [Real Numbers](./Real_Numbers.md) (complex numbers with an imaginary part of 0)
*   **Imaginary Numbers** (complex numbers with a real part of 0)
*   **Gaussian Integers** (complex numbers \(a+bi\) where \(a, b\) are integers)
*   **Roots of Unity:** Complex numbers that, when raised to some integer power \(n\), equal 1.

## Everything else it relates to

*   **Fundamental Theorem of Algebra:** States that the field of complex numbers is algebraically closed.
*   **Geometry of the Complex Plane:** Operations on complex numbers have geometric interpretations (e.g., multiplication is a rotation and scaling).
*   **Riemann Sphere:** An extension of the complex plane with a point at infinity.
*   **Vector Spaces:** The complex numbers form a two-dimensional vector space over the real numbers.
