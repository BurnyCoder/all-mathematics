# Wave Equation

- **Mathematical Definition**: The wave equation is a second-order linear partial differential equation that describes the propagation of a variety of waves, such as sound waves, light waves, and water waves. For a scalar function $u(x_1, ..., x_n, t)$, the wave equation is:
$$ \frac{\partial^2 u}{\partial t^2} = c^2 \nabla^2 u $$
  or
$$ \frac{\partial^2 u}{\partial t^2} = c^2 \left( \frac{\partial^2 u}{\partial x_1^2} + \dots + \frac{\partial^2 u}{\partial x_n^2} \right) $$
  where $c$ is a constant representing the propagation speed of the wave, and $\nabla^2$ is the [Laplace operator](../../pure_mathematics/analysis/laplace_operator.md).

- **Description**: The wave equation is a hyperbolic partial differential equation and is a fundamental equation in classical physics. It models phenomena where disturbances travel at a finite speed. Solutions to the wave equation describe the amplitude of the wave at a given point in space and time. Unlike the heat equation, which models dissipative processes, the wave equation models conservative processes where energy is typically conserved.

- **Subfields it's part of**:
    - [Partial Differential Equations](https://en.wikipedia.org/wiki/Partial_differential_equation): It is one of the three fundamental linear second-order PDEs, along with the heat equation and Laplace's equation.
    - [Mathematical Physics](https://en.wikipedia.org/wiki/Mathematical_physics): It is central to the study of wave phenomena in physics.
    - [Acoustics](https://en.wikipedia.org/wiki/Acoustics): Describes the propagation of sound.
    - [Electromagnetism](https://en.wikipedia.org/wiki/Electromagnetism): Light waves are described by the electromagnetic wave equation, derived from Maxwell's equations.
    - [Fluid Dynamics](https://en.wikipedia.org/wiki/Fluid_dynamics): Describes surface waves in fluids.

- **Subfields and concepts it includes**:
    - [Calculus](https://en.wikipedia.org/wiki/Calculus): Utilizes second-order partial derivatives.
        - **[Partial Derivative](../../pure_mathematics/analysis/partial_derivative.md)**: The equation is formulated using partial derivatives.
    - [Fourier Analysis](https://en.wikipedia.org/wiki/Fourier_analysis): Used to solve the wave equation by decomposing solutions into a sum of sinusoidal waves.
    - [Method of characteristics](https://en.wikipedia.org/wiki/Method_of_characteristics): A technique for solving first-order PDEs, which can be extended to the wave equation. D'Alembert's solution for the 1D wave equation is a classic example.

- **Applications**:
    - **Physics**: Modeling sound waves, light waves, seismic waves, and vibrations of strings and membranes.
    - **Engineering**: Design of musical instruments, analysis of vibrations in structures, and telecommunications.
    - **Geophysics**: Studying the propagation of seismic waves through the Earth.
    - **General Relativity**: The propagation of gravitational waves is described by a form of the wave equation.

- **More Concrete Variants**:
    - **One-dimensional wave equation**: Describes waves on a string.
    - **Two-dimensional wave equation**: Describes waves on a membrane.
    - **Electromagnetic wave equation**: A vector wave equation for electric and magnetic fields.

- **More General Variants**:
    - **Inhomogeneous wave equation**: Includes a source term, representing the generation of waves.
    - **Nonlinear wave equations**: The wave speed $c$ can depend on the amplitude of the wave, leading to phenomena like shock waves (e.g., Korteweg-de Vries equation).
    - **Wave equation in curved spacetime**: Used in general relativity.

- **Related Concepts**:
    - **[Heat Equation](./heat_equation.md)**: Another fundamental PDE. The wave equation is hyperbolic, while the heat equation is parabolic. The wave equation's second-order time derivative leads to propagating solutions, while the heat equation's first-order time derivative leads to diffusive solutions.
    - **[Laplace's Equation](https://en.wikipedia.org/wiki/Laplace%27s_equation)**: An elliptic PDE that can be seen as the steady-state version of the heat equation, but is also related to the time-independent wave equation (Helmholtz equation).
    - **[Maxwell's Equations](../../physics/electromagnetism/maxwells_equations.md)**: In a vacuum, these equations can be combined to form the electromagnetic wave equation.
    - **[Schrödinger Equation](../../physics/quantum_mechanics/schrodinger_equation.md)**: Has a form similar to a wave equation, but with a first-order time derivative and a complex coefficient, leading to its unique quantum mechanical properties.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Wave_equation](https://en.wikipedia.org/wiki/Wave_equation)
