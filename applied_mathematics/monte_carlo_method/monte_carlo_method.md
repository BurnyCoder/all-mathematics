# Monte Carlo Method

- **Mathematical Definition**: Monte Carlo methods are a broad class of computational algorithms that rely on repeated random sampling to obtain numerical results. The underlying concept is to use randomness to solve problems that might be deterministic in principle. They are often used when it is infeasible or impossible to compute an exact result with a deterministic algorithm. A classic example is estimating the value of $\pi$:
  1. Inscribe a circle of radius $r$ inside a square with side length $2r$. The area of the circle is $\pi r^2$ and the area of the square is $(2r)^2 = 4r^2$. The ratio of the areas is $\frac{\pi r^2}{4r^2} = \frac{\pi}{4}$.
  2. Generate a large number $N$ of random points uniformly distributed inside the square.
  3. Count the number of points $M$ that fall inside the circle.
  4. The ratio $\frac{M}{N}$ is an estimate of the ratio of the areas, so $\pi \approx 4 \frac{M}{N}$.

- **Description**: Monte Carlo methods use randomness and repeated sampling to approximate complex or high-dimensional problems. Instead of calculating an exact value, which might be too difficult, these methods simulate a process many times and calculate a statistical property (like an average) of the results to approximate the desired value. The accuracy of the approximation generally improves as the number of samples increases.

- **Subfields it's part of**:
    - [Computational Statistics](https://en.wikipedia.org/wiki/Computational_statistics): A fundamental technique for simulation and inference.
    - [Numerical Analysis](https://en.wikipedia.org/wiki/Numerical_analysis): Used for numerical integration, optimization, and solving systems of equations.
    - [Computer Science](../computer_science/): Widely used in algorithms for simulation, search, and machine learning.
    - [Applied Mathematics](../): A key tool in mathematical modeling.
    - [Statistical Physics](https://en.wikipedia.org/wiki/Statistical_physics): Used to simulate complex physical systems.

- **Subfields and concepts it includes**:
    - **[Probability Theory](../probability_theory/)**: The entire method is built upon the principles of probability and random variables.
    - **[Statistics](../statistics/)**: Concepts like sampling, expectation, variance, and the law of large numbers are central to understanding why Monte Carlo methods work.
    - **Random Number Generation**: A prerequisite for any Monte Carlo simulation.
    - **Law of Large Numbers**: This theorem provides the theoretical justification for why the average of the results obtained from a large number of trials should be close to the expected value.

- **Applications**:
    - **Numerical Integration**: Estimating complex, high-dimensional integrals (e.g., in Bayesian statistics or financial modeling).
    - **Optimization**: Finding the minimum or maximum of a function, for instance, through simulated annealing.
    - **Finance**: Used in quantitative finance to model the behavior of financial instruments and derivatives (e.g., option pricing).
    - **Computer Graphics**: For rendering realistic images by simulating the paths of light rays (path tracing).
    - **Artificial Intelligence**: In search algorithms like Monte Carlo Tree Search for game playing.
    - **Physics and Chemistry**: Simulating particle transport, molecular dynamics, and fluid mechanics.

- **More Concrete Variants**:
    - **[Markov Chain Monte Carlo (MCMC)](./markov_chain_monte_carlo.md)**: A powerful variant that uses Markov chains to sample from a probability distribution. It's especially useful when direct sampling is difficult.
    - **[Monte Carlo Tree Search (MCTS)](./monte_carlo_tree_search.md)**: A specific application of Monte Carlo methods to search decision trees, famously used in game-playing AI like AlphaGo.
    - **Sequential Monte Carlo (Particle Filters)**: Used for tracking the state of dynamic systems over time.
    - **Quantum Monte Carlo**: A class of algorithms used to solve quantum many-body problems.

- **Related Concepts and Algorithms**:
    - **Deterministic Algorithms**: Monte Carlo methods are probabilistic, contrasting with algorithms that follow a predictable path.
    - **Las Vegas Algorithm**: A type of randomized algorithm that always produces the correct result, but its runtime varies. Monte Carlo algorithms, in contrast, run for a fixed time but may produce a result with some error.
    - **Quasi-Monte Carlo methods**: These methods use low-discrepancy sequences instead of pseudo-random numbers for a potentially faster rate of convergence.

- **Wikipedia**: https://en.wikipedia.org/wiki/Monte_Carlo_method
