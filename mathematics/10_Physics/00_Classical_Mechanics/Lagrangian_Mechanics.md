# Lagrangian Mechanics

## Mathematical Definition

**Lagrangian mechanics** is a reformulation of classical mechanics that is based on the **principle of stationary action**. It describes a mechanical system by a single scalar function, the **Lagrangian**, \(L\), which is the difference between the system's kinetic energy \(T\) and its potential energy \(V\).
\[ L = T - V \]
The dynamics of the system are determined by finding the path through the system's **configuration space** that extremizes the **action**, \(S\), which is the [integral](../../../02_Analysis/00_Calculus/Integral.md) of the Lagrangian over time:
\[ S = \int_{t_1}^{t_2} L(q(t), \dot{q}(t), t) \,dt \]
where \(q\) represents the **generalized coordinates** of the system and \(\dot{q}\) represents the generalized velocities.

The path that the system follows is the one for which the action is stationary (i.e., the variation of the action is zero, \(\delta S = 0\)). The condition for this is given by the **Euler-Lagrange equations**, which are a set of second-order ordinary [differential equations](../../../08_Applied_Mathematics/00_Differential_Equations/Differential_Equation.md):
\[ \frac{d}{dt} \left( \frac{\partial L}{\partial \dot{q}_i} \right) - \frac{\partial L}{\partial q_i} = 0 \]
for each generalized coordinate \(q_i\).

## Description

Lagrangian mechanics provides a more abstract and powerful framework for classical mechanics than the Newtonian approach. Instead of dealing with vector forces and accelerations, it describes a system in terms of its kinetic and potential energies. The core idea is that a physical system will always evolve in a way that minimizes (or, more generally, makes stationary) a quantity called the action. This approach is often simpler for constrained systems and elegantly connects symmetries to conservation laws.

## Subfields it's part of

*   [Classical Mechanics](./)
*   [Calculus of Variations](../../../08_Applied_Mathematics/02_Optimization/)
*   Physics

## Subfields and concepts it includes

*   **Lagrangian:** The function \(L = T - V\).
*   **Action:** The integral of the Lagrangian over time.
*   **Principle of Least Action (or more accurately, Principle of Stationary Action):** The principle that the true path of a system is an extremum of the action.
*   **Generalized Coordinates:** A set of independent coordinates that are used to describe the configuration of a system. They do not have to be Cartesian coordinates.
*   **Configuration Space:** The space of all possible values of the generalized coordinates.
*   **Noether's Theorem:** A fundamental theorem that relates continuous symmetries of a physical system with conservation laws. For example:
    *   Symmetry in time \(\implies\) Conservation of energy.
    *   Symmetry in translation \(\implies\) Conservation of momentum.
    *   Symmetry in rotation \(\implies\) Conservation of angular momentum.

## Applications

*   **Complex Mechanical Systems:** The Lagrangian method is often much simpler than the Newtonian method for systems with many components or constraints (e.g., a double pendulum).
*   **Foundation for Modern Physics:** The principle of stationary action and the Lagrangian formalism are central to the development of quantum mechanics (via the path integral formulation), quantum field theory, and general relativity.
*   **Robotics:** Used to derive the equations of motion for robotic arms and other mechanisms.
*   **Orbital Mechanics:** Calculating the motion of planets and satellites.

## More general variants

*   **Hamiltonian Mechanics:** An even more abstract reformulation of classical mechanics that is based on the Lagrangian. It describes the system in terms of generalized coordinates and generalized momenta in a **phase space**. It is the formulation of classical mechanics that is closest to quantum mechanics.
*   **Lagrangian Field Theory:** An extension of Lagrangian mechanics to continuous systems (fields), like the electromagnetic field or the Higgs field.

## More concrete variants

*   The Lagrangian for a simple particle of mass \(m\) in a conservative potential \(V(x)\) in one dimension is \(L = \frac{1}{2}m\dot{x}^2 - V(x)\).

## Everything else it relates to

*   **Newton's Laws of Motion:** The Euler-Lagrange equations are equivalent to Newton's second law for systems with conservative forces.
*   **Manifolds:** The configuration space of a mechanical system is often a differentiable [manifold](../../../03_Geometry/01_Differential_Geometry/Manifold.md).
*   **Calculus of Variations:** The mathematical framework for finding extrema of functionals, which is precisely what the principle of stationary action requires.
*   **Symmetry:** Noether's theorem, a cornerstone of the Lagrangian formalism, provides a deep and elegant connection between the symmetries of a system and its conservation laws.
