# Universal Approximation Theorem

- **Mathematical Definition**: The universal approximation theorems are a class of results in the theory of artificial neural networks. The most well-known version states that a feedforward neural network with a single hidden layer containing a finite number of neurons can approximate continuous functions on compact subsets of $\mathbb{R}^n$, under mild assumptions on the activation function.

  Specifically, for a non-polynomial, continuous, and bounded activation function $\sigma: \mathbb{R} \to \mathbb{R}$, the set of functions $F(\mathbf{x})$ that can be represented by a single-hidden-layer neural network is dense in the space of continuous functions on a compact set $K \subset \mathbb{R}^n$. This means that for any continuous function $f: K \to \mathbb{R}$ and any desired accuracy $\epsilon > 0$, there exists a network $F(\mathbf{x})$ of the form:
  $$ F(\mathbf{x}) = \sum_{i=1}^{N} v_i \sigma(\mathbf{w}_i \cdot \mathbf{x} + b_i) $$
  such that $|F(\mathbf{x}) - f(\mathbf{x})| < \epsilon$ for all $\mathbf{x} \in K$. Here, $N$ is the number of neurons, $\mathbf{w}_i$ are weight vectors, $b_i$ are biases, and $v_i$ are output weights.

- **Description**: This theorem provides the mathematical justification for using neural networks to model complex, unknown functions from data. It is an existence theorem: it guarantees that a sufficiently large network *exists*, but it does not provide a method for finding the network's parameters (weights and biases). The process of finding these parameters is what machine learning practitioners call "training," which is typically done using optimization algorithms like gradient descent. The theorem assures us that, in principle, a neural network is a powerful enough functional form to represent a vast range of relationships in data.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): The theorem is a foundational theoretical result in machine learning, particularly for neural networks.
    - [Artificial Neural Networks](https://en.wikipedia.org/wiki/Artificial_neural_network): It directly addresses the expressive power of neural network architectures.
    - [Approximation Theory](https://en.wikipedia.org/wiki/Approximation_theory): This field of mathematics studies how well functions can be approximated by simpler ones; the theorem is a key result in this area for network-based approximators.
    - [Mathematical Analysis](https://en.wikipedia.org/wiki/Mathematical_analysis): The proofs and concepts rely heavily on tools from real and functional analysis.

- **Subfields and concepts it includes**:
    - **Feedforward Neural Networks**: The classical theorem is formulated for this type of network architecture.
    - **Activation Function**: The properties of the activation function (e.g., being non-polynomial) are central to the theorem's validity.
    - **Function Approximation**: The core task that the theorem addresses.
    - **Network Width and Depth**: Different versions of the theorem explore universality by either increasing the number of neurons in a layer (width) or increasing the number of layers (depth).
    - [Real Analysis](https://en.wikipedia.org/wiki/Real_analysis):
        - **[Topological Space](../../../pure_mathematics/topology/topological_space.md)**: The theorem is framed in terms of functions on compact subsets of $\mathbb{R}^n$, a concept from topology.
        - **Continuous Functions**: The class of functions the theorem addresses are continuous, a central topic of analysis.
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra):
        - **[Vector Space](../../../pure_mathematics/linear_algebra/vector_space.md)**: The inputs $\mathbf{x}$ and weights $\mathbf{w}_i$ are vectors.

- **Applications**:
    - **Deep Learning**: Provides the theoretical underpinning for why deep neural networks can successfully model complex patterns in fields like computer vision, natural language processing, and speech recognition.
    - **Function Regression**: Any task that involves learning a continuous mapping from input data to a continuous output, such as predicting stock prices or modeling physical systems.
    - **Scientific Computing**: Used to create surrogate models for complex physical simulations, which are much faster to evaluate than the original simulations.
    - **Control Theory**: In reinforcement learning, neural networks are used to approximate value functions or policies, which the theorem guarantees is possible.

- **More Concrete Variants**:
    - **Arbitrary-Width Theorem**: The original versions (Cybenko, 1989; Hornik et al., 1989) showed that a single hidden layer is sufficient if its width (number of neurons) can be arbitrarily large.
    - **Arbitrary-Depth Theorem**: Later results demonstrated that for certain activation functions like ReLU, universality can also be achieved by fixing the width of the layers and making the network arbitrarily deep.
    - **Quantitative Bounds**: Research that provides estimates on the required width or depth of a network to approximate a given function to a certain degree of accuracy.

- **More General Variants**:
    - **Approximation of Discontinuous Functions**: Extensions of the theorem to cover the approximation of functions that are not continuous.
    - **Kolmogorov–Arnold Representation Theorem**: A related theorem in pure mathematics which shows that any multivariate continuous function can be represented as a composition of single-variable functions. This has been shown to have connections to network architectures.
    - **Approximation of Operators**: Generalizations for networks (like DeepONets) designed to learn operators between infinite-dimensional function spaces, not just functions between Euclidean spaces.

- **Related Concepts**:
    - **[Artificial Neural Network](./artificial_neural_network.md)**: The theorem describes a fundamental property of this model class.
    - **[Gradient Descent](../gradient_descent.md)**: While the theorem guarantees existence, gradient descent is the practical algorithm used to find the parameters of an approximating network.
    - **[Weierstrass Approximation Theorem](../../../pure_mathematics/analysis/weierstrass_approximation_theorem.md)**: A classic theorem stating that polynomials can approximate any continuous function on a closed interval. The Universal Approximation Theorem is often seen as an analogue for neural networks.
    - **[Stone-Weierstrass Theorem](../../../pure_mathematics/analysis/stone_weierstrass_theorem.md)**: A powerful generalization of the Weierstrass theorem, which can be used as a tool to prove versions of the universal approximation theorem.
    - **[Function Space](../../../pure_mathematics/analysis/function_space.md)**: The theorem can be formally stated in the language of function spaces, for instance, by saying that the set of functions representable by a neural network architecture is dense in the space of continuous functions equipped with the uniform norm.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Universal_approximation_theorem](https://en.wikipedia.org/wiki/Universal_approximation_theorem)
