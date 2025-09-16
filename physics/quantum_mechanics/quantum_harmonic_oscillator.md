# Quantum Harmonic Oscillator

- **Mathematical Definition**: The quantum harmonic oscillator is the quantum-mechanical analog of the classical harmonic oscillator. Its Hamiltonian operator is given by:
$$ \hat{H} = \frac{\hat{p}^2}{2m} + \frac{1}{2}m\omega^2\hat{x}^2 $$
  where:
    - $\hat{p}$ is the momentum operator ($-i\hbar\frac{d}{dx}$).
    - $\hat{x}$ is the position operator.
    - $m$ is the mass of the particle.
    - $\omega$ is the angular frequency of the oscillator.
  The time-independent Schrödinger equation is $\hat{H}\psi = E\psi$. The energy levels are quantized and given by:
$$ E_n = \hbar\omega\left(n + \frac{1}{2}\right), \quad n=0, 1, 2, \dots $$
  Unlike the classical case, the energy cannot be zero; the lowest possible energy is $E_0 = \frac{1}{2}\hbar\omega$, known as the zero-point energy.

- **Description**: The quantum harmonic oscillator is one of the most important model systems in quantum mechanics. It is one of the few quantum-mechanical systems for which an exact, analytical solution is known. The quantization of energy levels is a hallmark feature, meaning the oscillator can only have discrete amounts of energy.

- **Subfields it's part of**:
    - [Quantum Mechanics](https://en.wikipedia.org/wiki/Quantum_mechanics): It is a fundamental exactly solvable model.
    - [Quantum Field Theory](https://en.wikipedia.org/wiki/Quantum_field_theory): Quantum fields can be viewed as a collection of quantum harmonic oscillators. This is the basis for second quantization.
    - [Statistical Mechanics](https://en.wikipedia.org/wiki/Statistical_mechanics): Used to model the vibrations of a crystal lattice (phonons) and in Planck's law of black-body radiation.
    - [Chemistry](https://en.wikipedia.org/wiki/Chemistry): Used to model molecular vibrations.

- **Subfields and concepts it includes**:
    - **Quantization**: The energy of the system is restricted to discrete values.
    - **Zero-Point Energy**: The minimum possible energy of the system is non-zero, a direct consequence of the Heisenberg uncertainty principle.
    - **Creation and Annihilation Operators**: Algebraic methods using ladder operators ($a^\dagger$ and $a$) are often used to solve for the energy spectrum.
    - **Wave Functions**: The stationary states are described by wave functions involving Hermite polynomials.

- **Applications**:
    - **Solid-State Physics**: Describing phonons, which are quantized modes of vibration in a crystal lattice.
    - **Quantum Optics**: Modeling the electromagnetic field in a cavity, leading to the concept of photons.
    - **Molecular Physics**: Approximating the vibrational energy levels of molecules.
    - **Quantum Field Theory**: The vacuum state is the ground state of a collection of quantum harmonic oscillators.

- **More Concrete Variants**:
    - **1D Quantum Harmonic Oscillator**: The simplest case, as described above.
    - **Isotropic 3D Quantum Harmonic Oscillator**: The energy levels depend on the sum of three quantum numbers.

- **More General Variants**:
    - **Quantum Anharmonic Oscillator**: An oscillator with a potential that is not purely quadratic.
    - **Coupled Quantum Oscillators**: A system of multiple interacting quantum oscillators.

- **Related Concepts**:
    - **[Schrödinger Equation](./schrodinger_equation.md)**: The fundamental equation used to determine the energy eigenvalues and eigenstates of the quantum harmonic oscillator.
    - **[Classical Harmonic Oscillator](../../classical_mechanics/harmonic_oscillator.md)**: The quantum harmonic oscillator is its quantum counterpart. The correspondence principle states that for large quantum numbers, the quantum system behaves like the classical one.
    - **Heisenberg Uncertainty Principle**: Explains the existence of zero-point energy.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Quantum_harmonic_oscillator](https://en.wikipedia.org/wiki/Quantum_harmonic_oscillator)
