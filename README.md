# All Mathematics

This repository aims to be a comprehensive, interconnected knowledge base of mathematical concepts from pure mathematics and applied mathematics, from the general to the concrete, from the foundational to the applied, showing the rich web of connections between them.

**Warning**: This project has a lot of AI assisted structuring of a lot of information and human double checking might have missed corrections of some hallucinations. Make sure to double check with Google, Wikipedia, etc.

## Structure

The content is organized hierarchically into major fields. Each concept has its own file, detailing its definition, applications, variants, and relationships to other concepts.

## Main Areas

- [**Foundations of Mathematics**](./foundations_of_mathematics/README.md)
  - The bedrock of mathematical thought, including logic, set theory, and category theory.

- [**Pure Mathematics**](./pure_mathematics/README.md)
  - The study of mathematical concepts independently of any application outside mathematics.

- [**Applied Mathematics**](./applied_mathematics/README.md)
  - The application of mathematical methods to different fields such as science, engineering, business, and industry.

- [**Physics**](./physics/README.md)
  - The natural science that studies matter, its fundamental constituents, its motion and behavior through space and time, and the related entities of energy and force.

- [**Computer Science**](./computer_science/README.md)
  - The study of computation, information, and automation, with deep roots in mathematical logic. Includes topics like Artificial Intelligence and Machine Learning.

## Ways to Explore

This knowledge base can be navigated in several ways:

- **By Field**: Start from one of the main areas above and dive into specific subfields. See the comprehensive [List of Concepts by Field](./_lists/by_field.md).
- **By Generality**: A list of concepts organized from the most abstract and general to the most concrete. See the [List of Concepts by Generality](./_lists/by_generality.md).
- **By Application**: A list of concepts organized by their field of application. See the [List of Concepts by Application](./_lists/by_application.md).
- **Graphical View**: (Coming soon) A graph visualizing the connections between concepts.

## File Structure

```
.
├── README.md
├── _lists
│   ├── by_application.md
│   ├── by_field.md
│   └── by_generality.md
├── applied_mathematics
│   ├── README.md
│   ├── differential_equations
│   │   ├── black_scholes_equation.md
│   │   ├── differential_equation.md
│   │   └── lotka_volterra_equations.md
│   └── statistics
│       ├── README.md
│       └── correlation.md
├── computer_science
│   ├── README.md
│   ├── algorithms_and_data_structures
│   │   └── algorithm.md
│   ├── artificial_intelligence
│   │   ├── aixi.md
│   │   ├── chollets_mathematical_definition_of_intelligence.md
│   │   ├── machine_learning
│   │   │   ├── README.md
│   │   │   ├── deep_learning
│   │   │   │   ├── artificial_neural_network.md
│   │   │   │   ├── cnn.md
│   │   │   │   ├── lstm.md
│   │   │   │   ├── neural_tangent_kernel.md
│   │   │   │   ├── rnn.md
│   │   │   │   ├── transformer.md
│   │   │   │   └── universal_approximation_theorem.md
│   │   │   ├── gradient_descent.md
│   │   │   ├── regression_analysis.md
│   │   │   └── svm.md
│   │   ├── monte_carlo_method
│   │   │   ├── markov_chain_monte_carlo.md
│   │   │   ├── monte_carlo_method.md
│   │   │   └── monte_carlo_tree_search.md
│   │   └── reinforcement_learning.md
│   ├── information_theory
│   │   ├── algorithmic_information_theory.md
│   │   └── entropy.md
│   └── theory_of_computation
│       ├── halting_problem.md
│       └── turing_machine.md
├── foundations_of_mathematics
│   ├── README.md
│   ├── category_theory
│   │   ├── category.md
│   │   ├── topos_theory
│   │   │   └── topos.md
│   │   └── yoneda_lemma.md
│   ├── logic
│   │   ├── first_order_logic.md
│   │   ├── godels_incompleteness_theorems.md
│   │   ├── lambda_calculus.md
│   │   ├── modal_logic.md
│   │   ├── proof theory
│   │   └── propositional_logic.md
│   ├── model_theory
│   │   └── structure.md
│   ├── set_theory
│   │   ├── set.md
│   │   └── zermelo_fraenkel_set_theory_with_the_axiom_of_choice.md
│   └── type_theory
│       └── type_theory.md
├── physics
│   ├── README.md
│   ├── analytical_mechanics
│   │   ├── hamiltonian_mechanics.md
│   │   ├── lagrangian_mechanics.md
│   │   ├── noethers_theorem.md
│   │   └── principle_of_least_action.md
│   ├── classical_mechanics
│   │   ├── harmonic_oscillator.md
│   │   └── newtons_laws.md
│   ├── electromagnetism
│   │   └── maxwells_equations.md
│   ├── fluid_dynamics
│   │   └── navier_stokes_equations.md
│   ├── general_relativity
│   │   └── einstein_field_equations.md
│   ├── heat_equation.md
│   ├── particle_physics
│   │   └── standard_model.md
│   ├── quantum_field_theory
│   │   └── quantum_field_theory.md
│   ├── quantum_mechanics
│   │   ├── quantum_harmonic_oscillator.md
│   │   └── schrodinger_equation.md
│   ├── special_relativity
│   │   └── special_relativity.md
│   ├── string_theory
│   │   └── string_theory.md
│   ├── thermodynamics
│   │   ├── README.md
│   │   ├── boltzmanns_entropy_formula.md
│   │   ├── entropy_production.md
│   │   ├── first_law_of_thermodynamics.md
│   │   ├── ideal_gas_law.md
│   │   ├── onsager_reciprocal_relations.md
│   │   └── second_law_of_thermodynamics.md
│   └── wave_equation.md
└── pure_mathematics
    ├── README.md
    ├── algebra
    │   ├── boolean_algebra.md
    │   ├── field.md
    │   ├── function.md
    │   ├── group.md
    │   ├── lattice.md
    │   ├── magma.md
    │   ├── monoid.md
    │   ├── relation.md
    │   ├── ring.md
    │   └── semigroup.md
    ├── analysis
    │   ├── complex_analysis
    │   │   └── eulers_identity.md
    │   ├── continuity.md
    │   ├── derivative.md
    │   ├── integral.md
    │   ├── limit.md
    │   ├── measure_theory
    │   │   ├── README.md
    │   │   ├── measure.md
    │   │   └── sigma_algebra.md
    │   ├── real_analysis
    │   │   └── completeness_of_the_reals.md
    │   ├── real_number.md
    │   └── taylor_series.md
    ├── discrete_mathematics
    │   ├── combinatorics
    │   │   └── combinations_and_permutations.md
    │   └── graph_theory
    │       └── graph.md
    ├── geometry
    │   └── manifold.md
    ├── linear_algebra
    │   ├── eigenvectors_and_eigenvalues.md
    │   ├── linear_transformation.md
    │   ├── matrix.md
    │   └── vector_space.md
    ├── number_theory
    │   └── fundamental_theorem_of_arithmetic.md
    ├── probability_theory
    │   ├── bayes_theorem.md
    │   ├── central_limit_theorem.md
    │   ├── law_of_large_numbers.md
    │   ├── normal_distribution.md
    │   ├── probability_space.md
    │   └── random_variable.md
    └── topology
        ├── metric_space.md
        └── topological_space.md
```
