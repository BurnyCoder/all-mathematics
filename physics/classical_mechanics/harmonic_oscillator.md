# Harmonic Oscillator

- **Mathematical Definition**: A classical harmonic oscillator is a system that, when displaced from its equilibrium position, experiences a restoring force $F$ proportional to the displacement $x$ (Hooke's Law):
$$ F = -k x $$
  where $k$ is a positive constant (the spring constant). Using Newton's second law ($F=ma$), this results in the second-order linear ordinary differential equation:
$$ m \frac{d^2x}{dt^2} + kx = 0 $$
  The solution to this equation describes simple harmonic motion:
$$ x(t) = A \cos(\omega t + \phi) $$
  where:
    - $A$ is the amplitude, the maximum displacement from equilibrium.
    - $\omega = \sqrt{k/m}$ is the angular frequency.
    - $\phi$ is the phase constant.

- **Description**: The harmonic oscillator is a fundamental model in physics for describing oscillations. Its motion is periodic and sinusoidal. It serves as a prototype for any system in a stable equilibrium, as any potential can be approximated by a harmonic potential at the bottom of a potential well.

- **Subfields it's part of**:
    - [Classical Mechanics](https://en.wikipedia.org/wiki/Classical_mechanics): It is a cornerstone model for oscillatory systems like springs and pendulums.
    - [Physics](https://en.wikipedia.org/wiki/Physics): The concept is ubiquitous in almost all areas of physics.
    - [Differential Equations](https://en.wikipedia.org/wiki/Differential_equation): The equation of motion is a key example of a second-order ODE.

- **Subfields and concepts it includes**:
    - **Simple Harmonic Motion**: The type of motion exhibited by a simple harmonic oscillator.
    - **Frequency and Period**: Key characteristics of the oscillation.
    - **Amplitude and Phase**: Parameters determined by the initial conditions of the system.
    - **Potential Energy**: The potential energy of a harmonic oscillator is quadratic: $U(x) = \frac{1}{2}kx^2$.

- **Applications**:
    - **Mechanical Engineering**: Modeling vibrations in structures, vehicle suspensions.
    - **Electrical Engineering**: The behavior of RLC circuits is described by a harmonic oscillator equation.
    - **Acoustics**: Modeling sound waves and musical instruments.
    - **Molecular Physics**: Approximating the vibrations of atoms in a molecule.

- **More Concrete Variants**:
    - **Simple Pendulum**: For small angles, a simple pendulum approximates a harmonic oscillator.
    - **Mass-Spring System**: The canonical example of a harmonic oscillator.
    - **RLC Circuit**: An electrical circuit that exhibits damped and driven harmonic oscillations.

- **More General Variants**:
    - **Damped Harmonic Oscillator**: Includes a frictional force, causing the oscillations to decay over time.
    - **Driven Harmonic Oscillator**: Includes an external driving force, which can lead to resonance.
    - **Anharmonic Oscillator**: A system where the restoring force is not proportional to the displacement.
    - **[Quantum Harmonic Oscillator](../../quantum_mechanics/quantum_harmonic_oscillator.md)**: The quantum mechanical analogue, which has quantized energy levels.

- **Related Concepts**:
    - **[Lagrangian Mechanics](../analytical_mechanics/lagrangian_mechanics.md)**: The harmonic oscillator can be described using a Lagrangian.
    - **[Hamiltonian Mechanics](../analytical_mechanics/hamiltonian_mechanics.md)**: The harmonic oscillator can also be described using a Hamiltonian.
    - **Fourier Series**: Any periodic motion can be decomposed into a sum of simple harmonic motions.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Harmonic_oscillator](https://en.wikipedia.org/wiki/Harmonic_oscillator)
