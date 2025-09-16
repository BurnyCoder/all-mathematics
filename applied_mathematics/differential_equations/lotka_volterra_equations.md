# Lotka-Volterra Equations

- **Mathematical Definition**: The Lotka-Volterra equations, also known as the predator-prey equations, are a pair of first-order nonlinear ordinary differential equations. They describe the dynamics of biological systems in which two species interact, one as a predator and the one as prey. The equations are:
$$ \frac{dx}{dt} = \alpha x - \beta xy $$
$$ \frac{dy}{dt} = \delta xy - \gamma y $$
  where:
  - $x$ is the number of prey.
  - $y$ is the number of predators.
  - $t$ represents time.
  - $\alpha, \beta, \gamma, \delta$ are positive real parameters describing the interaction of the two species.

- **Description**: The Lotka-Volterra model makes a number of simplifying assumptions, such as the prey population finding ample food at all times, the predator population growth rate being proportional to the size of the prey population, and so on. The model predicts a cyclical relationship between predator and prey populations, where peaks in the predator population lag behind peaks in the prey population.

- **Subfields it's part of**:
    - [Mathematical Biology](https://en.wikipedia.org/wiki/Mathematical_and_theoretical_biology): It's a foundational model in population dynamics.
    - [Dynamical Systems](https://en.wikipedia.org/wiki/Dynamical_system): The equations describe the evolution of a system over time.
    - [Nonlinear Systems](https://en.wikipedia.org/wiki/Nonlinear_system): The equations are nonlinear due to the $xy$ term.

- **Subfields and concepts it includes**:
    - [Ordinary Differential Equations](https://en.wikipedia.org/wiki/Ordinary_differential_equation): The model consists of a system of ODEs.
    - [Equilibrium points](https://en.wikipedia.org/wiki/Equilibrium_point): The system has equilibrium points (fixed points) where the populations do not change. Analysis of the stability of these points is a key part of studying the system.
    - [Phase space analysis](https://en.wikipedia.org/wiki/Phase_space): The dynamics can be visualized in a phase plane, plotting the predator population against the prey population.

- **Applications**:
    - **Ecology**: Modeling predator-prey interactions, such as lynx and snowshoe hare populations.
    - **Economics**: Modeling competition and symbiotic relationships between industries.
    - **Chemistry**: Modeling oscillating chemical reactions.
    - **Epidemiology**: Can be adapted to model the spread of infectious diseases.

- **More Concrete Variants**:
    - **Competitive Lotka-Volterra equations**: Models competition between two species for the same resources.

- **More General Variants**:
    - **Models with carrying capacity**: The logistic equation can be incorporated to model the effect of limited resources on the prey population.
    - **Multi-species models**: The model can be extended to include more than two species, leading to more complex dynamics.
    - **Models with functional response**: The rate of predation can be modeled more realistically as a function of prey density.

- **Related Concepts**:
    - **[Logistic Growth](https://en.wikipedia.org/wiki/Logistic_function)**: Often combined with Lotka-Volterra to make the model more realistic by introducing a carrying capacity for the prey.
    - **[SIR model](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology)**: Another system of ODEs used in epidemiology to model the spread of disease.
    - **[Chaos Theory](https://en.wikipedia.org/wiki/Chaos_theory)**: Extensions of the Lotka-Volterra model can exhibit chaotic behavior.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations](https://en.wikipedia.org/wiki/Lotka%E2%80%93Volterra_equations)
