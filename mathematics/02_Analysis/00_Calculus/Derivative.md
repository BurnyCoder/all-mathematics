# Derivative

## Mathematical Definition

The **derivative** of a function of a real variable measures the sensitivity to change of the function value (output value) with respect to a change in its argument (input value). It is a fundamental tool of calculus.

For a function \(f(x)\), the derivative at a point \(a\) in its domain is defined by the [limit](./Limit.md) of a difference quotient:
\[ f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h} \]
If this limit exists, the function is said to be **differentiable** at \(a\). The function \(f'(x)\), which gives the value of the derivative for any \(x\) where it is defined, is called the **derivative function** or simply the **derivative** of \(f\).

Other common notations for the derivative of \(y = f(x)\) include:
\[ \frac{dy}{dx}, \quad \frac{df}{dx}, \quad Df(x), \quad D_x f(x) \]

Geometrically, the derivative at a point is the **slope of the tangent line** to the graph of the function at that point.

## Description

The derivative represents the **instantaneous rate of change** of a function. It generalizes the simple notion of the slope of a line to more complex functions. The process of finding a derivative is called **differentiation**.

## Subfields it's part of

*   [Calculus](./)
*   [Differential Equations](../../../08_Applied_Mathematics/00_Differential_Equations/)
*   [Differential Geometry](../../../03_Geometry/01_Differential_Geometry/)
*   [Real Analysis](../01_Real_Analysis/)
*   [Complex Analysis](../02_Complex_Analysis/)

## Subfields and concepts it includes

*   **Rules of Differentiation:**
    *   **Power Rule, Product Rule, Quotient Rule, Chain Rule**
*   **Higher-Order Derivatives:** The second derivative, third derivative, etc., obtained by differentiating repeatedly.
*   **Partial Derivative:** A generalization for functions of multiple variables, where the derivative is taken with respect to one variable while holding the others constant.
*   **Total Derivative:** Another generalization for functions of multiple variables that accounts for changes in all variables simultaneously.
*   **Critical Points, Maxima, and Minima:** Points where the derivative is zero or undefined are critical for finding local extrema of a function.
*   **Mean Value Theorem:** A fundamental result in calculus that relates the average rate of change over an interval to the instantaneous rate of change at some point in that interval.

## Applications

*   **Physics:**
    *   **Velocity:** The derivative of position with respect to time.
    *   **Acceleration:** The derivative of velocity with respect to time.
    *   Many physical laws (e.g., Newton's second law, Maxwell's equations) are expressed as **differential equations**, which involve derivatives.
*   **Optimization:** Finding the maximum or minimum value of a function, which has applications in economics (maximizing profit, minimizing cost), engineering (optimizing design), and other fields.
*   **Approximation:** Using the tangent line (a linear approximation based on the derivative) to approximate the value of a function near a point (Taylor series).
*   **Curve Sketching:** Using the first and second derivatives to determine the shape of a function's graph (increasing/decreasing intervals, concavity).
*   **Machine Learning:** The process of training neural networks relies on an algorithm called backpropagation, which uses derivatives (gradients) to update the network's parameters (gradient descent).

## More general variants

*   **Fréchet Derivative and Gâteaux Derivative:** Generalizations of the derivative for functions between Banach spaces (used in functional analysis).
*   **Covariant Derivative:** A generalization used in differential geometry that takes into account the curvature of a space.
*   **Weak Derivative:** A concept from the theory of distributions used to define derivatives for functions that are not differentiable in the classical sense.

## More concrete variants

*   **Derivative of a polynomial**
*   **Derivative of trigonometric, exponential, and logarithmic functions**

## Everything else it relates to

*   **Integral:** The **Fundamental Theorem of Calculus** establishes that differentiation and integration are inverse operations.
*   **Continuity:** If a function is differentiable at a point, it must also be continuous at that point. The converse is not true.
*   **Linear Approximation:** The derivative provides the best linear approximation of a function at a given point.
*   **Rate of Change:** The derivative is the mathematical formalization of the concept of an instantaneous rate of change.
