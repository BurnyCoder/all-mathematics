# Black-Scholes Equation

- **Mathematical Definition**: The Black-Scholes equation is a second-order partial differential equation that governs the price evolution of a European-style option under the Black-Scholes model. The equation is:
$$ \frac{\partial V}{\partial t} + \frac{1}{2}\sigma^2 S^2 \frac{\partial^2 V}{\partial S^2} + rS \frac{\partial V}{\partial S} - rV = 0 $$
  where:
  - $V$ is the price of the option as a function of stock price $S$ and time $t$.
  - $S$ is the price of the underlying asset.
  - $t$ is time.
  - $\sigma$ is the volatility of the underlying asset's returns.
  - $r$ is the risk-free interest rate.

- **Description**: The Black-Scholes equation provides a theoretical estimate of the price of European-style options. It is based on the idea of constructing a riskless portfolio whose value change exactly matches that of the option, thereby eliminating risk. The equation's solution, the Black-Scholes formula, gives the price of the option. The model makes several assumptions, including that the underlying asset follows a geometric Brownian motion with constant drift and volatility, and that there are no transaction costs or dividends.

- **Subfields it's part of**:
    - [Financial Mathematics](https://en.wikipedia.org/wiki/Mathematical_finance): It is a cornerstone of modern financial theory.
    - [Quantitative Finance](https://en.wikipedia.org/wiki/Quantitative_analysis_(finance)): Used extensively by quantitative analysts for pricing and hedging derivatives.
    - [Stochastic Calculus](https://en.wikipedia.org/wiki/Stochastic_calculus): The derivation of the equation relies heavily on stochastic calculus, particularly Itô's lemma.
    - [Partial Differential Equations](https://en.wikipedia.org/wiki/Partial_differential_equation): It is a parabolic PDE.

- **Subfields and concepts it includes**:
    - [Geometric Brownian Motion](https://en.wikipedia.org/wiki/Geometric_Brownian_motion): The model assumes the price of the underlying asset follows this stochastic process.
    - [Itô's Lemma](https://en.wikipedia.org/wiki/It%C3%B4%27s_lemma): A fundamental result in stochastic calculus used to derive the Black-Scholes equation.
    - [Risk-neutral pricing](https://en.wikipedia.org/wiki/Risk-neutral_measure): The equation is often solved in a risk-neutral world.

- **Applications**:
    - **Options Pricing**: Used to calculate the fair price of European call and put options.
    - **Risk Management**: Used by traders to hedge their positions and manage risk (e.g., Delta hedging).
    - **Financial Engineering**: A fundamental tool for creating and pricing complex financial derivatives.

- **More Concrete Variants**:
    - **Black-Scholes formula**: The explicit solution for the price of a European call or put option.

- **More General Variants**:
    - **Merton's model**: Extends the Black-Scholes model to include dividends.
    - **Models with stochastic volatility**: Heston model, for example, assumes that volatility is not constant but follows a stochastic process.
    - **Jump-diffusion models**: Incorporate sudden jumps in the asset price.
    - **American options**: For American options, which can be exercised at any time, the problem becomes a free-boundary problem for the PDE.

- **Related Concepts**:
    - **[Heat Equation](./heat_equation.md)**: The Black-Scholes equation can be transformed into the heat equation through a change of variables, which allows for finding an analytical solution.
    - **[Stochastic Differential Equation](https://en.wikipedia.org/wiki/Stochastic_differential_equation)**: The price of the underlying asset is modeled by an SDE.
    - **[Arbitrage](https://en.wikipedia.org/wiki/Arbitrage)**: The derivation of the equation is based on the no-arbitrage principle.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_equation](https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_equation)
