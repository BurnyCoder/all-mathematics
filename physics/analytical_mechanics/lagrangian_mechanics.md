# Lagrangian Mechanics

- **Mathematical Definition**: Lagrangian mechanics is a reformulation of classical mechanics that is based on the **[principle of stationary action](./principle_of_least_action.md)**. The central object is the **Lagrangian** \\(L\\), which for many systems is defined as the kinetic energy \\(T\\) minus the potential energy \\(V\\):
  \\( L = T - V \\)
  The motion of the system between two points in time \\(t_1\\) and \\(t_2\\) is described by the path that makes the **action** integral \\(S\\) stationary (typically, a minimum):
  \\( S = \int_{t_1}^{t_2} L(q, \dot{q}, t) \,dt \\)
  where \\(q\\) represents the **generalized coordinates** of the system and \\(\dot{q}\\) their time derivatives. The condition that the action is stationary leads to the **Euler-Lagrange equations**:
  \\( \frac{d}{dt} \left( \frac{\partial L}{\partial \dot{q}_j} \right) - \frac{\partial L}{\partial q_j} = 0 \\)
  This is a set of second-order ordinary differential equations whose solutions are the equations of motion of the system.

- **Description**: Lagrangian mechanics provides a powerful alternative to the Newtonian approach. Instead of dealing with vector forces, it uses scalar quantities (kinetic and potential energy) and a single variational principle. This often simplifies problems, especially those with constraints (like a bead on a wire), because it allows for the use of any convenient set of generalized coordinates.

- **Subfields it's part of**:
    - [Analytical Mechanics](https://en.wikipedia.org/wiki/Analytical_mechanics)
    - [Classical Mechanics](https://en.wikipedia.org/wiki/Classical_mechanics)
    - [Calculus of Variations](https://en.wikipedia.org/wiki/Calculus_of_variations)

- **Subfields and concepts it includes**:
    - **Lagrangian**: The core function \\(L = T - V\\).
    - **Action**: The integral of the Lagrangian over time.
    - **[Principle of Stationary Action](./principle_of_least_action.md)**: The physical principle that the action is minimized or maximized.
    - **Generalized Coordinates**: A set of parameters that can describe the configuration of the system.
    - **Euler-Lagrange Equations**: The equations of motion derived from the principle of stationary action.

- **Applications**:
    - **Physics**: It is the preferred formalism for writing down theories in modern physics, from classical field theory and general relativity to quantum field theory.
    - **Robotics**: Used to derive the equations of motion for robotic arms and other complex mechanical systems.
    - **Engineering**: Modeling complex constrained mechanical systems.

- **More Concrete Variants**:
    - **Lagrangian for a single particle**: For a particle in a conservative potential, this is simply \\( L = \frac{1}{2}m\mathbf{v}^2 - V(\mathbf{x}) \\).

- **More General Variants**:
    - **Hamiltonian Mechanics**: A reformulation of Lagrangian mechanics that is even more central to the development of modern physics, particularly quantum mechanics.
    - **Lagrangian Field Theory**: An extension of the formalism to continuous systems (fields) instead of discrete particles.

- **Related Concepts**:
    - **[Newton's Laws of Motion](../classical_mechanics/newtons_laws.md)**: The Euler-Lagrange equations are equivalent to Newton's second law for many systems.
    - **[Differential Equation](../../applied_mathematics/differential_equations/differential_equation.md)**: The Euler-Lagrange equations are a system of differential equations.
    - **Calculus of Variations**: The mathematical field that deals with finding minima or maxima of functionals (mappings from a set of functions to the real numbers), which is the mathematical basis for Lagrangian mechanics.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Lagrangian_mechanics](https://en.wikipedia.org/wiki/Lagrangian_mechanics)
