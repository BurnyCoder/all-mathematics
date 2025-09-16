# Schrödinger Equation

- **Mathematical Definition**: The Schrödinger equation is a linear partial differential equation that describes the wave function of a quantum-mechanical system. The time-dependent Schrödinger equation is:
$$ i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t) = \hat{H} \Psi(\mathbf{r}, t) $$
  where:
    - $i$ is the imaginary unit.
    - $\hbar$ is the reduced Planck constant.
    - $\Psi(\mathbf{r}, t)$ is the **wave function** of the system, which is a complex-valued function that describes the quantum state of a particle.
    - $\hat{H}$ is the **Hamiltonian operator**, which characterizes the total energy of the system. For a single particle with potential energy $V(\mathbf{r}, t)$, it is $\hat{H} = -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r}, t)$.

- **Description**: The Schrödinger equation is the central equation of quantum mechanics. Its solution, the wave function, does not give the exact position and momentum of a particle but instead describes the probability of finding the particle at a given position or with a given momentum. The square of the magnitude of the wave function, $|\Psi|^2$, represents the probability density. This probabilistic nature is a fundamental departure from classical mechanics.

- **Subfields it's part of**:
    - [Quantum Mechanics](https://en.wikipedia.org/wiki/Quantum_mechanics)
    - [Physics](https://en.wikipedia.org/wiki/Physics)
    - [Partial Differential Equations](https://en.wikipedia.org/wiki/Partial_differential_equation)

- **Subfields and concepts it includes**:
    - **Wave Function ($\Psi$)**: The mathematical description of the quantum state of a system.
    - **Hamiltonian Operator ($\hat{H}$)**: An operator corresponding to the total energy of the system.
    - **Probability Density**: The probability per unit volume of finding a particle at a given location.
    - **Quantum State**: The state of an isolated quantum system.
    - **Superposition**: The principle that a quantum system can be in multiple states at the same time.

- **Applications**:
    - **Chemistry**: Determining the electronic structure of atoms and molecules (quantum chemistry).
    - **Condensed Matter Physics**: Describing the behavior of electrons in solids, leading to the development of semiconductors and transistors.
    - **Particle Physics**: A foundation for the development of quantum field theory.
    - **Technology**: Essential for the design of lasers, MRI machines, and quantum computers.

- **More Concrete Variants**:
    - **Time-Independent Schrödinger Equation**: A simplified version of the equation used for systems in a stationary state (where the energy is constant).
    - **Particle in a Box**: A simple, solved model in quantum mechanics for a particle confined to a small space.
    - **Quantum Harmonic Oscillator**: A model for vibrations in molecules.
    - **Hydrogen Atom**: The Schrödinger equation can be solved exactly for the hydrogen atom, which was a major success of the theory.

- **More General Variants**:
    - **Dirac Equation**: A relativistic wave equation that describes electrons and is consistent with both quantum mechanics and special relativity.
    - **Klein-Gordon Equation**: A relativistic wave equation for spin-0 particles.
    - **Quantum Field Theory (QFT)**: The framework that extends quantum mechanics to fields, providing the basis for the Standard Model of particle physics.

- **Related Concepts**:
    - **[Partial Differential Equation](../../applied_mathematics/differential_equations/pde.md)**: The Schrödinger equation is a specific type of PDE.
    - **[Linear Algebra](../../pure_mathematics/algebra/linear_algebra.md)**: The state of a quantum system is represented by a vector in a Hilbert space, and physical observables are represented by Hermitian operators.
    - **[Probability Theory](../../applied_mathematics/probability_theory/probability_space.md)**: The output of the equation is interpreted probabilistically.
    - **Fourier Analysis**: Used extensively to solve the equation and to move between position and momentum representations.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation)
