# Heat Equation

- **Mathematical Definition**: The heat equation is a second-order partial differential equation that describes how the distribution of some quantity (such as heat) evolves over time in a solid medium. For a function $u(x, y, z, t)$ of three spatial variables and the time variable $t$, the heat equation is:
$$ \frac{\partial u}{\partial t} - \alpha \nabla^2 u = 0 $$
  or
$$ \frac{\partial u}{\partial t} = \alpha \left( \frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2} \right) $$
  where $\alpha$ is a positive constant known as thermal diffusivity, and $\nabla^2$ is the [Laplace operator](../../pure_mathematics/analysis/laplace_operator.md).

- **Description**: The heat equation is a fundamental equation in physics and mathematics for modeling diffusion processes. It describes the flow of heat in a material, but it can also be used to model other phenomena where a quantity diffuses through a medium, such as the diffusion of particles in a fluid (Brownian motion) or the diffusion of information in a social network. The solutions to the heat equation are functions that describe the temperature at each point in the medium at each moment in time.

- **Subfields it's part of**:
    - [Partial Differential Equations](https://en.wikipedia.org/wiki/Partial_differential_equation): It is one of the three fundamental linear second-order PDEs, alongside the wave equation and Laplace's equation.
    - [Mathematical Physics](https://en.wikipedia.org/wiki/Mathematical_physics): It is a core equation in the study of physical phenomena.
    - [Thermodynamics](https://en.wikipedia.org/wiki/Thermodynamics): It describes heat transfer.
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory): It is related to the study of Brownian motion and other stochastic processes.

- **Subfields and concepts it includes**:
    - [Calculus](https://en.wikipedia.org/wiki/Calculus): Utilizes partial derivatives to express the rate of change of temperature in space and time.
        - **[Partial Derivative](../../pure_mathematics/analysis/partial_derivative.md)**: The equation is formulated using partial derivatives.
    - [Fourier Analysis](https://en.wikipedia.org/wiki/Fourier_analysis): Fourier series and Fourier transforms are essential tools for solving the heat equation on finite and infinite domains.
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra): The principle of superposition, a consequence of linearity, allows for the construction of complex solutions by summing simpler ones. Eigenfunction expansions are used to solve it.

- **Applications**:
    - **Physics**: Modeling heat conduction in solids, liquids, and gases.
    - **Chemistry**: Describing the diffusion of chemical reactants.
    - **Biology**: Modeling the diffusion of substances across cell membranes.
    - **Finance**: The Black-Scholes equation for option pricing is a variant of the heat equation.
    - **Image Processing**: Used for noise reduction and image enhancement, where pixel intensity is treated like temperature.

- **More Concrete Variants**:
    - **One-dimensional heat equation**: Describes heat flow in a thin rod.
    - **Heat equation in cylindrical/spherical coordinates**: Used for problems with corresponding symmetries.

- **More General Variants**:
    - **Inhomogeneous heat equation**: Includes a source term, representing heat being generated or removed.
    - **Nonlinear heat equations**: The thermal diffusivity $\alpha$ may depend on temperature, leading to a nonlinear equation.
    - **Convection-diffusion equation**: Includes a term for transport of heat by fluid flow (convection).

- **Related Concepts**:
    - **[Wave Equation](./wave_equation.md)**: Another fundamental PDE that describes wave propagation instead of diffusion. The key difference is the first-order time derivative in the heat equation versus the second-order in the wave equation.
    - **[Laplace's Equation](https://en.wikipedia.org/wiki/Laplace%27s_equation)**: Describes the steady-state temperature distribution, where the temperature is no longer changing with time ($\partial u / \partial t = 0$).
    - **[Brownian motion](https://en.wikipedia.org/wiki/Brownian_motion)**: The heat equation can be derived from the random walk of individual particles.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Heat_equation](https://en.wikipedia.org/wiki/Heat_equation)
