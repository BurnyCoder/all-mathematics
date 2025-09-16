# Newton's Laws of Motion

## Mathematical Definition

Newton's laws of motion are three physical laws that, together, laid the foundation for classical mechanics. They describe the relationship between a body and the forces acting upon it, and its motion in response to those forces.

### Newton's First Law (Law of Inertia)

An object at rest stays at rest and an object in motion stays in motion with the same speed and in the same direction unless acted upon by an unbalanced force.

Mathematically, this means that if the net force on an object is zero, then the velocity of the object is constant.
\[ \sum \mathbf{F} = 0 \iff \frac{d\mathbf{v}}{dt} = 0 \]
where \(\mathbf{F}\) is the force [vector](../../../01_Algebra/02_Linear_Algebra/Vector_Space.md) and \(\mathbf{v}\) is the velocity vector.

### Newton's Second Law (Law of Acceleration)

The acceleration of an object as produced by a net force is directly proportional to the magnitude of the net force, in the same direction as the net force, and inversely proportional to the mass of the object.

This is the most famous law, expressed as a [differential equation](../../../08_Applied_Mathematics/00_Differential_Equations/Differential_Equation.md):
\[ \mathbf{F} = m\mathbf{a} = m \frac{d\mathbf{v}}{dt} = m \frac{d^2\mathbf{x}}{dt^2} \]
where \(m\) is the mass of the object and \(\mathbf{a}\) is its acceleration. A more general form states that the net force is equal to the rate of change of momentum \(\mathbf{p} = m\mathbf{v}\):
\[ \mathbf{F} = \frac{d\mathbf{p}}{dt} \]

### Newton's Third Law (Law of Action and Reaction)

For every action, there is an equal and opposite reaction.

This means that if object A exerts a force \(\mathbf{F}_{AB}\) on object B, then object B simultaneously exerts a force \(\mathbf{F}_{BA}\) on object A, and the two forces are equal in magnitude and opposite in direction:
\[ \mathbf{F}_{AB} = -\mathbf{F}_{BA} \]

## Description

Newton's laws of motion provide a conceptual and mathematical framework for understanding the motion of macroscopic objects in an inertial frame of reference. They were the first to show that the motion of objects on Earth and of celestial bodies could be described by the same set of natural laws.

## Subfields it's part of

*   [Classical Mechanics](./)
*   Dynamics
*   Physics

## Subfields and concepts it includes

*   **Force:** A push or pull upon an object resulting from the object's interaction with another object.
*   **Mass:** A measure of an object's inertia.
*   **Inertia:** The resistance of any physical object to any change in its state of motion.
*   **Momentum:** The product of the mass and velocity of an object (\(\mathbf{p} = m\mathbf{v}\)). The third law implies the conservation of momentum.
*   **Frame of Reference:** A coordinate system used to describe the motion of objects. Newton's laws hold in **inertial frames of reference**.

## Applications

*   **Engineering:** Designing and analyzing structures, machines, and vehicles.
*   **Astronomy:** Calculating the orbits of planets, moons, and satellites (celestial mechanics).
*   **Vehicle Dynamics:** Understanding the motion of cars, airplanes, and rockets.
*   **Biomechanics:** Modeling the movement of animals and humans.

## More general variants

*   **Lagrangian Mechanics:** A reformulation of classical mechanics that is based on the principle of stationary action. It uses generalized coordinates and energy (the Lagrangian) instead of forces.
*   **Hamiltonian Mechanics:** Another reformulation of classical mechanics that is based on the total energy (the Hamiltonian). It is central to the development of quantum mechanics.
*   **Special Relativity:** Modifies Newton's laws to be consistent with the principle that the speed of light is constant for all observers. This becomes important for objects moving at speeds close to the speed of light.
*   **General Relativity:** A theory of gravitation in which gravity is not a force, but a consequence of the curvature of spacetime. It replaces Newton's law of universal gravitation.
*   **Quantum Mechanics:** Describes the motion and interaction of subatomic particles, where Newton's laws fail.

## More concrete variants

*   **Statics:** The study of forces in equilibrium (\(\sum \mathbf{F} = 0\)).
*   **Kinematics:** The study of motion without considering its causes (forces).
*   **Projectile Motion**
*   **Simple Harmonic Motion**

## Everything else it relates to

*   **Differential Equations:** Newton's second law is a second-order ordinary differential equation. Solving it allows for the prediction of an object's trajectory.
*   **Calculus:** The concepts of [derivative](../../../02_Analysis/00_Calculus/Derivative.md) (velocity, acceleration) and [integral](../../../02_Analysis/00_Calculus/Integral.md) (to find position from velocity) are essential.
*   **Vector Spaces:** Force, velocity, acceleration, and momentum are all vector quantities, typically in 3D [Euclidean Space](../../../03_Geometry/00_Euclidean_Geometry/Euclidean_Space.md).
*   **Conservation Laws:** Newton's laws lead directly to the principles of conservation of momentum and energy.
