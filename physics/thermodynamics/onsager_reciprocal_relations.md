# Onsager Reciprocal Relations

- **Mathematical Definition**: In non-equilibrium thermodynamics, many systems can be described by a set of linear equations relating thermodynamic fluxes ($J_i$) to thermodynamic forces ($X_j$). The Onsager reciprocal relations state that the matrix of phenomenological coefficients ($L_{ij}$) in these equations is symmetric, provided that time-reversal symmetry of the underlying microscopic dynamics holds.
$$ J_i = \sum_{j} L_{ij} X_j $$
The reciprocal relation is:
$$ L_{ij} = L_{ji} $$

- **Description**: These relations, introduced by Lars Onsager, express a fundamental symmetry in the transport properties of a system near thermodynamic equilibrium. They imply that the influence of a force $X_j$ on a flow $J_i$ is the same as the influence of force $X_i$ on flow $J_j$. For example, a temperature gradient can cause a flow of particles (thermodiffusion), and a concentration gradient can cause a flow of heat; the Onsager relations connect the coefficients describing these two effects.

- **Subfields it's part of**:
    - [Non-Equilibrium Thermodynamics](https://en.wikipedia.org/wiki/Non-equilibrium_thermodynamics): A cornerstone of the linear regime of non-equilibrium thermodynamics.
    - [Statistical Mechanics](https://en.wikipedia.org/wiki/Statistical_mechanics): The relations are derived from the principle of microscopic reversibility in statistical mechanics.
    - [Continuum Mechanics](https://en.wikipedia.org/wiki/Continuum_mechanics): Used to formulate constitutive equations for transport phenomena in continuous media.

- **Subfields and concepts it includes**:
    - **Thermodynamic Forces**: Gradients of intensive properties like temperature, pressure, or chemical potential that drive the system away from equilibrium.
    - **Thermodynamic Fluxes**: The resulting flows of quantities like heat, matter, or charge.
    - **Phenomenological Coefficients**: Transport coefficients like thermal conductivity, electrical conductivity, and diffusion coefficients.

- **Applications**:
    - **Thermoelectricity**: They provide the relationship between the Seebeck, Peltier, and Thomson effects.
    - **Thermophoresis and Electrophoresis**: Used in modeling the movement of particles in response to thermal or electric gradients.
    - **Electrokinetic Phenomena**: Describing phenomena like electro-osmosis and streaming potential.
    - **Chemistry**: Modeling coupled chemical reactions near equilibrium.

- **More Concrete Variants**:
    - **Seebeck Effect Coefficient vs. Peltier Effect Coefficient**: The relation between the Seebeck coefficient ($\Pi$) and the Peltier coefficient ($S$) is a direct consequence of the Onsager relations.

- **More General Variants**:
    - **Casimir-Onsager Relations**: A generalization for systems in the presence of magnetic fields or Coriolis forces, where the coefficient matrix becomes anti-symmetric for odd variables under time reversal.
    - **Fluctuation-Dissipation Theorem**: A more general result in statistical mechanics that relates the response of a system to an external perturbation with its internal fluctuations at equilibrium.

- **Related Concepts**:
    - **[Second Law of Thermodynamics](./second_law_of_thermodynamics.md)**: The linear force-flux relations are valid for systems not too far from equilibrium, where entropy production is a key concept.
    - **[Entropy Production](./entropy_production.md)**: The rate of entropy production is a bilinear form of forces and fluxes, and the Onsager relations constrain the coefficients of this form.
    - **Linear Response Theory**: A broader framework for studying the response of a system to small external perturbations.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Onsager_reciprocal_relations](https://en.wikipedia.org/wiki/Onsager_reciprocal_relations)
