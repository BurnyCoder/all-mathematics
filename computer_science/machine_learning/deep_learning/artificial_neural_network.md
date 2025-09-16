# Artificial Neural Network

- **Mathematical Definition**: An artificial neural network (ANN) is a computational model inspired by the structure and function of biological neural networks. Mathematically, it is a network of interconnected nodes, called neurons, organized in layers. A common type, the feedforward neural network, can be represented as a composition of functions. For a single neuron, the output $y$ is typically calculated as:
$$ y = \phi(\sum_{i=1}^{n} w_i x_i + b) $$
  where $\mathbf{x} = (x_1, \dots, x_n)$ is the input vector, $\mathbf{w} = (w_1, \dots, w_n)$ is the vector of weights, $b$ is the bias, and $\phi$ is a non-linear **activation function** (e.g., sigmoid, ReLU). A multi-layered network composes these functions layer by layer. The network "learns" by adjusting the weights $\mathbf{w}$ and biases $b$ through an optimization process, such as **gradient descent**, to minimize a **loss function**.

- **Description**: Artificial neural networks are a cornerstone of modern machine learning and artificial intelligence. They are powerful tools for finding complex patterns in data. By adjusting their internal parameters (weights), they can learn to approximate complex, non-linear functions and perform tasks like classification, regression, and generation. Deep learning refers to ANNs with many layers (deep architectures).

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence)
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science)
    - [Optimization](https://en.wikipedia.org/wiki/Mathematical_optimization)

- **Subfields and concepts it includes**:
    - **Neuron**: The basic computational unit of the network.
    - **Activation Function**: A non-linear function that determines the output of a neuron.
    - **Layer**: A collection of neurons that operate together.
    - **Loss Function**: A function that measures the difference between the network's prediction and the actual target, which the network aims to minimize. This is a central concept in optimization theory.
    - **Backpropagation**: An algorithm used to efficiently compute the gradients of the loss function with respect to the network's weights. The chain rule from [calculus](../../../pure_mathematics/analysis/derivative.md) is the foundation of the backpropagation algorithm.
    - **Gradient Descent**: An iterative optimization algorithm used to find the minimum of the loss function by using the [derivative](../../../pure_mathematics/analysis/derivative.md).
    - **[Linear Algebra](../../../pure_mathematics/linear_algebra/)**: Operations within a neural network are primarily matrix and vector manipulations.
        - **[Vector Space](../../../pure_mathematics/linear_algebra/vector_space.md)**: Input data (e.g., images, text) is represented as vectors.
        - **Tensors and [Matrices](../../../pure_mathematics/linear_algebra/matrix.md)**: In general, weights and inputs are represented as tensors. A matrix (a 2D tensor) is very common, for example, representing the weights in a dense layer. Inputs (like images or video) and the kernels of convolutional layers are often higher-order tensors.
        - **Affine Transformation**: Most layers perform an affine transformation ($W\mathbf{x} + b$) followed by a non-linear activation function. Some common layers (e.g., attention, normalization, pooling) are not simple affine transformations.
    - **Calculus**: The branch of mathematics that provides the tools for optimizing neural networks.
        - **[Derivative](../../../pure_mathematics/analysis/derivative.md)**: Used to calculate the gradient of the loss function, indicating the direction of steepest ascent, so optimization algorithms like gradient descent move in the opposite direction to find the function's minimum.
        - **Chain Rule**: The fundamental rule for differentiating composite functions, which is the cornerstone of the backpropagation algorithm.

- **Applications**:
    - **Computer Vision**: Image recognition, object detection, and image segmentation.
    - **Natural Language Processing (NLP)**: Machine translation, sentiment analysis, and text generation.
    - **Speech Recognition**: Converting spoken language into text.
    - **Recommender Systems**: Powering recommendations on platforms like Netflix and Amazon.
    - **Medical Diagnosis**: Analyzing medical images and predicting diseases.

- **More Concrete Variants**:
    - **Feedforward Neural Network (FNN)**: The simplest type of ANN where connections between the nodes do not form a cycle.
    - **[Convolutional Neural Network (CNN)](./cnn.md)**: A class of deep neural networks, most commonly applied to analyzing visual imagery.
    - **[Recurrent Neural Network (RNN)](./rnn.md)**: A class of ANNs where connections between nodes form a directed graph along a temporal sequence, allowing them to exhibit temporal dynamic behavior.
    - **[Long Short-Term Memory (LSTM)](./lstm.md)**: A specialized type of RNN designed to handle long-term dependencies.
    - **[Transformer](./transformer.md)**: A deep learning architecture that relies on self-attention mechanisms instead of recurrence or convolution, becoming a standard for NLP and other sequence modeling tasks.

- **Related Concepts**:
    - **[Universal Approximation Theorem](./universal_approximation_theorem.md)**: This theorem provides the theoretical foundation that a neural network can approximate any continuous function on a compact set to arbitrary accuracy, given a suitable activation function and sufficient network width.
    - **[Neural Tangent Kernel](./neural_tangent_kernel.md)**: A concept that helps to understand the training dynamics of very wide neural networks.
    - **Probabilistic Graphical Models (PGMs)**: PGMs are a separate family of models for reasoning with uncertainty. While most ANNs are not PGMs, some variants like Boltzmann machines can be formulated as PGMs.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Artificial_neural_network](https://en.wikipedia.org/wiki/Artificial_neural_network)
