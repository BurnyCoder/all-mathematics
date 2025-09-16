# Quantum Field Theory

- **Mathematical Definition**: Quantum Field Theory (QFT) is a theoretical framework that combines classical field theory, special relativity, and quantum mechanics. A central mathematical tool in QFT is the **path integral formulation**, where the probability amplitude for a process is the sum over all possible histories of the system. For a scalar field $\phi$, the vacuum-to-vacuum transition amplitude in the presence of a source $J$ is given by the generating functional $Z[J]$:
$$ Z[J] = \int \mathcal{D}\phi e^{iS[\phi] + i\int d^4x J(x)\phi(x)} $$
  Here, $\mathcal{D}\phi$ represents integration over all possible field configurations. The action $S[\phi]$ is the integral of the **Lagrangian density** $\mathcal{L}$, which determines the dynamics of the field. For a simple scalar field, this might be:
$$ S[\phi] = \int d^4x \mathcal{L}(\phi, \partial_\mu \phi) = \int d^4x \left( \frac{1}{2}(\partial_\mu \phi)(\partial^\mu \phi) - \frac{1}{2}m^2\phi^2 \right) $$
  Correlation functions, which are central to calculating physical observables, can be obtained by taking functional derivatives of $Z[J]$ with respect to the source $J(x)$.

- **Description**: Quantum Field Theory is the fundamental language of modern particle physics and condensed matter physics. It describes elementary particles not as classical points, but as excitations (quanta) of underlying quantum fields that permeate all of spacetime. For example, an electron is a quantum of the "electron field". This framework allows for the description of processes where particles are created and annihilated, a key feature of high-energy physics that is absent in non-relativistic quantum mechanics.

