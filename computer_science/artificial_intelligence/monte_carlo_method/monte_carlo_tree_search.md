# Monte Carlo Tree Search

- **Mathematical Definition**: Monte Carlo Tree Search (MCTS) is an algorithm for finding optimal decisions in a given domain by taking random samples in the decision space and building a search tree according to the results. MCTS is a probabilistic and heuristic-driven search algorithm that combines the precision of tree search with the generality of random sampling. The core of the algorithm is the Upper Confidence bound applied to Trees (UCT) formula, which is used to select which node to explore. To balance exploitation and exploration, the child node $i$ that maximizes the following expression is chosen:
$$ \frac{w_i}{n_i} + c \sqrt{\frac{\ln N_i}{n_i}} $$
  where:
  - $w_i$ is the number of wins for the node considered after the i-th move.
  - $n_i$ is the number of simulations for the node considered after the i-th move.
  - $N_i$ is the total number of simulations for the parent of the node considered after the i-th move.
  - $c$ is the exploration parameter (theoretically $\sqrt{2}$).
The algorithm iterates through four main phases: Selection, Expansion, Simulation, and Backpropagation.

- **Description**: MCTS is a heuristic search algorithm used for decision-making in some kinds of decision processes, especially for game playing. It builds a search tree by randomly sampling the search space. The results of these random "playouts" are used to weight the nodes in the tree, so that more promising nodes are more likely to be chosen in future iterations. This allows the search to focus on more promising parts of the game tree.

- **Subfields it's part of**:
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence): MCTS is a key algorithm in AI for planning and game playing.
    - [Search Algorithms](https://en.wikipedia.org/wiki/Search_algorithm): It is a type of heuristic search algorithm.
    - [Game Theory](https://en.wikipedia.org/wiki/Game_theory): It's widely used to find optimal strategies in two-player games.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science)

- **Subfields and concepts it includes**:
    - **Selection**: Traversing the existing tree from the root by repeatedly selecting the child with the highest UCT value.
    - **Expansion**: When a leaf node is reached, one or more child nodes are added to the tree for valid moves from that position.
    - **Simulation (Rollout)**: From a newly expanded node, a simulation is run to the end of the game. This is typically done by choosing moves randomly or with a simple policy.
    - **Backpropagation**: The outcome of the simulation is propagated back up the tree to the root, updating the visit counts ($n_i$) and win counts ($w_i$) for all visited nodes.
    - **Game Tree**: The tree of all possible states and moves in a game, which MCTS partially explores.
    - **Exploration vs. Exploitation**: A fundamental trade-off in decision-making, managed in MCTS by the UCT formula.
    - **[Monte Carlo method](./monte_carlo_method.md)**: A broad class of computational algorithms that rely on repeated random sampling to obtain numerical results. MCTS applies this to tree search.
    - **Upper Confidence Bound (UCB)**: A formula used to address the exploration-exploitation dilemma in multi-armed bandit problems, adapted for trees in UCT.
    - **[Probability Theory](../probability_theory/):** The "Monte Carlo" aspect of MCTS is fundamentally based on probability. The simulation (or rollout) phase involves random sampling of move sequences to estimate the value of a game state.
    - **[Graph Theory](../../pure_mathematics/discrete_mathematics/graph_theory/graph.md):** The "Tree Search" aspect of MCTS is an application of graph theory. The algorithm incrementally builds and explores a game tree, where nodes represent game states and edges represent moves.
    - **[Statistics](../statistics/):** The algorithm uses basic statistical measures. The win rate $\frac{w_i}{n_i}$ is a statistical estimate of a move's quality, and the UCT formula is derived from statistical principles to manage the exploration-exploitation tradeoff.
    - **[Analysis](../../pure_mathematics/analysis/):** The UCT formula uses the [natural logarithm](../../pure_mathematics/analysis/logarithm.md), a concept from mathematical analysis, to balance the search between exploring less-visited nodes and exploiting known good nodes.

- **Applications**:
    - **Board Games**: It has achieved superhuman performance in complex games like Go (in AlphaGo), Chess, and Shogi. Also used in Hex, Havannah, and Arimaa.
    - **Video Games**: Used for AI in real-time strategy games like Total War: Rome II and for playing games like Ms. Pac-Man.
    - **Nondeterministic Games**: Applied to games with elements of chance, such as Skat, poker, Magic: The Gathering, and Settlers of Catan.

- **More Concrete Variants**:
    - **Pure Monte Carlo Game Search**: A basic version that runs a number of random playouts for each legal move and chooses the one with the best average result.
    - **MCTS with Neural Networks**: As famously used in AlphaGo, a policy network is used to guide the tree search (selection phase), and a value network is used to evaluate leaf nodes, replacing random simulations. This significantly improves performance.

- **Related Concepts and Algorithms**:
    - **[Minimax](https://en.wikipedia.org/wiki/Minimax)**: A traditional algorithm for game tree search, often enhanced with [Alpha-Beta Pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning). MCTS is often preferred for games with large branching factors where minimax is infeasible.
    - **[Markov Chain Monte Carlo](./markov_chain_monte_carlo.md)**: Another major class of Monte Carlo methods. While MCTS is a search/planning algorithm, MCMC is a method for sampling from a complex probability distribution. Both rely on random sampling, but for different goals.
    - **[Reinforcement Learning](../../computer_science/artificial_intelligence/reinforcement_learning.md)**: MCTS can be considered a planning algorithm within an RL framework. It's a method for finding an optimal policy by simulating future states. It's a core component of programs like AlphaGo, which combines MCTS with deep reinforcement learning.
    - **[Artificial Neural Network](../../computer_science/machine_learning/artificial_neural_network.md)**: Modern MCTS implementations often use neural networks to guide the search and evaluate positions, leading to much stronger performance.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Monte_Carlo_tree_search](https://en.wikipedia.org/wiki/Monte_Carlo_tree_search)
