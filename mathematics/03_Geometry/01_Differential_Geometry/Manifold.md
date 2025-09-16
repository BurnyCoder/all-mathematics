# Manifold

## Mathematical Definition

A **manifold** is a [topological space](../../../04_Topology/Topological_Space.md) that locally resembles [Euclidean space](../../00_Euclidean_Geometry/Euclidean_Space.md). More precisely, an \(n\)-dimensional manifold, or \(n\)-manifold, is a topological space with the property that each point has a neighborhood that is homeomorphic (topologically identical) to an open subset of \(n\)-dimensional Euclidean space \(\mathbb{R}^n\).

Manifolds can be endowed with additional structure. A key example is a **differentiable manifold**, which is a manifold with a structure that allows for calculus to be done. A differentiable manifold has a **global differential structure**, which means it is equipped with an **atlas**. An atlas is a collection of **charts** (homeomorphisms from open subsets of the manifold to open subsets of \(\mathbb{R}^n\)) such that the **transition maps** between overlapping charts are differentiable functions.

## Description

A manifold is a mathematical space that looks "flat" on a small enough scale, even though it may be "curved" on a larger scale. The surface of the Earth is a classic example of a 2-dimensional manifold; while it is a sphere (curved), any small portion of it appears flat and can be accurately mapped by a 2D Euclidean coordinate system. Manifolds generalize the concepts of curves (1-manifolds) and surfaces (2-manifolds) to any number of dimensions. They are the central objects of study in differential geometry and topology.

## Subfields it's part of

*   [Differential Geometry](./)
*   [Algebraic Geometry](./../02_Algebraic_Geometry/)
*   [Topology](../../../04_Topology/)
*   General Relativity

## Subfields and concepts it includes

*   **Chart and Atlas:** The mathematical tools used to define a coordinate system on a local piece of the manifold.
*   **Tangent Space:** At each point on a differentiable manifold, there is a vector space called the tangent space, which is the space of all possible "velocity vectors" for curves passing through that point. It is the best linear approximation of the manifold at that point.
*   **Vector Field:** An assignment of a tangent vector to each point of a manifold.
*   **Tensor Field:** A generalization of a vector field that assigns a tensor to each point.
*   **Differential Forms:** A type of tensor field that can be integrated over a manifold.
*   **Riemannian Manifold:** A differentiable manifold equipped with a smoothly varying inner product on each tangent space (a Riemannian metric). This allows for the definition of distance, angle, curvature, and volume.
*   **Lie Group:** A group that is also a differentiable manifold, with the group operations being smooth maps.

## Applications

*   **General Relativity:** Einstein's theory of gravity models spacetime as a 4-dimensional, curved (pseudo-Riemannian) manifold, where the curvature is induced by the presence of mass and energy.
*   **Classical Mechanics:** The state space of a mechanical system is often a manifold (e.g., a symplectic manifold in Hamiltonian mechanics).
*   **Robotics:** The configuration space of a robot (the set of all possible positions of its joints) is a manifold.
*   **Computer Graphics:** Manifolds are used to represent surfaces and shapes.
*   **Economics:** Used in econometrics and general equilibrium theory.

## More general variants

*   **Orbifold:** A generalization of a manifold that allows for certain kinds of "singularities".
*   **Infinite-dimensional Manifolds:** Manifolds modeled on infinite-dimensional vector spaces like Banach spaces or Fréchet spaces.

## More concrete variants

*   **Curves (1-manifolds):** e.g., a circle, a line.
*   **Surfaces (2-manifolds):** e.g., the sphere, the torus, the projective plane.
*   **3-Manifolds:** The study of 3-manifolds is a major area of research, related to the Poincaré conjecture.
*   **Euclidean Space (\(\mathbb{R}^n\)):** The simplest example of an n-manifold.
*   **Lie Groups:** e.g., the group of rotations in 3D, SO(3).

## Everything else it relates to

*   **Topology:** Manifolds are a special type of topological space.
*   **Linear Algebra:** The tangent space at each point of a manifold is a vector space.
*   **Calculus:** Differentiable manifolds are the setting for a generalized, coordinate-independent version of multivariable calculus.
*   **De Rham Cohomology:** A tool from algebraic topology used to study the global properties of manifolds by relating differential forms to topological invariants.
