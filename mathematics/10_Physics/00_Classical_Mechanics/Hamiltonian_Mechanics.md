# Hamiltonian Mechanics

## Mathematical Definition

**Hamiltonian mechanics** is a reformulation of classical mechanics that is based on the **Hamiltonian** function, \(H\), which represents the total energy of the system. It is derived from the [Lagrangian](./Lagrangian_Mechanics.md) via a **Legendre transformation**.

The system is described by a set of **canonical coordinates**, which consist of the generalized coordinates \(q_i\) and their corresponding **conjugate momenta** \(p_i\).
The conjugate momentum is defined as:
\[ p_i = \frac{\partial L}{\partial \dot{q}_i} \]
The Hamiltonian is then defined as:
\[ H(q, p, t) = \sum_i p_i \dot{q}_i - L(q, \dot{q}, t) \]
For many common systems, the Hamiltonian is equal to the total energy, \(H = T + V\).

The dynamics of the system are described by a set of 2n first-order ordinary [differential equations](../../../08_Applied_Mathematics/00_Differential_Equations/Differential_Equation.md), known as **Hamilton's equations**:
\[ \frac{dq_i}{dt} = \frac{\partial H}{\partial p_i} \]
\[ \frac{dp_i}{dt} = -\frac{\partial H}{\partial q_i} \]

## Description

Hamiltonian mechanics is a highly abstract and powerful formulation of classical mechanics. Instead of a configuration space of dimension n, it describes the system's evolution in a 2n-dimensional space called **phase space**, whose coordinates are position and momentum. The state of the system is a single point in this space, and the evolution of the system is a path (or flow) in phase space determined by the Hamiltonian. This geometric picture is very powerful and provides a direct bridge to quantum mechanics and statistical mechanics.

## Subfields it's part of

*   [Classical Mechanics](./)
*   Symplectic Geometry
*   Dynamical Systems
*   Physics

## Subfields and concepts it includes

*   **Hamiltonian:** The total energy function of the system.
*   **Canonical Coordinates:** The pair of generalized coordinates (\(q_i\)) and conjugate momenta (\(p_i\)).
*   **Phase Space:** The 2n-dimensional space whose axes are the canonical coordinates. The state of a system is a single point in phase space.
*   **Poisson Bracket:** An operation between two quantities in phase space that describes how they evolve in time. For any quantity \(A\), its time evolution is given by \(\frac{dA}{dt} = \{A, H\} + \frac{\partial A}{\partial t}\).
*   **Liouville's Theorem:** States that the volume of a region of phase space is conserved as it evolves in time. This is a key principle in statistical mechanics.
*   **Canonical Transformation:** A change of coordinates in phase space that preserves the form of Hamilton's equations.
*   **Hamilton-Jacobi Equation:** A formulation of Hamiltonian mechanics that is particularly useful for identifying conserved quantities.

## Applications

*   **Foundation for Quantum Mechanics:** The structure of Hamiltonian mechanics is a direct inspiration for the formalism of quantum mechanics. The Hamiltonian becomes an operator, Poisson brackets become commutators, and the state of the system is a vector in a Hilbert space.
*   **Statistical Mechanics:** The concept of phase space is the foundation for the statistical description of systems with many particles.
*   **Celestial Mechanics:** Used for advanced calculations of planetary orbits and stability.
*   **Chaos Theory:** The geometric picture of flows in phase space is ideal for studying chaotic systems.
*   **Control Theory:** Used in optimal control problems.

## More general variants

*   **Hamiltonian Field Theory:** An extension of Hamiltonian mechanics to continuous systems (fields).
*   **Symplectic Geometry:** The mathematical study of symplectic manifolds, which are the geometric structure of phase space in Hamiltonian mechanics.

## Everything else it relates to

*   **Lagrangian Mechanics:** Hamiltonian mechanics is derived from Lagrangian mechanics via the Legendre transformation.
*   **Quantum Mechanics:** Provides the classical limit and the formal inspiration for quantum mechanics. The Schrödinger equation can be seen as the quantum analog of Hamilton's equations.
*   **Manifolds:** Phase space is an example of a symplectic [manifold](../../../03_Geometry/01_Differential_Geometry/Manifold.md).
*   **Conservation Laws:** A quantity is conserved if its Poisson bracket with the Hamiltonian is zero.
