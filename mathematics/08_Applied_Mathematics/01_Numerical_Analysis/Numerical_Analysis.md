# Numerical Analysis

## Mathematical Definition

**Numerical analysis** is the study of algorithms that use numerical approximation (as opposed to symbolic manipulation) for the problems of mathematical analysis. It involves the design, analysis, and implementation of algorithms for solving continuous mathematical problems.

The core idea is to replace a complex, continuous problem with a simpler, discrete problem that can be solved computationally, and to quantify the error between the solution of the discrete problem and the solution of the original continuous problem.

## Description

Numerical analysis is the branch of mathematics that deals with the development and use of numerical methods to solve problems. In practice, many mathematical problems arising from science and engineering are too difficult or impossible to solve exactly (analytically). Numerical analysis provides the tools to find approximate, but accurate, solutions to these problems using computers. The field is as much concerned with the accuracy and efficiency of the methods as it is with finding a solution.

## Subfields it's part of

*   [Applied Mathematics](../)
*   Computer Science
*   Data Science

## Subfields and concepts it includes

*   **Floating-Point Arithmetic:** The system of representing real numbers on a computer, which has finite precision and can lead to **round-off error**.
*   **Root Finding:** Algorithms for finding roots of functions (e.g., Newton's method, bisection method).
*   **Systems of Linear Equations:** Iterative and direct methods for solving large systems of linear equations (e.g., LU decomposition, Jacobi method, Gauss-Seidel method).
*   **Interpolation and Extrapolation:** Estimating the value of a function at points between or outside a set of known data points (e.g., polynomial interpolation, splines).
*   **Numerical Integration (Quadrature):** Methods for approximating definite integrals (e.g., Newton-Cotes formulas like the Trapezoidal rule and Simpson's rule).
*   **Numerical Differentiation:** Approximating the derivative of a function.
*   **Numerical Solutions to Differential Equations:**
    *   **Ordinary Differential Equations (ODEs):** Methods like Euler's method and the Runge-Kutta family of methods.
    *   **Partial Differential Equations (PDEs):** Methods like the Finite Difference Method, Finite Element Method (FEM), and Finite Volume Method.
*   **Optimization:** Finding the maximum or minimum of a function.
*   **Eigenvalue Problems:** Numerical algorithms for finding eigenvalues and eigenvectors of matrices.
*   **Error Analysis:** The study of the different types of errors involved in numerical computation, including round-off error and **truncation error** (the error from approximating a continuous process with a discrete one).

## Applications

*   **Engineering:** The Finite Element Method (FEM) is used extensively in structural analysis, heat transfer, and fluid dynamics to solve complex PDEs that model physical systems.
*   **Weather Forecasting:** Numerical weather prediction models solve systems of PDEs that describe the atmosphere.
*   **Finance:** Used to price financial derivatives and manage risk by solving stochastic differential equations.
*   **Data Science and Machine Learning:** Core algorithms in machine learning, such as training neural networks (gradient descent is a numerical optimization technique) and performing linear regression, are numerical methods.
*   **Computer Graphics and Animation:** Simulating physical phenomena like cloth, smoke, and water involves numerically solving differential equations.
*   **Astronomy:** Calculating the trajectories of celestial bodies.

## More general variants

*   **Scientific Computing:** A broader field that includes numerical analysis as well as other aspects of using computers for scientific inquiry, such as data visualization and high-performance computing.

## More concrete variants

*   **Specific algorithms** like Newton's method, Runge-Kutta methods, Fast Fourier Transform (FFT).

## Everything else it relates to

*   **Linear Algebra:** Many problems in numerical analysis are ultimately reduced to problems in linear algebra, such as solving large systems of linear equations.
*   **Calculus:** The core problems of calculus (differentiation, integration, solving differential equations) are the main subjects of numerical analysis.
*   **Computer Architecture:** The performance of numerical algorithms can be highly dependent on the underlying hardware.
*   **Complexity Theory:** The efficiency of numerical algorithms is a primary concern.
