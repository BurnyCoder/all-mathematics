# Euclidean Space

## Mathematical Definition

An **n-dimensional Euclidean space**, denoted \(\mathbb{R}^n\), is the [set](../../../00_Foundations/01_Set_Theory/Set.md) of all n-tuples of [real numbers](../../../00_Foundations/02_Number_Systems/Real_Numbers.md). A point in this space is represented by an ordered n-tuple \((x_1, x_2, ..., x_n)\).

Euclidean space is a [vector space](../../../01_Algebra/02_Linear_Algebra/Vector_Space.md), but it is equipped with an additional structure: the **Euclidean inner product** (or dot product). For two vectors \(\mathbf{x} = (x_1, ..., x_n)\) and \(\mathbf{y} = (y_1, ..., y_n)\), the dot product is defined as:
\[ \mathbf{x} \cdot \mathbf{y} = \sum_{i=1}^{n} x_i y_i = x_1 y_1 + x_2 y_2 + \cdots + x_n y_n \]
This inner product allows for the definition of geometric concepts:
*   **Length (or Euclidean Norm):** The length of a vector \(\mathbf{x}\) is given by:
    \[ \|\mathbf{x}\| = \sqrt{\mathbf{x} \cdot \mathbf{x}} = \sqrt{x_1^2 + x_2^2 + \cdots + x_n^2} \]
*   **Distance (Euclidean Metric):** The distance between two points \(\mathbf{x}\) and \(\mathbf{y}\) is:
    \[ d(\mathbf{x}, \mathbf{y}) = \|\mathbf{x} - \mathbf{y}\| = \sqrt{(x_1 - y_1)^2 + \cdots + (x_n - y_n)^2} \]
    This is the familiar Pythagorean theorem generalized to n dimensions.
*   **Angle:** The angle \(\theta\) between two non-zero vectors \(\mathbf{x}\) and \(\mathbf{y}\) is defined by:
    \[ \cos \theta = \frac{\mathbf{x} \cdot \mathbf{y}}{\|\mathbf{x}\| \|\mathbf{y}\|} \]

## Description

Euclidean space is the flat, n-dimensional space that serves as the setting for classical geometry. It is the familiar space of points, lines, planes, and higher-dimensional analogs. The key feature is that it has a metric structure that allows for the measurement of distances and angles, and this structure is constant throughout the space (it is "flat").

## Subfields it's part of

*   [Euclidean Geometry](./)
*   [Geometry](../)
*   [Linear Algebra](../../../01_Algebra/02_Linear_Algebra/)
*   [Topology](../../../04_Topology/)

## Subfields and concepts it includes

*   **Points, Lines, Planes, Hyperplanes**
*   **Euclidean Transformations (Isometries):** Transformations that preserve distance, such as translations, rotations, and reflections.
*   **Parallelism and Perpendicularity (Orthogonality)**
*   **Geometric Shapes (Polygons, Polyhedra, etc.)**
*   **Coordinate Systems (e.g., Cartesian, Polar)**

## Applications

*   **Classical Mechanics:** The setting for Newtonian physics.
*   **Computer Graphics and CAD:** The 2D and 3D Euclidean spaces are the standard spaces for modeling and rendering.
*   **Geodesy and Cartography:** Modeling the Earth's surface (locally) as a Euclidean space.
*   **Data Analysis:** High-dimensional Euclidean spaces are used to represent data sets, where the distance between points represents the similarity between data items.
*   **Optimization:** Many optimization problems are formulated in terms of finding the point of minimum distance in a Euclidean space.

## More general variants

*   **Manifold:** A topological space that is locally Euclidean, meaning that every point has a neighborhood that "looks like" an open set in \(\mathbb{R}^n\). Manifolds can be curved, unlike Euclidean space.
    *   **Riemannian Manifold:** A manifold with a smoothly varying inner product on each tangent space, allowing for the measurement of distance and angle in curved space.
*   **Inner Product Space:** An abstract vector space with an inner product. Euclidean space is the primary example.
*   **Metric Space:** A set with a distance function (metric).
*   **Affine Space:** A geometric structure that is similar to a vector space but without a distinguished origin.
*   **Non-Euclidean Geometries (Hyperbolic and Elliptic/Spherical):** Geometries that reject Euclid's parallel postulate.

## More concrete variants

*   **\(\mathbb{R}^1\):** The real number line.
*   **\(\mathbb{R}^2\):** The Cartesian plane.
*   **\(\mathbb{R}^3\):** The three-dimensional space of classical physics and everyday experience.
*   **Minkowski Space:** A four-dimensional pseudo-Euclidean space used in special relativity, where the "distance" (spacetime interval) is not positive definite.

## Everything else it relates to

*   **Pythagorean Theorem:** The formula for Euclidean distance is a direct generalization of the Pythagorean theorem.
*   **Calculus on Euclidean Spaces:** The concepts of calculus (derivatives and integrals) can be extended to functions defined on \(\mathbb{R}^n\).
*   **Cauchy-Schwarz Inequality:** A fundamental inequality relating the dot product of two vectors to their lengths.
*   **Euclid's Axioms:** Euclidean geometry is the system of geometry that results from accepting the five postulates of Euclid.
