# Algorithmic Information Theory

- **Mathematical Definition**: Algorithmic Information Theory (AIT) provides a formal and absolute measure of the information content of an individual object, known as **Kolmogorov Complexity** or algorithmic complexity. The Kolmogorov complexity of a string $s$, denoted $K(s)$, is the length of the shortest program $p$ that can produce $s$ on a fixed universal Turing machine $U$.

  $$ K(s) = \min_{p} \{ |p| : U(p) = s \} $$

  Similarly, the conditional Kolmogorov complexity $K(s|x)$ is the length of the shortest program that produces $s$ given $x$ as an input.

  $$ K(s|x) = \min_{p} \{ |p| : U(p, x) = s \} $$

  An object is considered "random" if it is incompressible, meaning $K(s) \approx |s|$.

- **Description**: AIT is a branch of theoretical computer science that combines information theory, computability theory, and probability. Unlike Shannon's information theory, which deals with the average information in an ensemble of messages, AIT deals with the information content of a single, specific object. It equates the complexity of an object with the size of its smallest possible description. This provides a powerful, objective way to reason about concepts like randomness, complexity, and information.

- **Subfields it's part of**:
    - [Information Theory](./entropy.md)
    - [Computability Theory](../../foundations_of_mathematics/computability_theory/turing_machine.md)
    - [Computer Science](../README.md)
    - [Foundations of Mathematics](../../foundations_of_mathematics/README.md)

- **Subfields and concepts it includes**:
    - **Kolmogorov Complexity**: The central measure of the descriptive complexity of an object.
    - **Universal Turing Machine**: The theoretical model of computation upon which the definition of complexity is based.
    - **Algorithmic Randomness**: A formal definition for when an individual sequence can be considered random (i.e., when it's incompressible).
    - **Incompressibility Method**: A proof technique where one shows an object has a certain property by arguing that if it didn't, it could be compressed, contradicting its randomness.
    - **Algorithmic Probability**: Defines a universal probability distribution for predicting the next element in a sequence, related to Solomonoff induction.

- **Applications**:
    - **Philosophy of Science**: Formalizes Occam's Razor, suggesting that the simplest hypothesis (the one with the shortest description) is the best.
    - **Artificial Intelligence**: Forms the theoretical basis for definitions of intelligence like **[AIXI](../artificial_intelligence/aixi.md)** and **[Chollet's Measure of Intelligence](../artificial_intelligence/chollets_measure_of_intelligence.md)**.
    - **Machine Learning**: The Minimum Description Length (MDL) principle is a practical application of AIT ideas to statistical modeling and inference.
    - **Data Compression**: Provides the theoretical lower bound for lossless data compression.
    - **Bioinformatics**: Used to analyze the complexity and randomness of DNA sequences.

- **More Concrete Variants**:
    - **Minimum Description Length (MDL)**: A practical framework for statistical inference that uses the ideas of AIT.

- **More General Variants**:
    - **Shannon's Information Theory**: AIT can be seen as an individual-sequence counterpart to Shannon's probabilistic theory. While Shannon's entropy measures the average information of a source, Kolmogorov complexity measures the specific information of a sequence.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Algorithmic_information_theory](https://en.wikipedia.org/wiki/Algorithmic_information_theory)
