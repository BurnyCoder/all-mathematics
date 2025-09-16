# Bayes' Theorem

- **Mathematical Definition**: Bayes' theorem describes the probability of an event, based on prior knowledge of conditions that might be related to the event. The theorem is stated mathematically as the following equation:
$$ P(A|B) = \frac{P(B|A) \, P(A)}{P(B)} $$
  where $A$ and $B$ are events and $P(B) \neq 0$.
    - $P(A|B)$ is the **posterior probability**: the probability of event $A$ occurring given that $B$ is true.
    - $P(B|A)$ is the **likelihood**: the probability of event $B$ occurring given that $A$ is true.
    - $P(A)$ is the **prior probability**: the initial probability of event $A$.
    - $P(B)$ is the **marginal probability** of event $B$.

- **Description**: Bayes' theorem provides a way to update our beliefs (the prior probability) in light of new evidence (the likelihood). It is the mathematical foundation of Bayesian inference, a major school of thought in statistics. It describes how to rationally update the degree of confidence in a hypothesis when new information becomes available.

- **Subfields it's part of**:
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory)
    - [Statistics](https://en.wikipedia.org/wiki/Statistics) (particularly Bayesian statistics)

- **Subfields and concepts it includes**:
    - **Conditional Probability**: The probability of an event given that another event has occurred.
    - **Prior and Posterior Probability**: The probability of a hypothesis before and after observing evidence.
    - **Likelihood**: The probability of the evidence given a hypothesis.
    - **Bayesian Inference**: A method of statistical inference based on Bayes' theorem.

- **Applications**:
    - **Machine Learning**: Used in Bayesian classifiers (e.g., Naive Bayes for spam filtering) and for developing probabilistic models.
    - **Medicine**: Used in diagnostic testing to determine the probability of a patient having a disease given the result of a test.
    - **Law**: Used to update the probability of a defendant's guilt or innocence based on new evidence.
    - **A/B Testing**: Used in marketing and product development to determine if a change has a real effect.
    - **Artificial Intelligence**: Used in reasoning under uncertainty.

- **More Concrete Variants**:
    - **Bayes' rule with a partition**: A version of the rule for when event B can be partitioned into several disjoint events.

- **More General Variants**:
    - **Bayesian Networks**: A probabilistic graphical model that represents a set of variables and their conditional dependencies via a directed acyclic graph, where the relationships are governed by Bayes' theorem.

- **Related Concepts**:
    - **Conditional Probability**: The theorem is a direct consequence of the definition of conditional probability.
    - **[Probability Space](./probability_space.md)**: The underlying framework in which the probabilities are defined.
    - **Maximum Likelihood Estimation (MLE)**: A frequentist statistical method that is closely related to Bayesian inference.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Bayes%27_theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem)
