# Shannon Entropy

- **Mathematical Definition**: In information theory, Shannon entropy (or simply entropy) is the measure of the average level of "information", "surprise", or "uncertainty" inherent in a random variable's possible outcomes. For a discrete [random variable](../../../applied_mathematics/probability_theory/random_variable.md) $X$ with possible outcomes $x_1, \dots, x_n$ and probability mass function $P(X)$, the entropy $H(X)$ is defined as:
$$ H(X) = - \sum_{i=1}^{n} P(x_i) \log_b P(x_i) $$
  The base of the logarithm, $b$, is usually 2, in which case the units of entropy are **bits**. The formula can be interpreted as the expected value of the self-information of the variable, where the self-information of an outcome $x_i$ is $-\log_b P(x_i)$.

- **Description**: Introduced by Claude Shannon in his 1948 paper "A Mathematical Theory of Communication", entropy provides a rigorous mathematical way to quantify uncertainty. A random variable with a uniform distribution (all outcomes equally likely) has the highest possible entropy, representing maximum uncertainty. A variable that can only take one value has zero entropy, as there is no uncertainty. The concept is central to data compression and the theoretical limits of communication.

- **Subfields it's part of**:
    - [Information Theory](https://en.wikipedia.org/wiki/Information_theory)
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory)
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science)
    - [Statistical Mechanics](https://en.wikipedia.org/wiki/Statistical_mechanics)

- **Subfields and concepts it includes**:
    - **Information Content (Self-information)**: The amount of "surprise" associated with a single outcome.
    - **Joint Entropy**: The entropy of a pair of random variables.
    - **Conditional Entropy**: The entropy of a random variable given knowledge of another variable.
    - **Mutual Information**: A measure of the mutual dependence between two random variables.
    - **Cross-Entropy**: A measure of the difference between two probability distributions.

- **Applications**:
    - **Data Compression**: The entropy of a data source specifies the theoretical lower bound on the average number of bits per symbol required to compress it without loss (e.g., in ZIP or PNG files).
    - **Machine Learning**: Cross-entropy is a widely used loss function for classification problems. Mutual information is used in feature selection.
    - **Cryptography**: Used to measure the uncertainty of a secret key.
    - **Physics**: Forms the basis for entropy in statistical mechanics.
    - **Linguistics**: Used to model the statistical structure of language.

- **More Concrete Variants**:
    - **Binary Entropy Function**: The entropy of a Bernoulli trial as a function of its success probability.

- **More General Variants**:
    - **Differential Entropy**: The corresponding concept for continuous random variables.
    - **Von Neumann Entropy**: An extension of the concept of entropy to quantum mechanics.
    - **Rényi Entropy**: A generalization of Shannon entropy.

- **Related Concepts**:
    - **[Random Variable](../../../applied_mathematics/probability_theory/random_variable.md)**: Entropy is a property of the probability distribution of a random variable.
    - **[Combinatorics](../../../pure_mathematics/discrete_mathematics/combinatorics/combinations_and_permutations.md)**: Entropy is related to the number of possible arrangements of a system, a core concept in combinatorics.
    - **[Limit](../../../pure_mathematics/analysis/limit.md)**: The concept of entropy for continuous variables (differential entropy) involves integrals, which are defined through limits.
    - **Thermodynamic Entropy**: The concept in statistical mechanics is deeply connected to Shannon entropy.
    - **Kolmogorov Complexity**: A measure of the computational complexity of an object, which is related to its information content.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Entropy_(information_theory)](https://en.wikipedia.org/wiki/Entropy_(information_theory))
