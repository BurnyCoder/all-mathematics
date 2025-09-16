# Integral

## Mathematical Definition

The **integral** is another fundamental concept of calculus, alongside the [derivative](./Derivative.md). Integration can be introduced in two main ways: as the **indefinite integral** (or antiderivative) and as the **definite integral**.

### Indefinite Integral (Antiderivative)

The indefinite integral of a function \(f(x)\) is a differentiable function \(F(x)\) whose derivative is equal to the original function \(f(x)\).
\[ F'(x) = f(x) \]
This is denoted by:
\[ \int f(x) \,dx = F(x) + C \]
The constant \(C\) is called the **constant of integration**, and it is necessary because the derivative of a constant is zero. The process of finding an antiderivative is called **antidifferentiation** or **indefinite integration**.

### Definite Integral

The definite integral of a function \(f(x)\) over an interval \([a, b]\) is the net signed area of the region in the xy-plane bounded by the graph of \(f\), the x-axis, and the vertical lines \(x = a\) and \(x = b\). The area above the x-axis adds to the total, and the area below the x-axis subtracts from the total.

It is defined formally as the [limit](./Limit.md) of a Riemann sum:
\[ \int_{a}^{b} f(x) \,dx = \lim_{n \to \infty} \sum_{i=1}^{n} f(x_i^*) \Delta x \]
where the interval \([a, b]\) is partitioned into \(n\) subintervals of width \(\Delta x\), and \(x_i^*\) is a sample point in the \(i\)-th subinterval. If this limit exists, the function is said to be **integrable** on \([a, b]\).

The **Fundamental Theorem of Calculus** connects the two concepts. It states that if \(F\) is an antiderivative of \(f\), then:
\[ \int_{a}^{b} f(x) \,dx = F(b) - F(a) \]

## Description

The integral can be thought of as a way of accumulating quantities. It generalizes the concept of summation. The definite integral calculates a total accumulation (like total distance traveled from a varying velocity), while the indefinite integral reverses the process of differentiation.

## Subfields it's part of

*   [Calculus](./)
*   [Real Analysis](../01_Real_Analysis/)
*   [Complex Analysis](../02_Complex_Analysis/)
*   [Differential Equations](../../../08_Applied_Mathematics/00_Differential_Equations/)
*   [Measure Theory](../)

## Subfields and concepts it includes

*   **Riemann Integral:** The standard definition taught in introductory calculus.
*   **Lebesgue Integral:** A more powerful generalization of the Riemann integral, central to measure theory.
*   **Integration Techniques:** (e.g., integration by substitution, integration by parts, partial fractions).
*   **Improper Integrals:** Integrals where the interval of integration is infinite or the function is unbounded.
*   **Multiple Integrals:** Integrals of functions of multiple variables, used to calculate volume, surface area, etc.
*   **Line Integrals and Surface Integrals:** Integrals taken along curves and surfaces.

## Applications

*   **Area and Volume:** Calculating areas under curves, areas between curves, and volumes of solids.
*   **Physics:**
    *   **Work:** The work done by a variable force is calculated by an integral.
    *   **Center of Mass:** The coordinates of the center of mass of an object are found using integrals.
    *   **Electricity and Magnetism:** Integrals are used extensively (e.g., Gauss's law, Ampère's law).
*   **Probability and Statistics:** The probability of a continuous random variable falling within a certain range is the integral of its probability density function.
*   **Economics:** Calculating consumer surplus and producer surplus.
*   **Accumulation of Quantities:** Finding the total change in a quantity given its rate of change (e.g., total water leaked from a tank, total population growth).

## More general variants

*   **Lebesgue–Stieltjes integral:** A generalization of both the Riemann-Stieltjes and Lebesgue integrals.
*   **Path Integral:** A concept from quantum mechanics that generalizes the action principle of classical mechanics. It involves integrating over a space of all possible paths.
*   **Itô Integral and Stratonovich Integral:** Used in the study of stochastic processes.

## More concrete variants

*   **Integral of a polynomial**
*   **Integral of standard functions (trigonometric, exponential, etc.)**

## Everything else it relates to

*   **Derivative:** The **Fundamental Theorem of Calculus** establishes integration as the inverse operation of differentiation.
*   **Summation:** The definite integral is the limit of a summation process (Riemann sums).
*   **Measure Theory:** The Lebesgue integral provides a more general and powerful framework for integration, based on the concept of measure.
*   **Differential Forms:** In differential geometry, integration is generalized to the integration of differential forms on manifolds.
