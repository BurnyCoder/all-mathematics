# Artificial Neural Network

- **Mathematical Definition**: Mathematically, an **artificial neural network (ANN)** is a network of **interconnected nodes**, called neurons, typically organized in **layers**. From a graph theory perspective, it can be viewed as a **directed graph**. For **feedforward networks** the graph is **acyclic** (a DAG). **Recurrent networks** contain **cycles** (feedback connections) in the static graph; when unrolled through time, the resulting computational graph is acyclic. A feedforward neural network can be represented as a **composition of functions**. **Inputs** are represented as **vectors** in a **vector space**, or **higher-order tensors**. For a single neuron, the output $y$ is calculated by applying a **non-linear activation function** $\phi$ (e.g., sigmoid, ReLU) to an **affine transformation** of the input vector $\mathbf{x}$:
$$ y = \phi(\mathbf{w} \cdot \mathbf{x} + b) = \phi(\sum_{i=1}^{n} w_i x_i + b) $$
where $\mathbf{w}$ is the **vector of weights** and $b$ is the **bias**, which are **real numbers**. In a dense (fully connected) **layer**, the weights form a **matrix**; many layers (e.g., convolution, attention) use **higher-rank tensors**, and in general both **data and parameters** are **tensors**. The network learns by adjusting these parameters through an **optimization** process that usually **minimizes** a **loss function**. This optimization relies on **calculus**, using **gradients** (or subgradients for non-smooth operations) of the loss with respect to the parameters, which are efficiently computed via the **chain rule** using reverse-mode automatic differentiation (**backpropagation**). The mathematical building blocks of neural networks, **calculus**, **linear algebra**, **probability theory**, **mathematical optimization**, admit formalization in standard mathematical foundations such as Zermelo-Fraenkel set theory with the Axiom of Choice (ZFC), but this is a foundational note rather than a practical concern for modeling.

- **Description**: Artificial neural networks are a cornerstone of modern machine learning and artificial intelligence. They are a computational model inspired by the structure and function of biological neural networks. They are powerful tools for finding complex patterns in data. By adjusting their internal parameters (weights), they can learn to approximate complex, non-linear functions and perform tasks like classification, regression, and generation. Deep learning typically refers to ANNs with many stacked nonlinear transformations (deep architectures).

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) - ANNs are a primary tool for building models that learn from data.
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence) - They are a cornerstone of modern AI, powering many intelligent systems.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science) - Their study and application are significant areas of research and development.
    - [Optimization](https://en.wikipedia.org/wiki/Mathematical_optimization) - Training neural networks is fundamentally an optimization problem.

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
    - **[Convolutional Neural Network (CNN)](./cnn.md)**: A class of deep neural networks that use convolutions, most commonly applied to analyzing visual imagery.
    - **[Recurrent Neural Network (RNN)](./rnn.md)**: A class of ANNs where connections between nodes form a directed graph along a temporal sequence.
    - **[Long Short-Term Memory (LSTM)](./lstm.md)**: A specialized type of RNN designed to handle long-term dependencies.
    - **[Transformer](./transformer.md)**: A deep learning architecture that relies on self-attention mechanisms instead of recurrence or convolution, becoming a standard for NLP and other sequence modeling tasks.

- **Related Concepts**:
    - **[Universal Approximation Theorem](./universal_approximation_theorem.md)**: This theorem provides the theoretical foundation that neural networks with a certain structure can, in principle, approximate any continuous function to any desired degree of accuracy
    - **[Neural Tangent Kernel](./neural_tangent_kernel.md)**: A concept that helps to understand the training dynamics of very wide neural networks.
    - **Probabilistic Graphical Models (PGMs)**: PGMs are a separate family of models for reasoning with uncertainty. While most ANNs are not PGMs, some variants like Boltzmann machines can be formulated as PGMs.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Artificial_neural_network](https://en.wikipedia.org/wiki/Artificial_neural_network)