- **Subfields it's part of**:
    - [Theoretical Physics](https://en.wikipedia.org/wiki/Theoretical_physics): QFT is a cornerstone of modern theoretical physics.
    - [Quantum Mechanics](../quantum_mechanics/schrodinger_equation.md): It is the relativistic generalization of quantum mechanics.
    - [Particle Physics](../particle_physics/standard_model.md): The Standard Model is formulated as a QFT.
    - [Condensed Matter Physics](https://en.wikipedia.org/wiki/Condensed_matter_physics): It is used to describe collective excitations like phonons and Cooper pairs.

- **Subfields and concepts it includes**:
    - **Quantum Fields**: Operator-valued distributions on spacetime that create and annihilate particles. These fields form a [vector space](../../../pure_mathematics/linear_algebra/vector_space.md), specifically an infinite-dimensional Hilbert space, and the operators are [linear transformations](../../../pure_mathematics/linear_algebra/linear_transformation.md) on this space. The mathematical theory of distributions, a part of [analysis](../../../pure_mathematics/analysis/), is essential.
    - **Lagrangian Field Theory**: QFTs are typically defined by a Lagrangian density, which is a generalization of the Lagrangian in [Lagrangian Mechanics](../analytical_mechanics/lagrangian_mechanics.md). The dynamics are found by minimizing the action, which is the [integral](../../../pure_mathematics/analysis/integral.md) of the Lagrangian density over spacetime. This minimization uses the calculus of variations, a topic in mathematical [analysis](../../../pure_mathematics/analysis/).
    - **Canonical Quantization**: A procedure for turning a classical field theory into a quantum theory by imposing commutation relations. This introduces a non-commutative [algebraic structure](../../../pure_mathematics/algebra/) on the field operators, which are related to Lie algebras, a type of [group](../../../pure_mathematics/algebra/group.md) theory.
    - **Path Integral Formulation**: An alternative quantization procedure that sums over all possible field histories, using a generalization of the [integral](../../../pure_mathematics/analysis/integral.md) over an infinite-dimensional space of functions.
    - **Feynman Diagrams**: A powerful perturbative tool for visualizing and calculating interactions between particles. Each diagram corresponds to a mathematical expression representing a term in a perturbative expansion (like a [Taylor series](../../../pure_mathematics/analysis/taylor_series.md)). The diagrams themselves are [graphs](../../../pure_mathematics/discrete_mathematics/graph_theory/graph.md), and their calculation involves multi-dimensional [integrals](../../../pure_mathematics/analysis/integral.md).
    - **Renormalization**: A collection of techniques used to handle the infinities that arise in calculations to produce finite, physically meaningful predictions. It involves carefully taking [limits](../../../pure_mathematics/analysis/limit.md) and relies heavily on complex [analysis](../../../pure_mathematics/analysis/). The Renormalization Group has deep connections to dynamical systems.
    - **Gauge Theory**: A type of QFT with local symmetries, which forms the basis for the fundamental forces of the [Standard Model](../particle_physics/standard_model.md). The mathematical framework is differential geometry, using concepts like [manifolds](../../../pure_mathematics/geometry/manifold.md) and fiber bundles. The symmetries are described by Lie [groups](../../../pure_mathematics/algebra/group.md).
    - **Spontaneous Symmetry Breaking**: A mechanism through which fields can acquire mass, such as the Higgs mechanism in the Standard Model. This is a phenomenon where the ground state of a system has less symmetry than the underlying laws that govern it. The symmetries are described by [group theory](../../../pure_mathematics/algebra/group.md).

- **Applications**:
    - **[Particle Physics](../particle_physics/standard_model.md)**: The [Standard Model of particle physics](../particle_physics/standard_model.md) is a complex QFT that describes all known elementary particles and their interactions.
    - **[Condensed Matter Physics](https://en.wikipedia.org/wiki/Condensed_matter_physics)**: Describes quasiparticles and phase transitions in many-body systems.
    - **[Cosmology](https://en.wikipedia.org/wiki/Cosmology)**: QFT in curved spacetime is used to describe phenomena in the early universe, such as cosmic inflation and the production of particles in gravitational fields.
    - **[Statistical Mechanics](https://en.wikipedia.org/wiki/Statistical_mechanics)**: Through a Wick rotation (imaginary time), QFT methods are directly applicable to problems in statistical mechanics.

- **More Concrete Variants**:
    - **Quantum Electrodynamics (QED)**: The relativistic quantum theory of electromagnetism, describing how light and matter interact.
    - **Quantum Chromodynamics (QCD)**: The theory of the strong interaction between quarks and gluons.
    - **Electroweak Theory**: The unified theory of electromagnetic and weak interactions.
    - **[Standard Model](../particle_physics/standard_model.md)**: Combines QCD and the Electroweak theory to describe the strong, weak, and electromagnetic fundamental forces.
    - **Scalar Field Theory ($\phi^4$ theory)**: The simplest interacting QFT, often used as a pedagogical tool and a starting point for more complex theories.

- **More General Variants**:
    - **Quantum Field Theory in Curved Spacetime**: An approximation to quantum gravity that treats spacetime as a classical background described by [General Relativity](../general_relativity/einstein_field_equations.md).
    - **[String Theory](../string_theory/string_theory.md)**: A candidate theory of quantum gravity which can be seen as a generalization of QFT where point particles are replaced by one-dimensional strings.
    - **Topological Quantum Field Theory (TQFT)**: A QFT whose correlation functions do not depend on the metric of spacetime, but on its topology.
    - **Supersymmetry (SUSY)**: A proposed extension of spacetime symmetry that relates particles with different spins (fermions and bosons).

- **Related Concepts**:
    - **[Special Relativity](../special_relativity/special_relativity.md)**: QFT is fundamentally based on the principles of special relativity.
    - **[Quantum Mechanics](../quantum_mechanics/schrodinger_equation.md)**: QFT extends quantum mechanics to systems with a varying number of particles and to describe fields.
    - **[Lagrangian Mechanics](../analytical_mechanics/lagrangian_mechanics.md)** and **[Hamiltonian Mechanics](../analytical_mechanics/hamiltonian_mechanics.md)**: The formalisms of QFT are built upon the Lagrangian and Hamiltonian formulations of classical field theory.
    - **[Standard Model](../particle_physics/standard_model.md)**: The most experimentally successful QFT developed to date.
    - **[General Relativity](../general_relativity/einstein_field_equations.md)**: The unification of QFT with general relativity to produce a theory of quantum gravity is one of the major unsolved problems in physics.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Quantum_field_theory](https://en.wikipedia.org/wiki/Quantum_field_theory)
