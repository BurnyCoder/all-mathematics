# Gradient Descent

- **Mathematical Definition**: Gradient descent is an iterative first-order optimization algorithm for finding a local minimum of a differentiable function. To find a local minimum of a function $F(\mathbf{x})$, one takes steps proportional to the negative of the gradient of the function at the current point. The update rule is:
$$ \mathbf{x}_{n+1} = \mathbf{x}_n - \gamma \nabla F(\mathbf{x}_n) $$
  where:
    - $\mathbf{x}_n$ is the current position in the parameter space.
    - $\gamma$ is the **learning rate**, a positive scalar determining the step size.
    - $\nabla F(\mathbf{x}_n)$ is the **gradient** of the function $F$ at $\mathbf{x}_n$, which is the vector of partial derivatives that points in the direction of the steepest ascent.

- **Description**: Gradient descent is one of the most important algorithms in machine learning and optimization. The intuition is to imagine walking down a hill to find its lowest point. The gradient gives you the direction of the steepest slope, so you take a small step in the opposite direction. By repeating this process, you iteratively descend towards a minimum. In machine learning, the function $F$ is a **loss function**, and $\mathbf{x}$ is the set of model parameters (e.g., the weights of a neural network). Gradient descent adjusts these parameters to minimize the error of the model on the training data.

- **Subfields it's part of**:
    - [Optimization](https://en.wikipedia.org/wiki/Mathematical_optimization)
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
    - [Numerical Analysis](https://en.wikipedia.org/wiki/Numerical_analysis)

- **Subfields and concepts it includes**:
    - **Gradient**: The vector of partial derivatives.
    - **Learning Rate**: A hyperparameter that controls the step size.
    - **Loss Function**: The function to be minimized.
    - **Local Minimum**: The point to which the algorithm converges, which may not be the global minimum.

- **Applications**:
    - **Machine Learning**: The primary algorithm used to train a wide variety of models, including linear regression, logistic regression, and especially [artificial neural networks](./artificial_neural_network.md).
    - **Control Theory**: Used for optimizing the parameters of a controller.
    - **Operations Research**: Solving large-scale optimization problems.

- **More Concrete Variants**:
    - **Stochastic Gradient Descent (SGD)**: Estimates the gradient using a single, randomly chosen data sample at each iteration. This is much faster for large datasets.
    - **Mini-Batch Gradient Descent**: A compromise between full-batch and stochastic, where the gradient is estimated on a small random subset (a mini-batch) of the data. This is the most common variant used in deep learning.
    - **Momentum, AdaGrad, Adam**: More advanced optimizers that adapt the learning rate or use information from past gradients to speed up convergence.

- **More General Variants**:
    - **Second-Order Optimization Methods**: Algorithms like Newton's method, which use the second derivative (the Hessian) to find the minimum, often converging faster but with a higher computational cost per step.

- **Related Concepts**:
    - **[Derivative](../../pure_mathematics/analysis/derivative.md)**: The gradient is a vector of partial derivatives.
    - **[Artificial Neural Network](./artificial_neural_network.md)**: Gradient descent, combined with the backpropagation algorithm, is the standard way to train neural networks.
    - **Convex Optimization**: A subfield of optimization that studies the case where the function to be minimized is a convex function, in which case gradient descent is guaranteed to find the global minimum.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Gradient_descent](https://en.wikipedia.org/wiki/Gradient_descent)
