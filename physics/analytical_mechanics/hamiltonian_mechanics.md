# Hamiltonian Mechanics

- **Mathematical Definition**: Hamiltonian mechanics is a reformulation of Lagrangian mechanics. It is based on the **Hamiltonian** $H$, which represents the total energy of the system. The Hamiltonian is defined as a Legendre transformation of the Lagrangian:
$$ H(q, p, t) = \sum_j p_j \dot{q}_j - L(q, \dot{q}, t) $$
  where $q$ are the generalized coordinates, $\dot{q}$ are the generalized velocities, and $p$ are the **generalized momenta**, defined as $p_j = \frac{\partial L}{\partial \dot{q}_j}$. This procedure recasts the dynamics in terms of positions $q$ and momenta $p$ in **phase space**. The equations of motion are given by **Hamilton's equations**:
$$ \frac{dq_j}{dt} = \frac{\partial H}{\partial p_j} $$
$$ \frac{dp_j}{dt} = -\frac{\partial H}{\partial q_j} $$
  These are a set of first-order ordinary differential equations, in contrast to the second-order equations of Lagrangian mechanics.

- **Description**: Hamiltonian mechanics offers another perspective on classical mechanics. By treating position and momentum on an equal footing, it reveals a deeper symmetry in mechanics. The state of a system is described by a point in phase space, and the evolution of the system is described by the flow of points in this space. This geometric picture is very powerful and provides a direct bridge to quantum mechanics, where the Hamiltonian becomes the energy operator.

- **Subfields it's part of**:
    - [Analytical Mechanics](https://en.wikipedia.org/wiki/Analytical_mechanics): Hamiltonian mechanics is one of the two major reformulations of classical mechanics, alongside Lagrangian mechanics.
    - [Classical Mechanics](https://en.wikipedia.org/wiki/Classical_mechanics): It provides a powerful and abstract formulation of classical mechanics.
    - [Symplectic Geometry](https://en.wikipedia.org/wiki/Symplectic_geometry): Hamiltonian mechanics is the physical application of symplectic geometry; phase space is a symplectic manifold.
    - [Differential Equations](https://en.wikipedia.org/wiki/Differential_equation): The dynamics are described by Hamilton's equations, a set of first-order ordinary differential equations.

- **Subfields and concepts it includes**:
    - **Hamiltonian**: The total energy of the system as a function of position and momentum.
    - **Generalized Momenta**: Momenta corresponding to the generalized coordinates.
    - **Phase Space**: A space in which all possible states of a system are represented, with each possible state corresponding to a unique point. The phase space of Hamiltonian mechanics is a [symplectic manifold](../../../pure_mathematics/geometry/manifold.md).
    - **Hamilton's Equations**: The first-order differential equations of motion.
    - **Poisson Brackets**: A mathematical tool in Hamiltonian mechanics, which has a direct analogue in the commutators of quantum mechanics.

- **Applications**:
    - **Quantum Mechanics**: The Hamiltonian operator $\hat{H}$ in the [Schrödinger equation](../quantum_mechanics/schrodinger_equation.md) is the quantum-mechanical counterpart of the classical Hamiltonian.
    - **Celestial Mechanics**: Used for studying the long-term stability of planetary orbits.
    - **Statistical Mechanics**: The state of a system is a point in phase space, and statistical ensembles are distributions of points in phase space.
    - **Control Theory**: Used in the optimal control of dynamical systems.

- **More Concrete Variants**:
    - **Hamiltonian for a single particle**: For a particle in a conservative potential, this is simply the total energy $ H = \frac{\mathbf{p}^2}{2m} + V(\mathbf{x}) $.

- **More General Variants**:
    - **Hamiltonian Field Theory**: An extension of the formalism to continuous systems (fields).
    - **Symplectic Geometry**: The mathematical study of phase space and Hamiltonian dynamics.

- **Related Concepts**:
    - **[Lagrangian Mechanics](./lagrangian_mechanics.md)**: Hamiltonian mechanics is derived from Lagrangian mechanics via a Legendre transformation.
    - **[Schrödinger Equation](../quantum_mechanics/schrodinger_equation.md)**: The formulation of quantum mechanics is based on the Hamiltonian.
    - **Conservation of Energy**: If the Hamiltonian does not explicitly depend on time, it is a conserved quantity, representing the total energy of the system.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Hamiltonian_mechanics](https://en.wikipedia.org/wiki/Hamiltonian_mechanics)
