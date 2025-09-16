# Navier-Stokes Equations

- **Mathematical Definition**: The Navier-Stokes equations are a set of non-linear partial differential equations that describe the motion of viscous fluid substances. The general form of the equations for an incompressible fluid is:
$$ \rho \left( \frac{\partial \mathbf{v}}{\partial t} + (\mathbf{v} \cdot \nabla) \mathbf{v} \right) = -\nabla p + \mu \nabla^2 \mathbf{v} + \mathbf{f} $$
  This is a vector equation representing the conservation of momentum. It is often paired with the continuity equation for incompressible flow, representing conservation of mass:
$$ \nabla \cdot \mathbf{v} = 0 $$
  Here:
    - $\mathbf{v}$ is the fluid velocity vector.
    - $\rho$ is the fluid density.
    - $p$ is the pressure.
    - $\mu$ is the dynamic viscosity.
    - $\mathbf{f}$ represents external body forces (like gravity).
    - $\nabla$ is the del operator, representing the gradient and divergence.

- **Description**: The Navier-Stokes equations are the cornerstone of fluid dynamics. They are essentially Newton's second law of motion applied to a fluid element, accounting for forces including pressure, viscosity, and external influences. The equations are notoriously difficult to solve; their non-linearity (from the $(\mathbf{v} \cdot \nabla) \mathbf{v}$ term) leads to the complex and chaotic behavior of turbulence. The existence and smoothness of their solutions is the subject of one of the Clay Mathematics Institute's Millennium Prize Problems.

- **Subfields it's part of**:
    - [Fluid Dynamics](https://en.wikipedia.org/wiki/Fluid_dynamics)
    - [Applied Mathematics](https://en.wikipedia.org/wiki/Applied_mathematics)
    - [Physics](https://en.wikipedia.org/wiki/Physics)

- **Subfields and concepts it includes**:
    - **Viscosity**: A measure of a fluid's resistance to flow.
    - **Turbulence**: The chaotic and unpredictable motion that arises in many fluid flows.
    - **Laminar Flow**: Smooth, orderly fluid motion, which occurs at low velocities.
    - **Incompressibility**: An assumption that the density of the fluid is constant.

- **Applications**:
    - **Engineering**: Designing aircraft (aerodynamics) and ships (hydrodynamics), modeling blood flow in arteries, and designing pipelines and ventilation systems.
    - **Meteorology**: Weather forecasting relies on numerical solutions to the Navier-Stokes equations for the atmosphere.
    - **Oceanography**: Modeling ocean currents.
    - **Computer Graphics**: Creating realistic animations of smoke, water, and fire for movies and video games.

- **More Concrete Variants**:
    - **Euler Equations**: A simplified version of the equations for a fluid with zero viscosity.
    - **Stokes Flow (Creeping Flow)**: A simplified version for very slow, viscous flows where the non-linear convective term is negligible.

- **More General Variants**:
    - **Relativistic Fluid Dynamics**: Extends the equations to be consistent with general relativity.

- **Related Concepts**:
    - **[Differential Equation](../differential_equations/differential_equation.md)**: The Navier-Stokes equations are a system of non-linear partial differential equations.
    - **[Derivative](../../../pure_mathematics/analysis/derivative.md)**: The equations are expressed using vector calculus concepts like the gradient and divergence, which are based on partial derivatives.
    - **[Vector Space](../../../pure_mathematics/linear_algebra/vector_space.md)**: The fluid velocity is a vector field, a key concept built upon vector spaces.
    - **[Linear Transformation](../../../pure_mathematics/linear_algebra/linear_transformation.md)**: The viscous stress tensor, which relates shear stress to the rate of strain, is a linear transformation.
    - **[Newton's Laws of Motion](../../physics/classical_mechanics/newtons_laws.md)**: The equations are a continuum mechanics application of Newton's second law.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_equations](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_equations)
