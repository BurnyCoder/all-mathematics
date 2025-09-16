# Maxwell's Equations

## Mathematical Definition

Maxwell's equations are a set of four coupled [partial differential equations](../../../08_Applied_Mathematics/00_Differential_Equations/Differential_Equation.md) that, together with the Lorentz force law, form the foundation of classical electromagnetism, classical optics, and electric circuits.

The equations are most commonly expressed in their differential form, which describes the relationships between the fields at a point in space.

1.  **Gauss's Law for Electricity:** Describes how electric charges create electric fields.
    \[ \nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0} \]
    (\(\nabla \cdot\) is the divergence operator, \(\mathbf{E}\) is the electric field, \(\rho\) is the electric charge density, and \(\varepsilon_0\) is the permittivity of free space.)

2.  **Gauss's Law for Magnetism:** States that there are no magnetic monopoles.
    \[ \nabla \cdot \mathbf{B} = 0 \]
    (\(\mathbf{B}\) is the magnetic field.)

3.  **Faraday's Law of Induction:** Describes how a time-varying magnetic field creates an electric field.
    \[ \nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t} \]
    (\(\nabla \times\) is the curl operator, and \(\frac{\partial}{\partial t}\) is the partial time derivative.)

4.  **Ampère's Law with Maxwell's Addition:** Describes how an electric current and a time-varying electric field create a magnetic field.
    \[ \nabla \times \mathbf{B} = \mu_0 \left( \mathbf{J} + \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t} \right) \]
    (\(\mu_0\) is the permeability of free space, and \(\mathbf{J}\) is the current density.)

These equations can also be written in an integral form, which relates the fields over a surface or a volume. A more advanced and elegant formulation uses the language of tensor calculus and differential forms, which is essential for the relativistic form of the equations.

## Description

Maxwell's equations are a complete description of the behavior of electric and magnetic fields. They unified electricity and magnetism into a single theory of electromagnetism and, remarkably, predicted the existence of electromagnetic waves that travel at the speed of light. This led to the conclusion that light itself is an electromagnetic wave.

## Subfields it's part of

*   [Electromagnetism](./)
*   Classical Field Theory
*   Physics

## Subfields and concepts it includes

*   **Electric Field (\(\mathbf{E}\)) and Magnetic Field (\(\mathbf{B}\))**: Vector fields that describe the electric and magnetic influence in space.
*   **Electric Charge (\(\rho\)) and Current (\(\mathbf{J}\))**: The sources of the electric and magnetic fields.
*   **Vector Calculus**: The mathematical language of Maxwell's equations (divergence and curl).
*   **Electromagnetic Waves**: The equations predict that oscillating electric and magnetic fields can propagate through space as waves. The speed of these waves in a vacuum is the speed of light, \(c = 1/\sqrt{\varepsilon_0 \mu_0}\).
*   **Lorentz Force**: The force exerted by electric and magnetic fields on a charged particle: \(\mathbf{F} = q(\mathbf{E} + \mathbf{v} \times \mathbf{B})\).

## Applications

*   **Electrical Engineering**: Design of antennas, waveguides, electric motors, generators, and circuits.
*   **Optics**: As light is an electromagnetic wave, Maxwell's equations are the foundation of classical optics.
*   **Telecommunications**: Describe the propagation of radio waves, microwaves, and other forms of wireless communication.
*   **Medical Technology**: Magnetic Resonance Imaging (MRI) is based on the principles of electromagnetism.

## More general variants

*   **Quantum Electrodynamics (QED)**: The quantum field theory of electromagnetism. It describes how light and matter interact and is the first theory where quantum mechanics and special relativity were successfully combined.
*   **General Relativity**: Maxwell's equations can be formulated in the context of curved spacetime, which is necessary for describing the propagation of light in strong gravitational fields.

## More concrete variants

*   **Electrostatics**: The study of stationary charges and their electric fields (when \(\mathbf{B}\) is constant and \(\mathbf{J}=0\)).
*   **Magnetostatics**: The study of steady currents and their magnetic fields (when \(\mathbf{E}\) is constant).

## Everything else it relates to

*   **Special Relativity**: Maxwell's equations are inherently relativistic. The theory of special relativity was developed in part to resolve inconsistencies between classical mechanics and electromagnetism. The electric and magnetic fields are unified into a single electromagnetic tensor in the relativistic formulation.
*   **Differential Equations**: They are a system of partial differential equations.
*   **Manifolds and Differential Forms**: In this more advanced language, Maxwell's equations take on a very compact and elegant form.
*   **Vector Calculus**: The divergence and curl operators are central to the differential form of the equations.
*   **Integral Calculus**: The integral form of the equations relates integrals over surfaces and volumes.
