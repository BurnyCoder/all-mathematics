# Chollet's Measure of Intelligence

- **Mathematical Definition**: François Chollet defines intelligence as *skill-acquisition efficiency*. It's a measure of how efficiently a system turns its experience and prior knowledge into skill on a range of tasks, particularly tasks that require generalization. This is formalized using Algorithmic Information Theory.

  The core idea can be summarized as: `Intelligence ∝ (Skill × Generalization Difficulty) / (Priors + Experience)`

  **Intelligence of system $IS$ over $scope$ (sufficient case):**
  $$ I_{IS, scope}^{\theta_{T}} = \underset{T \in scope}{\operatorname{Avg}} \left[ \omega_{T} \cdot \theta_{T} \sum_{C \in Cur_{T}^{\theta_{T}}} \left[ P_C \cdot \frac{ GD^{\theta_{T}}_{IS, T, C}}{P^{\theta_{T}}_{IS, T} + E_{IS, T, C}^{\theta_{T}}} \right] \right] $$

  **Intelligence of system $IS$ over $scope$ (optimal case):**
  $$ I_{IS, scope}^{opt} = \underset{T \in scope}{\operatorname{Avg}} \left[ \omega_{T, \Theta} \cdot \Theta \sum_{C \in Cur_{T}^{opt}} \left[ P_C \cdot \frac{ GD^{\Theta}_{IS, T, C}}{P^{\Theta}_{IS, T} + E_{IS, T, C}^{\Theta}} \right] \right] $$

  Where:
  - $I_{IS, scope}$: Intelligence of a system $IS$ over a $scope$ of tasks.
  - $T$: A task from the $scope$.
  - $GD$: **Generalization Difficulty**, the complexity of adapting from a training solution to a general solution.
  - $P$: **Priors**, the system's relevant initial knowledge about the task.
  - $E$: **Experience**, the relevant, novel information gained during training via a curriculum $C$.
  - $\omega_T$: The value/importance of the task.
  - $\theta_T$: The skill level achieved.
  - $P_C$: The probability of a curriculum $C$.
  - The formula averages over all tasks in the scope and sums over all possible learning curricula.

- **Description**: This definition provides a formal way to think about and measure intelligence that is distinct from pure task performance or skill. It emphasizes the ability to learn and adapt efficiently. By focusing on skill-acquisition efficiency, it distinguishes the process of intelligence from its output (skill). A system is considered intelligent not just because it can perform a task well, but because it can learn to do so with minimal data and pre-programmed knowledge, especially for problems it has never seen before. This framework is designed to guide AI research towards more general, human-like intelligence rather than narrow, superhuman skill on specific tasks.

- **Subfields it's part of**:
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence): Chollet's measure is a formal definition of general intelligence, a central concept in the field of AI.
    - [Algorithmic Information Theory](../../information_theory/algorithmic_information_theory.md): The definition uses Algorithmic Information Theory to formally quantify concepts like generalization difficulty, priors, and experience.
    - [Computer Science](../README.md): This measure of intelligence is a theoretical concept within computer science, aiming to guide AI research.
    - [Information Theory](../../information_theory/entropy.md): It builds upon information-theoretic ideas to measure the efficiency of learning.

- **Subfields and concepts it includes**:
    - **Skill-Acquisition Efficiency**: The core idea that intelligence is about how efficiently a system learns.
    - **Algorithmic Complexity (Kolmogorov Complexity)**: The theoretical tool from Algorithmic Information Theory used to quantify the concepts of generalization, priors, and experience.
        - **[Computability Theory](../../foundations_of_mathematics/computability_theory/turing_machine.md)**: The foundations of Algorithmic Information Theory lie in computability theory, which defines the universal Turing machine—the basis for defining algorithmic complexity.
        - **[Mathematical Logic](../../foundations_of_mathematics/logic/first_order_logic.md)**: The entire framework of computation and information is built upon principles of mathematical logic.
    - **[Probability Theory](../../applied_mathematics/probability_theory/probability_space.md)**: The definition involves averaging over task scopes and curricula, using concepts like expectation ($Avg$) and probability distributions over curricula ($P_C$).
    - **Generalization**: The ability to handle situations that differ from previously encountered ones. The definition uses a formal measure of "generalization difficulty".
    - **Priors**: The set of assumptions and knowledge a system starts with. The framework provides a way to account for their contribution.
    - **Experience**: The information gathered during a learning process (a curriculum).
    - **Program Synthesis**: The definition fits well with a view of AI as a program synthesis engine that generates "skill programs" to solve tasks.
    - **Curriculum Learning**: The sequence of learning examples (the curriculum) is a key component in measuring the efficiency of learning.

- **Applications**:
    - **AI Evaluation**: Provides a theoretical basis for creating more robust benchmarks for AI systems, particularly for Artificial General Intelligence (AGI).
    - **Guiding AI Research**: Can act as a "North Star" objective function for developing flexible, general AI systems rather than brittle, specialized ones.
    - **Abstraction and Reasoning Corpus (ARC)**: This definition directly inspired the creation of the ARC dataset, a benchmark designed to test these ideas in practice.

- **More Concrete Variants**:
    - **Abstraction and Reasoning Corpus (ARC)**: A practical benchmark proposed in the same paper to measure intelligence according to this definition. It consists of visual reasoning puzzles that are easy for humans but difficult for current AI systems.

- **More General Variants**:
    - [AIXI](./aixi.md): AIXI is another formal definition of intelligence based on Algorithmic Information Theory, but focuses on reward maximization rather than skill-acquisition efficiency.
    - **Universal Intelligence**: A formal definition of intelligence by Legg and Hutter, closely related to AIXI.

- **Source**: [On the Measure of Intelligence, by François Chollet (2019)](https://arxiv.org/abs/1911.01547)
