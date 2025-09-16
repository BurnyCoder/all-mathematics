# Normal Distribution

- **Mathematical Definition**: The normal (or Gaussian) distribution is a continuous probability distribution for a real-valued random variable. Its probability density function (PDF) for a random variable $X$ with mean $\mu$ and variance $\sigma^2$ is given by:
$$ f(x | \mu, \sigma^2) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2} $$
  This function describes the famous "bell curve" shape. The parameter $\mu$ is the mean or expectation of the distribution (and also its median and mode), while the parameter $\sigma$ is its standard deviation, and $\sigma^2$ is its variance.

- **Description**: The normal distribution is the most common probability distribution in statistics and is often used in the natural and social sciences to represent real-valued random variables whose distributions are not known. Its familiarity is due to the Central Limit Theorem, which states that the average of many independent, identically distributed random variables tends toward a normal distribution, regardless of the original distribution.

- **Subfields it's part of**:
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory): The normal distribution is a fundamental continuous probability distribution.
    - [Statistics](https://en.wikipedia.org/wiki/Statistics): It is one of the most important distributions for statistical inference and hypothesis testing.

- **Subfields and concepts it includes**:
    - **Mean ($\mu$)**: The central point of the distribution, which determines its location. This is a fundamental concept in **probability theory**.
    - **Variance ($\sigma^2$)**: A measure of the spread or dispersion of the distribution, also a core concept from **probability theory**.
    - **Standard Deviation ($\sigma$)**: The square root of the variance, providing another measure of spread in the same units as the data, rooted in **probability theory**.
    - **Probability Density Function (PDF)**: The function that defines the shape of the distribution, a concept from **mathematical analysis** and **probability theory**.

- **Applications**:
    - **Natural and Social Sciences**: Used to model phenomena that are assumed to be the sum of many independent processes, such as measurement errors, height, and test scores.
    - **Finance**: In financial modeling, asset returns are often assumed to be normally distributed, as in the Black-Scholes model for option pricing.
    - **Quality Control**: To model variations in manufacturing processes and set control limits.
    - **Machine Learning**: It is used for initializing weights in neural networks, as a component in Gaussian mixture models, and to model the distribution of errors in regression analysis.
    - **Signal Processing**: Thermal noise in electronic components is often modeled as Gaussian noise.

- **More Concrete Variants**:
    - **Standard Normal Distribution**: A special case of the normal distribution where the mean $\mu=0$ and the standard deviation $\sigma=1$. Any normally distributed variable can be converted to a standard normal variable by subtracting the mean and dividing by the standard deviation.

- **More General Variants**:
    - **Multivariate Normal Distribution**: A generalization to higher dimensions, describing a vector of correlated, normally distributed random variables.
    - **Log-normal Distribution**: The distribution of a random variable whose logarithm is normally distributed.
    - **Student's t-distribution**: A distribution that arises when estimating the mean of a normally distributed population with a small sample size and unknown standard deviation.

- **Related Concepts**:
    - **[Random Variable](./random_variable.md)**: The normal distribution is a probability distribution for a continuous random variable.
    - **Central Limit Theorem**: This theorem provides the theoretical foundation for why the normal distribution is so prevalent in nature and statistics.
    - **[Bayes' Theorem](./bayes_theorem.md)**: The normal distribution is often used as a prior distribution for parameters in Bayesian inference (e.g., Gaussian process regression).
    - **[Gradient Descent](../../../computer_science/machine_learning/gradient_descent.md)**: The assumptions about the distribution of data (often normal) can influence the performance and formulation of optimization algorithms like gradient descent.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Normal_distribution](https://en.wikipedia.org/wiki/Normal_distribution)
