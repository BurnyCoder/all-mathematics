# Differential Equation

## Mathematical Definition

A **differential equation** is a mathematical equation that relates some [function](../../../00_Foundations/01_Set_Theory/Function.md) with its [derivatives](../../../02_Analysis/00_Calculus/Derivative.md). In applications, the functions generally represent physical quantities, the derivatives represent their rates of change, and the differential equation defines a relationship between the two.

Differential equations are categorized based on several properties:

*   **Ordinary Differential Equation (ODE):** An equation involving an unknown function of a single independent variable and its derivatives.
    *   Example (Newton's Second Law): \( F = m \frac{d^2x}{dt^2} \)
    *   Example (Simple Harmonic Oscillator): \( \frac{d^2y}{dx^2} + k^2y = 0 \)

*   **Partial Differential Equation (PDE):** An equation involving an unknown function of multiple independent variables and their partial derivatives.
    *   Example (Heat Equation): \( \frac{\partial u}{\partial t} = \alpha \nabla^2 u \)
    *   Example (Wave Equation): \( \frac{\partial^2 u}{\partial t^2} = c^2 \nabla^2 u \)

The **order** of a differential equation is the order of the highest derivative present in the equation.

A **solution** to a differential equation is a function that satisfies the equation.

## Description

Differential equations are a powerful tool for modeling and describing systems that are in a state of change. Because such relationships are ubiquitous, differential equations play a prominent role in many disciplines including engineering, physics, economics, and biology. They allow us to model a system's behavior over time by describing how it changes at any given moment.

## Subfields it's part of

*   [Differential Equations](./)
*   [Applied Mathematics](../)
*   [Calculus](../../../02_Analysis/00_Calculus/)
*   [Mathematical Modeling](../)
*   Dynamical Systems

## Subfields and concepts it includes

*   **Initial Value Problems (IVPs) and Boundary Value Problems (BVPs):** Finding a specific solution to a differential equation that also satisfies certain initial or boundary conditions.
*   **Linear vs. Nonlinear Differential Equations:** Linear equations are those for which the solution set forms a vector space. Nonlinear equations often exhibit complex behaviors like chaos.
*   **Homogeneous vs. Inhomogeneous Equations**
*   **Analytical Solutions:** Finding exact, closed-form solutions.
*   **Numerical Methods:** Approximating solutions using computational algorithms (e.g., Euler's method, Runge-Kutta methods). This is the focus of [Numerical Analysis](../01_Numerical_Analysis/).
*   **Existence and Uniqueness of Solutions:** Theorems that guarantee whether a solution exists and if it is unique.
*   **Qualitative Analysis:** Studying the behavior of solutions without finding them explicitly.

## Applications

*   **Physics:**
    *   **Classical Mechanics:** Newton's laws of motion, Lagrange's equations, Hamilton's equations.
    *   **Electromagnetism:** Maxwell's equations.
    *   **General Relativity:** Einstein's field equations.
    *   **Quantum Mechanics:** Schrödinger equation.
    *   **Thermodynamics:** Heat equation.
*   **Engineering:** Modeling electrical circuits, the motion of mechanical systems, fluid flow (Navier-Stokes equations), and heat transfer.
*   **Biology:** Modeling population dynamics (Lotka-Volterra equations), the spread of diseases (SIR model), and nerve impulse propagation.
*   **Economics and Finance:** Modeling stock price fluctuations (Black-Scholes equation) and economic growth.
*   **Chemistry:** Modeling chemical reaction rates.

## More general variants

*   **Stochastic Differential Equation (SDE):** A differential equation in which one of the terms is a stochastic process, meaning the solutions are themselves stochastic processes.
*   **Delay Differential Equation (DDE):** A differential equation where the derivative of the function at a certain time depends on the solution at previous times.
*   **Differential-Algebraic Equation (DAE):** A differential equation that also involves algebraic constraints.
*   **Integral Equations:** Equations where the unknown function appears under an integral sign.

## More concrete variants

*   **First-Order Linear ODEs**
*   **Second-Order Linear ODEs with Constant Coefficients** (e.g., for simple harmonic motion)
*   **Separable Equations:** A type of ODE that can be solved by separating variables and integrating.
*   **Exact Equations**

## Everything else it relates to

*   **Calculus:** The language of differential equations is the language of derivatives and integrals. The **Fundamental Theorem of Calculus** is the solution to the simplest possible differential equation, \(dy/dx = f(x)\).
*   **Linear Algebra:** The theory of linear differential equations heavily relies on linear algebra, for example, the solution space of a linear homogeneous ODE is a vector space.
*   **Complex Analysis:** Can be used to find solutions to linear ODEs.
*   **Dynamical Systems and Chaos Theory:** The study of the long-term qualitative behavior of systems described by differential equations.
