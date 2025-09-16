# Random Variable

- **Mathematical Definition**: A random variable is a variable whose possible values are numerical outcomes of a random phenomenon. More formally, given a [probability space](./probability_space.md) \\((\Omega, \mathcal{F}, P)\\), a random variable is a function \\(X: \Omega \to E\\) that maps outcomes \\(\omega \in \Omega\\) to a measurable space \\(E\\) (often the real numbers \\(\mathbb{R}\\)). The function \\(X\\) must be **measurable**, which means that for any subset \\(S \subseteq E\\) in the corresponding \\(\sigma\\)-algebra of \\(E\\), the set \\(\{\omega \in \Omega \mid X(\omega) \in S\}\) is an event in \\(\mathcal{F}\\).

- **Description**: A random variable provides a way to attach a numerical value to the outcome of an experiment. For example, in a coin toss experiment, the sample space is \\(\Omega = \{\text{heads, tails}\}\\). We can define a random variable \\(X\\) such that \\(X(\text{heads}) = 1\\) and \\(X(\text{tails}) = 0\\). The random variable itself is a function, but we are often more interested in the probabilities of the values it takes, which are described by its probability distribution.

- **Subfields it's part of**:
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory)
    - [Statistics](https://en.wikipedia.org/wiki/Statistics)

- **Subfields and concepts it includes**:
    - **Probability Distribution**: A function that describes the probability of a random variable taking on certain values.
    - **Cumulative Distribution Function (CDF)**: The probability that a random variable \\(X\\) will take a value less than or equal to \\(x\\).
    - **Probability Mass Function (PMF)**: For a discrete random variable, the probability that it is equal to some value.
    - **Probability Density Function (PDF)**: For a continuous random variable, a function whose integral over a region gives the probability of the variable falling in that region.
    - **Expected Value (Mean)**: The long-run average value of a random variable.
    - **Variance**: A measure of the spread of a random variable's values.

- **Applications**:
    - **Statistics and Machine Learning**: Random variables are the fundamental building blocks for statistical models.
    - **Finance**: Stock prices, interest rates, and other financial quantities are modeled as random variables.
    - **Physics**: Quantities in statistical mechanics and quantum mechanics are modeled as random variables.
    - **Information Theory**: Used to model sources of information and communication channels.

- **More Concrete Variants**:
    - **Discrete Random Variable**: A variable that can take on a finite or countably infinite number of distinct values (e.g., the outcome of a dice roll).
    - **Continuous Random Variable**: A variable that can take on an uncountably infinite number of values within a given range (e.g., the height of a person).

- **More General Variants**:
    - **Random Vector**: A vector of random variables.
    - **Stochastic Process**: A collection of random variables, often indexed by time or space.

- **Related Concepts**:
    - **[Probability Space](./probability_space.md)**: The domain of a random variable is the sample space \\(\Omega\\).
    - **Probability Distribution**: Every random variable is associated with a probability distribution that characterizes it.
    - **Measure Theory**: The formal definition of a random variable is based on the concept of a measurable function.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Random_variable](https://en.wikipedia.org/wiki/Random_variable)
