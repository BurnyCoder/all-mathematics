# Noether's Theorem

- **Mathematical Definition**: Noether's theorem states that every differentiable symmetry of the action of a physical system has a corresponding conservation law. The action $S$ of a physical system is defined as the integral of the Lagrangian function $L(q, \dot{q}, t)$ over time:
    $$ S = \int_{t_1}^{t_2} L(q, \dot{q}, t) dt $$
    where $q$ are the generalized coordinates, $\dot{q}$ are the generalized velocities, and $t$ is time. A transformation of the coordinates $q \to q'(\epsilon)$ is a symmetry if the Lagrangian is invariant up to a total time derivative, which means the action is invariant. If the action is invariant under a continuous group of transformations, then there exists a corresponding conserved quantity. For a transformation $q \to q + \delta q$, the conserved quantity $Q$ is given by:
    $$ Q = \frac{\partial L}{\partial \dot{q}} \delta q $$

- **Description**: This theorem provides a deep and powerful connection between the symmetries of a physical system and the quantities that are conserved during its evolution. It is a cornerstone of modern theoretical physics, from classical mechanics to quantum field theory. It reveals that conservation laws are not arbitrary rules but are direct consequences of the fundamental symmetries of nature.

- **Subfields it's part of**:
    - [Analytical Mechanics](https://en.wikipedia.org/wiki/Analytical_mechanics): Noether's theorem is a central result in the Lagrangian and Hamiltonian formulations of classical mechanics.
    - [Theoretical Physics](https://en.wikipedia.org/wiki/Theoretical_physics): It is a fundamental tool in almost all areas of theoretical physics.
    - [Calculus of Variations](https://en.wikipedia.org/wiki/Calculus_of_variations): The theorem is a result in the calculus of variations applied to physics.

- **Subfields and concepts it includes**:
    - **[Symmetry (physics)](https://en.wikipedia.org/wiki/Symmetry_in_physics)**: The core concept that the theorem is based on.
    - **[Conservation law](https://en.wikipedia.org/wiki/Conservation_law)**: The conclusion of the theorem.
    - **[Lagrangian Mechanics](./lagrangian_mechanics.md)**: The framework in which Noether's theorem is most naturally formulated.
    - **[Hamiltonian Mechanics](./hamiltonian_mechanics.md)**: The conserved quantities derived from Noether's theorem are constants of motion in Hamiltonian mechanics.
    - **[Principle of Least Action](./principle_of_least_action.md)**: The physical principle from which the equations of motion and Noether's theorem are derived.
    - **[Calculus of Variations](https://en.wikipedia.org/wiki/Calculus_of_variations)**: The mathematical field that provides the tools to prove the theorem.
    - **[Group Theory](../../pure_mathematics/algebra/group.md)**: Continuous symmetries are mathematically described by Lie groups.
    - **[Differential Geometry](../../pure_mathematics/geometry/manifold.md)**: Provides the modern mathematical language to express these ideas, especially in general relativity and gauge theory.

- **Applications**:
    - **Conservation of Energy**: Arises from the symmetry of physical laws with respect to time translation (the laws don't change over time).
    - **Conservation of Linear Momentum**: Arises from the symmetry of physical laws with respect to spatial translation (the laws are the same everywhere).
    - **Conservation of Angular Momentum**: Arises from the symmetry of physical laws with respect to rotations (the laws are the same in all directions).
    - **[Quantum Field Theory](https://en.wikipedia.org/wiki/Quantum_field_theory)**: Used to derive conservation laws for quantities like electric charge (from U(1) gauge symmetry) and color charge (from SU(3) gauge symmetry in QCD).
    - **[General Relativity](../general_relativity/einstein_field_equations.md)**: The conservation of the stress-energy tensor is related to the diffeomorphism invariance of the theory.

- **More Concrete Variants**: The theorem itself is quite general, but its applications lead to very concrete conservation laws:
    - **Conservation of charge in Electromagnetism**: A direct consequence of gauge invariance in Maxwell's equations.
    - **Conservation laws in the Standard Model**: The conservation of baryon number and lepton number are consequences of specific symmetries of the Standard Model Lagrangian.

- **More General Variants**:
    - **Noether's Second Theorem**: Relates gauge symmetries (symmetries that depend on arbitrary functions of spacetime) to identities among the equations of motion.
    - **Ward-Takahashi identities**: The quantum mechanical version of Noether's theorem in quantum field theory.
    - **Supersymmetry**: A hypothesized symmetry between bosons and fermions that would lead to new conserved quantities.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Noether%27s_theorem](https://en.wikipedia.org/wiki/Noether%27s_theorem)
