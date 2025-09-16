# Taylor Series

## Mathematical Definition

A **Taylor series** is a representation of a [function](../../../../00_Foundations/01_Set_Theory/Function.md) as an infinite sum of terms, where each term is calculated from the values of the function's [derivatives](./Derivative.md) at a single point.

For a real or complex-valued function \(f(x)\) that is infinitely differentiable at a real or complex number \(a\), the Taylor series of the function centered at \(a\) is the power series:
\[ f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!} (x-a)^n = f(a) + \frac{f'(a)}{1!}(x-a) + \frac{f''(a)}{2!}(x-a)^2 + \frac{f'''(a)}{3!}(x-a)^3 + \cdots \]
where \(f^{(n)}(a)\) denotes the \(n\)-th derivative of \(f\) evaluated at the point \(a\), and \(n!\) is the factorial of \(n\).

If a function is equal to its Taylor series in a neighborhood of \(a\), it is called an **analytic function**.

A **Maclaurin series** is a special case of a Taylor series where the expansion is centered at \(a = 0\).

The finite version of the Taylor series is the **Taylor polynomial**. Taylor's theorem gives quantitative estimates on the error in this approximation.

## Description

The Taylor series provides a way to approximate a complicated function with a simpler polynomial function. The idea is that if you know enough information about a function at a single point (its value, its rate of change, its rate of change of its rate of change, etc.), you can construct a polynomial that mimics the function's behavior in the neighborhood of that point. For many well-behaved functions (analytic functions), this polynomial approximation becomes exact as you add an infinite number of terms.

## Subfields it's part of

*   [Calculus](./)
*   [Real Analysis](../01_Real_Analysis/)
*   [Complex Analysis](../02_Complex_Analysis/)
*   [Numerical Analysis](../../../08_Applied_Mathematics/01_Numerical_Analysis/)

## Subfields and concepts it includes

*   **Power Series:** An infinite series of the form \(\sum a_n (x-c)^n\).
*   **Radius of Convergence:** The radius of the largest disk in which a power series converges.
*   **Analytic Function:** A function that is locally given by a convergent power series.
*   **Taylor's Theorem and Remainder:** Provides an estimate of the error between a function and its Taylor polynomial approximation.

## Applications

*   **Approximation of Functions:** Taylor polynomials are used to approximate functions, which is particularly useful in numerical methods and physics when the exact value of a function is difficult to compute.
*   **Physics:** Used extensively to approximate complex potentials and equations of motion. For example, in mechanics, the potential energy function is often approximated by a Taylor series to analyze small oscillations around an equilibrium point.
*   **Numerical Analysis:** Forms the basis for many numerical methods for solving differential equations and performing integration.
*   **Proof of Euler's Formula:** One of the most elegant proofs of Euler's formula (\(e^{ix} = \cos x + i \sin x\)) comes from comparing the Maclaurin series for the exponential, sine, and cosine functions.
*   **Optimization:** In methods like Newton's method, functions are approximated by their second-degree Taylor polynomials to find maxima or minima.

## More general variants

*   **Laurent Series:** A generalization of the Taylor series that allows for negative powers of \((x-a)\). It is used in complex analysis to describe functions near a singularity.
*   **Puiseux Series:** A generalization of power series that allows for fractional exponents.
*   **Taylor Series in Multiple Variables:** The concept can be extended to functions of multiple variables.

## More concrete variants

*   **Maclaurin Series (Taylor series at a=0)** for common functions:
    *   **Exponential Function:** \(e^x = \sum_{n=0}^{\infty} \frac{x^n}{n!} = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots\)
    *   **Sine Function:** \(\sin x = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n+1}}{(2n+1)!} = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \cdots\)
    *   **Cosine Function:** \(\cos x = \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n}}{(2n)!} = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots\)
    *   **Geometric Series:** \(\frac{1}{1-x} = \sum_{n=0}^{\infty} x^n = 1 + x + x^2 + x^3 + \cdots\) (for \(|x|<1\))

## Everything else it relates to

*   **Derivatives:** The coefficients of the Taylor series are determined by the derivatives of the function.
*   **Polynomials:** The Taylor series represents a function as an "infinite polynomial".
*   **Complex Analysis:** The theory of Taylor series is particularly powerful for complex functions. A complex function that is differentiable once is automatically infinitely differentiable and analytic.
*   **Linear Approximation:** The first-degree Taylor polynomial, \(f(a) + f'(a)(x-a)\), is the best linear approximation of the function near \(a\).
