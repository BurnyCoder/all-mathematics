# Reinforcement Learning

- **Mathematical Definition**: Reinforcement learning (RL) is an area of machine learning concerned with how an **agent** takes **actions** in an **environment** to maximize some notion of cumulative **reward**. The problem is typically formalized as a **Markov Decision Process (MDP)**, which is a tuple $(\mathcal{S}, \mathcal{A}, P, R, \gamma)$:
    - $\mathcal{S}$ is the set of **states**.
    - $\mathcal{A}$ is the set of **actions**.
    - $P(s'|s, a)$ is the **transition probability** of moving from state $s$ to state $s'$ after taking action $a$.
    - $R(s, a, s')$ is the immediate **reward** received after transitioning from $s$ to $s'$ due to action $a$.
    - $\gamma \in [0, 1]$ is the **discount factor**, which trades off the importance of immediate versus future rewards.
The goal of the agent is to learn a **policy** $\pi(a|s)$, which is a strategy for choosing actions in given states, that maximizes the expected cumulative discounted reward.

- **Description**: Reinforcement learning is one of the three main paradigms of machine learning, alongside supervised and unsupervised learning. It is inspired by behaviorist psychology. The agent learns by trial and error, receiving feedback in the form of rewards or punishments. It is particularly suited for problems that involve sequential decision-making and control.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence)
    - [Control Theory](https://en.wikipedia.org/wiki/Control_theory)

- **Subfields and concepts it includes**:
    - **Markov Decision Process (MDP)**: The mathematical framework for modeling RL problems.
    - **Policy**: The strategy of the agent.
    - **Value Function**: A function that estimates the expected long-term return of being in a certain state.
    - **Q-Learning**: A popular model-free RL algorithm.
    - **Exploration vs. Exploitation Trade-off**: The dilemma of choosing between trying new actions to discover their rewards (exploration) and choosing actions that are known to yield high rewards (exploitation).

- **Applications**:
    - **Robotics**: Training robots to perform complex tasks like walking and manipulation.
    - **Game Playing**: RL agents have achieved superhuman performance in games like Go (AlphaGo), chess, and video games (AlphaStar, OpenAI Five).
    - **Autonomous Driving**: Used for tasks like lane keeping and trajectory optimization.
    - **Resource Management**: Optimizing the operation of data centers and power grids.
    - **Personalized Recommendations**: Optimizing which items to recommend to users.

- **More Concrete Variants**:
    - **Q-Learning**: A value-based algorithm.
    - **Policy Gradient Methods**: Algorithms that directly optimize the policy.
    - **Actor-Critic Methods**: A hybrid approach that combines value-based and policy-based methods.
    - **Deep Reinforcement Learning**: The use of deep [neural networks](../machine_learning/artificial_neural_network.md) as function approximators in RL.

- **More General Variants**:
    - **Partially Observable Markov Decision Process (POMDP)**: A generalization of MDPs where the agent does not have complete information about the state of the environment.

- **Related Concepts**:
    - **[Optimal Control](../control_theory/optimal_control.md)**: The field from which many of the mathematical ideas of RL originated.
    - **[Artificial Neural Network](../machine_learning/artificial_neural_network.md)**: Deep RL uses neural networks to represent policies or value functions, allowing it to scale to complex, high-dimensional problems.
    - **[Probability Theory](../../applied_mathematics/probability_theory/probability_space.md)**: MDPs are stochastic processes.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Reinforcement_learning](https://en.wikipedia.org/wiki/Reinforcement_learning)
