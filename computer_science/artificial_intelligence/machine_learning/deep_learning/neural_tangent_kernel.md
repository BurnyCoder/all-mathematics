# Neural Tangent Kernel

- **Mathematical Definition**: Let $f(x; \theta)$ be the output of a neural network with parameters $\theta$ for an input $x$. The Neural Tangent Kernel (NTK) is a function of two inputs $x$ and $x'$ defined as:
$$ \Theta(x, x'; \theta) = \nabla_{\theta} f(x; \theta) \cdot \nabla_{\theta} f(x'; \theta) $$
  where $\nabla_{\theta} f(x; \theta)$ is the gradient of the network's output with respect to its parameters. The NTK measures the similarity between two inputs in the space of parameter gradients. This dot product formulation ensures the NTK is a valid kernel function (symmetric and positive semi-definite).

- **Description**: The Neural Tangent Kernel is a key concept in the theoretical understanding of deep learning. It describes how the predictions of a deep neural network evolve during training with gradient descent. The NTK provides a bridge between deep learning and kernel methods, allowing the use of tools from kernel methods to analyze neural networks. In the limit of infinite width, the NTK becomes constant during training. This leads to a remarkable result: training an infinitely wide neural network with gradient descent is equivalent to performing kernel regression with the NTK. This 'lazy training' regime, where the network parameters change very little, simplifies the analysis of training dynamics and generalization.

- **Subfields it's part of**:
    - [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning): The NTK is a theoretical tool to understand deep neural networks, which are a class of machine learning algorithms.
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): It connects different paradigms within machine learning, namely neural networks and kernel methods.
    - [Kernel Methods](https://en.wikipedia.org/wiki/Kernel_method): The NTK shows that wide neural networks are effectively kernel machines.
    - [Statistical Learning Theory](https://en.wikipedia.org/wiki/Statistical_learning_theory): It provides a framework to study the generalization properties of deep neural networks.

- **Subfields and concepts it includes**:
    - [Gradient Descent](./gradient_descent.md): The training dynamics described by the NTK are based on gradient descent, an optimization algorithm used to find the local minimum of a function.
    - [Artificial Neural Network](./artificial_neural_network.md): The NTK is derived from the architecture of a neural network.
    - **Infinite-Width Limit**: The main results of NTK theory are derived in the limit where the number of neurons in each layer goes to infinity.
    - **Gaussian Process**: At initialization, an ensemble of wide neural networks forms a Gaussian process, and the NTK describes the evolution of this process.
    - **Kernel Regression**: Training a wide neural network is equivalent to kernel regression with the NTK.
    - [Calculus](../../pure_mathematics/analysis/derivative.md): The definition of the NTK is based on the gradient of the neural network's output function, which is a vector of partial derivatives.
    - [Linear Algebra](../../pure_mathematics/linear_algebra/vector_space.md): The NTK is computed as a dot product between two gradient vectors. The gradient vectors themselves live in a high-dimensional vector space (the parameter space). The properties of the kernel, such as being symmetric and positive semi-definite, are concepts from linear algebra.

- **Applications**:
    - **Training Dynamics**: Provides a precise mathematical description of how a network's output function changes during training.
    - **Generalization**: Helps explain why over-parameterized neural networks can generalize well to unseen data.
    - **Convergence Proofs**: Used to prove that gradient descent can find the global minimum of the loss function for sufficiently wide neural networks.
    - **Architecture Design**: The NTK can be used to analyze and compare different neural network architectures.

- **More Concrete Variants**:
    - **NTK for Convolutional Neural Networks (CNNs)**: NTK has been extended to networks with weight sharing like CNNs.
    - **NTK for Recurrent Neural Networks (RNNs)**: The convergence rate of training RNNs can be analyzed using NTK.
    - **NTK for Transformers/Attention**: NTK has been derived for attention-based architectures, providing insights into their behavior.

- **More General Variants**:
    - **NTK for generic nonlinear models**: The phenomenon is not specific to neural networks and can be observed in generic nonlinear models.
    - **Finite-Width Corrections**: Research is ongoing to understand how the NTK changes for finite-width networks and how it affects training.

- **Related Concepts**:
    - [Derivative](../../pure_mathematics/analysis/derivative.md): The gradient, which is central to the NTK definition, is a collection of partial derivatives.
    - **Feature Learning**: In contrast to the NTK's 'lazy' regime where features are considered fixed, feature learning describes how neural networks learn meaningful representations of data. This happens when parameters move significantly during training, which is often observed in practice, especially with finite-width networks.
    - **Mean-Field Theory**: An alternative theoretical framework for analyzing infinite-width neural networks, which focuses on the distribution of neuron activations.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Neural_tangent_kernel](https://en.wikipedia.org/wiki/Neural_tangent_kernel)
