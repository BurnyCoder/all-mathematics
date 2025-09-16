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

├── [All Mathematics](./README.md)

├── **_lists**

│   ├── [Concepts by Application](./_lists/by_application.md)

│   ├── [Concepts Organized by Field](./_lists/by_field.md)

│   └── [Concepts by Generality](./_lists/by_generality.md)

├── [**applied_mathematics**](./applied_mathematics/README.md)

│   ├── **differential_equations**

│   │   ├── [Black-Scholes Equation](./applied_mathematics/differential_equations/black_scholes_equation.md)

│   │   ├── [Differential Equation](./applied_mathematics/differential_equations/differential_equation.md)

│   │   └── [Lotka-Volterra Equations](./applied_mathematics/differential_equations/lotka_volterra_equations.md)

│   └── [**statistics**](./applied_mathematics/statistics/README.md)

│       └── [Correlation](./applied_mathematics/statistics/correlation.md)

├── [**computer_science**](./computer_science/README.md)

│   ├── **algorithms_and_data_structures**

│   │   └── [Algorithm](./computer_science/algorithms_and_data_structures/algorithm.md)

│   ├── **artificial_intelligence**

│   │   ├── [AIXI](./computer_science/artificial_intelligence/aixi.md)

│   │   ├── [Chollet's Measure of Intelligence](./computer_science/artificial_intelligence/chollets_mathematical_definition_of_intelligence.md)

│   │   ├── [**machine_learning**](./computer_science/artificial_intelligence/machine_learning/README.md)

│   │   │   ├── **deep_learning**

│   │   │   │   ├── [Artificial Neural Network](./computer_science/artificial_intelligence/machine_learning/deep_learning/artificial_neural_network.md)

│   │   │   │   ├── [Convolutional Neural Network (CNN)](./computer_science/artificial_intelligence/machine_learning/deep_learning/cnn.md)

│   │   │   │   ├── [Long Short-Term Memory (LSTM)](./computer_science/artificial_intelligence/machine_learning/deep_learning/lstm.md)

│   │   │   │   ├── [Neural Tangent Kernel](./computer_science/artificial_intelligence/machine_learning/deep_learning/neural_tangent_kernel.md)

│   │   │   │   ├── [Recurrent Neural Network (RNN)](./computer_science/artificial_intelligence/machine_learning/deep_learning/rnn.md)

│   │   │   │   ├── [Transformer](./computer_science/artificial_intelligence/machine_learning/deep_learning/transformer.md)

│   │   │   │   └── [Universal Approximation Theorem](./computer_science/artificial_intelligence/machine_learning/deep_learning/universal_approximation_theorem.md)

│   │   │   ├── [Gradient Descent](./computer_science/artificial_intelligence/machine_learning/gradient_descent.md)

│   │   │   ├── [Regression Analysis](./computer_science/artificial_intelligence/machine_learning/regression_analysis.md)

│   │   │   └── [Support Vector Machine (SVM)](./computer_science/artificial_intelligence/machine_learning/svm.md)

│   │   ├── **monte_carlo_method**

│   │   │   ├── [Markov Chain Monte Carlo](./computer_science/artificial_intelligence/monte_carlo_method/markov_chain_monte_carlo.md)

│   │   │   ├── [Monte Carlo Method](./computer_science/artificial_intelligence/monte_carlo_method/monte_carlo_method.md)

│   │   │   └── [Monte Carlo Tree Search](./computer_science/artificial_intelligence/monte_carlo_method/monte_carlo_tree_search.md)

│   │   └── [Reinforcement Learning](./computer_science/artificial_intelligence/reinforcement_learning.md)

│   ├── **information_theory**

│   │   ├── [Algorithmic Information Theory](./computer_science/information_theory/algorithmic_information_theory.md)

│   │   └── [Shannon Entropy](./computer_science/information_theory/entropy.md)

│   └── **theory_of_computation**

│       ├── [Halting Problem](./computer_science/theory_of_computation/halting_problem.md)

│       └── [Turing Machine](./computer_science/theory_of_computation/turing_machine.md)

├── [**foundations_of_mathematics**](./foundations_of_mathematics/README.md)

│   ├── **category_theory**

│   │   ├── [Category](./foundations_of_mathematics/category_theory/category.md)

│   │   ├── **topos_theory**

│   │   │   └── [Topos](./foundations_of_mathematics/category_theory/topos_theory/topos.md)

│   │   └── [Yoneda Lemma](./foundations_of_mathematics/category_theory/yoneda_lemma.md)

│   ├── **logic**

│   │   ├── [First-Order Logic](./foundations_of_mathematics/logic/first_order_logic.md)

│   │   ├── [Gödel's Incompleteness Theorems](./foundations_of_mathematics/logic/godels_incompleteness_theorems.md)

│   │   ├── [Lambda Calculus](./foundations_of_mathematics/logic/lambda_calculus.md)

│   │   ├── [Modal Logic](./foundations_of_mathematics/logic/modal_logic.md)

│   │   ├── **proof theory**

│   │   └── [Propositional Logic](./foundations_of_mathematics/logic/propositional_logic.md)

│   ├── **model_theory**

│   │   └── [Structure (Model Theory)](./foundations_of_mathematics/model_theory/structure.md)

│   ├── **set_theory**

│   │   ├── [Set](./foundations_of_mathematics/set_theory/set.md)

│   │   └── [Zermelo–Fraenkel Set Theory with the Axiom of Choice (ZFC)](./foundations_of_mathematics/set_theory/zermelo_fraenkel_set_theory_with_the_axiom_of_choice.md)

│   └── **type_theory**

│       └── [Type Theory](./foundations_of_mathematics/type_theory/type_theory.md)

├── [**physics**](./physics/README.md)

│   ├── **analytical_mechanics**

│   │   ├── [Hamiltonian Mechanics](./physics/analytical_mechanics/hamiltonian_mechanics.md)

│   │   ├── [Lagrangian Mechanics](./physics/analytical_mechanics/lagrangian_mechanics.md)

│   │   ├── [Noether's Theorem](./physics/analytical_mechanics/noethers_theorem.md)

│   │   └── [Principle of Least Action](./physics/analytical_mechanics/principle_of_least_action.md)

│   ├── **classical_mechanics**

│   │   ├── [Harmonic Oscillator](./physics/classical_mechanics/harmonic_oscillator.md)

│   │   └── [Newton's Laws of Motion](./physics/classical_mechanics/newtons_laws.md)

│   ├── **electromagnetism**

│   │   └── [Maxwell's Equations](./physics/electromagnetism/maxwells_equations.md)

│   ├── **fluid_dynamics**

│   │   └── [Navier-Stokes Equations](./physics/fluid_dynamics/navier_stokes_equations.md)

│   ├── **general_relativity**

│   │   └── [Einstein's Field Equations](./physics/general_relativity/einstein_field_equations.md)

│   ├── [Heat Equation](./physics/heat_equation.md)

│   ├── **particle_physics**

│   │   └── [The Standard Model of Particle Physics](./physics/particle_physics/standard_model.md)

│   ├── **quantum_field_theory**

│   │   └── [Quantum Field Theory](./physics/quantum_field_theory/quantum_field_theory.md)

│   ├── **quantum_mechanics**

│   │   ├── [Quantum Harmonic Oscillator](./physics/quantum_mechanics/quantum_harmonic_oscillator.md)

│   │   └── [Schrödinger Equation](./physics/quantum_mechanics/schrodinger_equation.md)

│   ├── **special_relativity**

│   │   └── [Special Relativity](./physics/special_relativity/special_relativity.md)

│   ├── **string_theory**

│   │   └── [String Theory](./physics/string_theory/string_theory.md)

│   ├── [**thermodynamics**](./physics/thermodynamics/README.md)

│   │   ├── [Boltzmann's Entropy Formula](./physics/thermodynamics/boltzmanns_entropy_formula.md)

│   │   ├── [Entropy Production](./physics/thermodynamics/entropy_production.md)

│   │   ├── [First Law of Thermodynamics](./physics/thermodynamics/first_law_of_thermodynamics.md)

│   │   ├── [Ideal Gas Law](./physics/thermodynamics/ideal_gas_law.md)

│   │   ├── [Onsager Reciprocal Relations](./physics/thermodynamics/onsager_reciprocal_relations.md)

│   │   └── [Second Law of Thermodynamics](./physics/thermodynamics/second_law_of_thermodynamics.md)

│   └── [Wave Equation](./physics/wave_equation.md)

└── [**pure_mathematics**](./pure_mathematics/README.md)

│   ├── **algebra**

│   │   ├── [Boolean Algebra](./pure_mathematics/algebra/boolean_algebra.md)

│   │   ├── [Field](./pure_mathematics/algebra/field.md)

│   │   ├── [Function](./pure_mathematics/algebra/function.md)

│   │   ├── [Group](./pure_mathematics/algebra/group.md)

│   │   ├── [Lattice](./pure_mathematics/algebra/lattice.md)

│   │   ├── [Magma (or Groupoid)](./pure_mathematics/algebra/magma.md)

│   │   ├── [Monoid](./pure_mathematics/algebra/monoid.md)

│   │   ├── [Relation](./pure_mathematics/algebra/relation.md)

│   │   ├── [Ring](./pure_mathematics/algebra/ring.md)

│   │   └── [Semigroup](./pure_mathematics/algebra/semigroup.md)

│   ├── **analysis**

│   │   ├── **complex_analysis**

│   │   │   └── [Euler's Identity](./pure_mathematics/analysis/complex_analysis/eulers_identity.md)

│   │   ├── [Continuity](./pure_mathematics/analysis/continuity.md)

│   │   ├── [Derivative](./pure_mathematics/analysis/derivative.md)

│   │   ├── [Integral](./pure_mathematics/analysis/integral.md)

│   │   ├── [Limit (Calculus)](./pure_mathematics/analysis/limit.md)

│   │   ├── [**measure_theory**](./pure_mathematics/analysis/measure_theory/README.md)

│   │   │   ├── [Measure](./pure_mathematics/analysis/measure_theory/measure.md)

│   │   │   └── [σ-algebra](./pure_mathematics/analysis/measure_theory/sigma_algebra.md)

│   │   ├── **real_analysis**

│   │   │   └── [Completeness of the Real Numbers](./pure_mathematics/analysis/real_analysis/completeness_of_the_reals.md)

│   │   ├── [Real Number](./pure_mathematics/analysis/real_number.md)

│   │   └── [Taylor Series](./pure_mathematics/analysis/taylor_series.md)

│   ├── **discrete_mathematics**

│   │   ├── **combinatorics**

│   │   │   └── [Combinations and Permutations](./pure_mathematics/discrete_mathematics/combinatorics/combinations_and_permutations.md)

│   │   └── **graph_theory**

│   │       └── [Graph (Graph Theory)](./pure_mathematics/discrete_mathematics/graph_theory/graph.md)

│   ├── **geometry**

│   │   └── [Manifold](./pure_mathematics/geometry/manifold.md)

│   ├── **linear_algebra**

│   │   ├── [Eigenvectors and Eigenvalues](./pure_mathematics/linear_algebra/eigenvectors_and_eigenvalues.md)

│   │   ├── [Linear Transformation](./pure_mathematics/linear_algebra/linear_transformation.md)

│   │   ├── [Matrix](./pure_mathematics/linear_algebra/matrix.md)

│   │   └── [Vector Space](./pure_mathematics/linear_algebra/vector_space.md)

│   ├── **number_theory**

│   │   └── [Fundamental Theorem of Arithmetic](./pure_mathematics/number_theory/fundamental_theorem_of_arithmetic.md)

│   ├── **probability_theory**

│   │   ├── [Bayes' Theorem](./pure_mathematics/probability_theory/bayes_theorem.md)

│   │   ├── [Central Limit Theorem](./pure_mathematics/probability_theory/central_limit_theorem.md)

│   │   ├── [Law of Large Numbers](./pure_mathematics/probability_theory/law_of_large_numbers.md)

│   │   ├── [Normal Distribution](./pure_mathematics/probability_theory/normal_distribution.md)

│   │   ├── [Probability Space](./pure_mathematics/probability_theory/probability_space.md)

│   │   └── [Random Variable](./pure_mathematics/probability_theory/random_variable.md)

│   └── **topology**

│   ├── [Metric Space](./pure_mathematics/topology/metric_space.md)

│   └── [Topological Space](./pure_mathematics/topology/topological_space.md)