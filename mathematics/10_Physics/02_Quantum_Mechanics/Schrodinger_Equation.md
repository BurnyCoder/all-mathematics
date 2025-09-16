# Schrödinger Equation

## Mathematical Definition

The **Schrödinger equation** is a linear [partial differential equation](../../../08_Applied_Mathematics/00_Differential_Equations/Differential_Equation.md) that governs the wave function of a quantum-mechanical system. It is a key result in quantum mechanics and its discovery was a significant landmark in the development of the subject.

The equation comes in two common forms: the time-dependent and time-independent Schrödinger equations.

### Time-Dependent Schrödinger Equation

This equation describes how the state of a system changes over time.
\[ i\hbar \frac{\partial}{\partial t} \Psi(\mathbf{r}, t) = \hat{H} \Psi(\mathbf{r}, t) \]
where:
*   \(i\) is the imaginary unit.
*   \(\hbar\) is the reduced Planck constant.
*   \(\frac{\partial}{\partial t}\) is the partial derivative with respect to time.
*   \(\Psi(\mathbf{r}, t)\) is the **wave function** of the system, which is a [complex-valued](../../../00_Foundations/02_Number_Systems/Complex_Numbers.md) function that describes the quantum state of a particle.
*   \(\hat{H}\) is the **Hamiltonian operator**, which characterizes the total energy of the system. For a single particle in a potential \(V\), it is given by:
    \[ \hat{H} = -\frac{\hbar^2}{2m}\nabla^2 + V(\mathbf{r}, t) \]
    (where \(m\) is the particle's mass and \(\nabla^2\) is the Laplacian operator).

### Time-Independent Schrödinger Equation

When the Hamiltonian operator is not dependent on time, the equation can be simplified by separation of variables to the time-independent form:
\[ \hat{H} \psi(\mathbf{r}) = E \psi(\mathbf{r}) \]
This is an **eigenvalue equation**. The solutions \(\psi(\mathbf{r})\) are the **energy eigenstates** (or stationary states), and the corresponding values \(E\) are the allowed **energy eigenvalues**.

## Description

The Schrödinger equation is the quantum mechanical counterpart to [Newton's second law](./../00_Classical_Mechanics/Newtons_Laws_of_Motion.md) in classical mechanics. It describes the time evolution of a system's wave function. The wave function itself is a probabilistic description of the particle's location and momentum; the square of its absolute value, \(|\Psi(\mathbf{r}, t)|^2\), represents the **probability density** of finding the particle at a given position \(\mathbf{r}\) at time \(t\). A key feature of the equation is its linearity, which leads to the principle of quantum superposition.

## Subfields it's part of

*   [Quantum Mechanics](./)
*   Quantum Chemistry
*   Quantum Field Theory
*   Physics

## Subfields and concepts it includes

*   **Wave Function (\(\Psi\)):** A mathematical description of the quantum state of a system.
*   **Hamiltonian Operator (\(\hat{H}\)):** The operator corresponding to the total energy of the system.
*   **Eigenstates and Eigenvalues:** The special solutions to the time-independent equation, representing states with a definite, quantized energy.
*   **Quantum Superposition:** The linearity of the equation means that if \(\Psi_1\) and \(\Psi_2\) are solutions, then any linear combination \(c_1\Psi_1 + c_2\Psi_2\) is also a valid solution.
*   **Probability Interpretation (Born Rule):** The interpretation of \(|\Psi|^2\) as a probability density.

## Applications

*   **Atomic and Molecular Physics:** Predicting the energy levels of electrons in atoms, which explains atomic spectra.
*   **Quantum Chemistry:** Solving the Schrödinger equation for molecules is a central task, allowing for the prediction of chemical bond energies and molecular geometries.
*   **Condensed Matter Physics:** Understanding the behavior of electrons in solids, which is essential for developing semiconductors and other materials.
*   **Quantum Computing:** The evolution of qubits is governed by the Schrödinger equation.
*   **Quantum Tunneling:** Describes how a particle can pass through a potential barrier even if it does not have enough energy to overcome it classically. This is crucial for nuclear fusion and scanning tunneling microscopes.

## More general variants

*   **Dirac Equation:** A relativistic wave equation that describes electrons and other spin-1/2 particles. It is consistent with both quantum mechanics and special relativity.
*   **Klein-Gordon Equation:** A relativistic wave equation for spin-0 particles.
*   **Quantum Field Theory (QFT):** In QFT, the Schrödinger equation is replaced by a more general framework where the fundamental objects are quantum fields, not fixed numbers of particles.

## Everything else it relates to

*   **Hamiltonian Mechanics:** The Schrödinger equation is constructed using the quantum mechanical version of the [Hamiltonian](./../00_Classical_Mechanics/Hamiltonian_Mechanics.md).
*   **Linear Algebra:** The state of a quantum system is a vector in an abstract [vector space](../../../01_Algebra/02_Linear_Algebra/Vector_Space.md) (a Hilbert space), and physical observables are represented by linear operators. The time-independent Schrödinger equation is an eigenvalue equation.
*   **Complex Numbers:** The wave function is fundamentally complex-valued.
*   **Probability Theory:** The predictions of quantum mechanics are inherently probabilistic.
*   **Fourier Analysis:** The relationship between a particle's wave function in position space and momentum space is given by the Fourier transform.
