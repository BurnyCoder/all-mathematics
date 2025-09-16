# AIXI

- **Mathematical Definition**: AIXI is a reinforcement learning agent that interacts with a stochastic and unknown but computable environment $\mu$. The interaction proceeds in discrete time steps from $t=1$ to $m$. At each time step $t$, the agent chooses an action $a_t$ from a set of possible actions $\mathcal{A}$, and the environment responds with a percept $e_t$, which consists of an observation $o_t$ and a reward $r_t$. The agent's goal is to maximize the sum of rewards $\sum_{t=1}^m r_t$. The action at time step $t$ is chosen by the following formula:
$$ a_t := \arg \max_{a_t} \sum_{o_t r_t} \ldots \max_{a_m} \sum_{o_m r_m} [r_t + \ldots + r_m] \sum_{q:\; U(q, a_1 \ldots a_m) = o_1 r_1 \ldots o_m r_m} 2^{-\text{length}(q)} $$
  Here, $U$ is a universal Turing machine, and $q$ is a program that simulates an environment. The sum is over all programs $q$ that are consistent with the past history of interaction. The term $2^{-\text{length}(q)}$ is a weight for each program, which favors shorter programs (a form of Occam's razor). AIXI chooses the action that maximizes its expected future rewards, averaged over all possible environments, weighted by their complexity.

- **Description**: AIXI is a theoretical mathematical formalism for artificial general intelligence (AGI). It provides a universal solution to the problem of an agent acting optimally in an unknown environment. It combines Solomonoff's theory of universal induction with sequential decision theory. In essence, AIXI considers every computable theory of the environment to be possible, weights them by their simplicity (Kolmogorov complexity), and uses this mixture of theories to make decisions. While it is incomputable, it serves as a gold standard for AGI and inspires the development of practical approximations.

- **Subfields it's part of**:
    - [Artificial General Intelligence](https://en.wikipedia.org/wiki/Artificial_general_intelligence): AIXI is a mathematical formalism for AGI, providing a theoretical model of an optimal general agent.
    - [Reinforcement Learning](./reinforcement_learning.md): The AIXI agent is framed within a reinforcement learning setting, where it aims to maximize rewards from an unknown environment.
    - [Algorithmic Information Theory](https://en.wikipedia.org/wiki/Algorithmic_information_theory): AIXI uses concepts from Algorithmic Information Theory, like Kolmogorov complexity, to weigh the plausibility of different environmental models.
    - [Decision Theory](https://en.wikipedia.org/wiki/Decision_theory): The agent's action selection process is an application of sequential decision theory to act optimally under uncertainty.

- **Subfields and concepts it includes**:
    - **Solomonoff Induction**: Used for prediction, by taking a weighted average of all computable hypotheses that explain past observations.
    - **Sequential Decision Theory**: Provides the framework for making optimal decisions under uncertainty to maximize a utility function (in this case, total reward).
    - **Universal Turing Machines**: Used to define the space of all computable environments.
    - **[Probability Theory](../../applied_mathematics/probability_theory/probability_space.md)**: The interaction with a stochastic environment and the maximization of expected rewards are core concepts from probability theory.
        - **[Bayes' Theorem](../../applied_mathematics/probability_theory/bayes_theorem.md)**: Solomonoff's theory of induction, a key component of AIXI, is a Bayesian method for prediction.
    - **Mathematical Optimization**: The agent's action selection is an optimization problem, aiming to maximize future rewards.
    - **[Mathematical Logic](../../../foundations_of_mathematics/logic/first_order_logic.md)**: The foundation of computability theory, which defines the space of possible environments.
    - **[Set Theory](../../../foundations_of_mathematics/set_theory/set.md)**: The action set $\mathcal{A}$ and the space of percepts are defined using sets.

- **Applications**:
    - **Theoretical Benchmark**: Serves as a theoretical benchmark for optimal rational agents.
    - **Game Playing**: Computable approximations of AIXI have been successfully applied to simple games like partially observable Pac-Man.

- **More Concrete Variants**:
    - **AIXI*tl***: A computable but still intractable approximation that is time `t` and space `l` bounded.
    - **MC-AIXI (Monte-Carlo AIXI)**: A tractable approximation using Monte Carlo methods to sample from the space of programs.

- **Related Concepts**:
    - **[Reinforcement Learning](./reinforcement_learning.md)**: AIXI is formulated as a reinforcement learning agent.
    - **[Turing Machine](../../theory_of_computation/turing_machine.md)**: The formalism relies on the concept of a universal Turing machine to model all computable environments.
    - **Solomonoff's theory of inductive inference**: AIXI's prediction model is based on this theory.
    - **Occam's Razor**: The principle of preferring simpler explanations is mathematically formalized through the $2^{-\text{length}(q)}$ weighting.
    - **Computability theory**: The theory is grounded in what is and is not computable.

- **Wikipedia**: [https://en.wikipedia.org/wiki/AIXI](https://en.wikipedia.org/wiki/AIXI)
