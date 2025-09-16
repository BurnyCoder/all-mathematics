# Probability Distribution

## Mathematical Definition

A **probability distribution** is a mathematical [function](../../../00_Foundations/01_Set_Theory/Function.md) that provides the probabilities of occurrence of different possible outcomes in an experiment. It is a fundamental concept in probability theory and statistics.

The specific mathematical form of a probability distribution depends on whether the random variable it describes is **discrete** or **continuous**.

### Discrete Probability Distribution

For a **discrete random variable** \(X\), which can take on a finite or countably infinite number of values, the probability distribution is described by a **probability mass function (PMF)**, denoted \(p(x)\). The PMF gives the probability that the random variable \(X\) is exactly equal to some value \(x\).
\[ p(x) = P(X = x) \]
A PMF must satisfy two conditions:
1.  \(0 \le p(x) \le 1\) for all \(x\).
2.  \(\sum_{x} p(x) = 1\), where the sum is over all possible values of \(X\).

### Continuous Probability Distribution

For a **continuous random variable** \(X\), which can take any value in a given range or interval, the probability distribution is described by a **probability density function (PDF)**, denoted \(f(x)\). The PDF does not give the probability of a specific value (which is always zero for a continuous variable), but rather the probability of the variable falling within a range of values is given by the [integral](../../../02_Analysis/00_Calculus/Integral.md) of the density function over that range.
\[ P(a \le X \le b) = \int_{a}^{b} f(x) \,dx \]
A PDF must satisfy two conditions:
1.  \(f(x) \ge 0\) for all \(x\).
2.  \(\int_{-\infty}^{\infty} f(x) \,dx = 1\).

## Description

A probability distribution describes how likely the different outcomes of a random event are. It provides a complete picture of the probabilities associated with a random variable.

## Subfields it's part of

*   [Probability and Statistics](./)
*   [Measure Theory](../../../02_Analysis/)
*   [Information Theory](../)

## Subfields and concepts it includes

*   **Random Variable:** A variable whose value is a numerical outcome of a random phenomenon.
*   **Cumulative Distribution Function (CDF):** A function giving the probability that a random variable \(X\) is less than or equal to \(x\), for every value \(x\).
*   **Expected Value (or Mean):** The long-run average value of repetitions of the experiment it represents.
*   **Variance and Standard Deviation:** Measures of the spread or dispersion of the distribution.
*   **Skewness and Kurtosis:** Measures of the shape of the distribution.
*   **Joint, Marginal, and Conditional Distributions:** Concepts for describing distributions of multiple random variables.
*   **Central Limit Theorem:** A fundamental theorem stating that the sum (or average) of a large number of independent and identically distributed random variables will be approximately normally distributed, regardless of the underlying distribution.

## Applications

*   **Statistics and Data Science:** Used to model data and make inferences. Statistical tests are often based on assumptions about the underlying probability distribution of the data.
*   **Physics:** Used in statistical mechanics to describe the distribution of particle speeds (Maxwell-Boltzmann distribution) and in quantum mechanics, where the state of a particle is described by a probability distribution (the square of the wave function).
*   **Finance:** Used to model the returns of assets (e.g., the log-normal distribution for stock prices).
*   **Biology:** Modeling population genetics, the spread of diseases, etc.
*   **Machine Learning:** Many machine learning models are probabilistic in nature and work with probability distributions.
*   **Risk Management and Insurance:** Actuarial science relies heavily on probability distributions to model mortality, claims, etc.

## More general variants

*   **Probability Measure:** The modern, axiomatic foundation of probability theory is based on measure theory. A probability distribution can be seen as a specific way to define a probability measure on the set of possible outcomes.
*   **Stochastic Process:** A collection of random variables, representing the evolution of some system over time.

## More concrete variants

### Common Discrete Distributions
*   **Bernoulli Distribution:** The outcome of a single trial with two possible outcomes (success/failure).
*   **Binomial Distribution:** The number of successes in a fixed number of independent Bernoulli trials.
*   **Poisson Distribution:** The number of events occurring in a fixed interval of time or space.
*   **Geometric Distribution:** The number of trials needed to get the first success.

### Common Continuous Distributions
*   **Uniform Distribution:** All outcomes in a range are equally likely.
*   **Normal (or Gaussian) Distribution:** The classic "bell curve", which is central to statistics due to the Central Limit Theorem.
*   **Exponential Distribution:** The time between events in a Poisson process.
*   **Chi-Squared Distribution:** Used in hypothesis testing.

## Everything else it relates to

*   **Calculus:** The integral is used to define the probabilities for continuous distributions.
*   **Combinatorics:** Used to calculate probabilities in discrete distributions, for example, the [Binomial Coefficient](../../../06_Combinatorics/Binomial_Coefficient.md) is used in the Binomial distribution.
*   **Information Theory:** The entropy of a probability distribution is a measure of its uncertainty.
