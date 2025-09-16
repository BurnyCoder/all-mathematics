# Convolutional Neural Network (CNN)

- **Mathematical Definition**: The foundational operation of a Convolutional Neural Network (CNN) is the **convolution**. For a 2D input, such as an image $I$, and a learnable kernel (or filter) $K$ of size $m \times n$, the discrete convolution produces a feature map $S$. The value at each position $(i, j)$ in the feature map is calculated as:
$$ S(i, j) = (I * K)(i, j) = \sum_{u=1}^{m} \sum_{v=1}^{n} I(i-u, j-v) K(u, v) $$
  In deep learning, this operation is technically **cross-correlation**, where the kernel is not flipped:
$$ S(i, j) = \sum_{u=1}^{m} \sum_{v=1}^{n} I(i+u, j+v) K(u, v) $$
  A typical CNN layer applies multiple kernels to its input, passes the resulting feature maps through a non-linear **activation function** (e.g., ReLU), and then often performs a **pooling** operation (e.g., max-pooling) to reduce spatial dimensions.

- **Description**: A Convolutional Neural Network (CNN or ConvNet) is a class of deep neural networks, most commonly applied to analyzing visual imagery. Inspired by the organization of the animal visual cortex, CNNs use a hierarchical structure of layers to learn representations of data. Early layers detect simple features like edges and colors, while deeper layers learn to recognize more complex features like shapes, objects, and scenes. Their architecture, featuring parameter sharing and sparse connectivity, makes them highly efficient for processing grid-like data.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): A cornerstone of modern machine learning, especially for perceptual tasks.
    - [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning): One of the most important and widely used deep learning architectures.
    - [Computer Vision](https://en.wikipedia.org/wiki/Computer_vision): The dominant tool for tasks like image classification, object detection, and segmentation.
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence): A key technology enabling AI systems to perceive and understand the visual world.

- **Subfields and concepts it includes**:
    - **Convolution**: The mathematical operation of sliding a kernel over an input to produce a feature map.
    - **Pooling (Subsampling)**: A technique to reduce the spatial dimensions of the feature maps, providing a degree of translation invariance.
    - **Activation Function (ReLU)**: A non-linear function applied element-wise to introduce non-linearity into the model.
    - **Feature Maps**: The output of a convolutional layer, representing the presence of specific features in the input.
    - **Filters/Kernels**: Small matrices of learnable parameters that are trained to detect specific features.
    - **[Linear Algebra](../../pure_mathematics/linear_algebra/)**: Convolution is a linear operation, and all operations are based on tensors (multi-dimensional matrices).
    - **[Calculus](../../pure_mathematics/analysis/)**: Used for training the network via backpropagation and gradient descent.

- **Applications**:
    - **Computer Vision**: Image and video recognition, image classification, object detection, medical image analysis, and facial recognition.
    - **Natural Language Processing**: Sentence classification and other text analysis tasks.
    - **Drug Discovery**: Analyzing molecular structures.
    - **Recommender Systems**: Analyzing patterns in user-item interaction data.

- **More Concrete Variants**:
    - **LeNet-5**: One of the earliest successful CNNs, used for digit recognition.
    - **AlexNet**: A breakthrough architecture that won the 2012 ImageNet competition and popularized deep CNNs.
    - **VGGNet**: Characterized by its simplicity, using only 3x3 convolutional layers stacked on top of each other.
    - **ResNet (Residual Network)**: Introduced "skip connections" to allow for the training of extremely deep networks (hundreds of layers).
    - **Inception (GoogLeNet)**: Used "inception modules" that perform multiple convolutions with different filter sizes in parallel.

- **More General Variants**:
    - **[Artificial Neural Network](./artificial_neural_network.md)**: CNNs are a specific type of ANN with a specialized architecture.

- **Related Concepts**:
    - **[Gradient Descent](./gradient_descent.md)**: The optimization algorithm used to train CNNs.
    - **[Transformer](./transformer.md)**: The Vision Transformer (ViT) is a recent architecture that adapts the Transformer model for computer vision, challenging the dominance of CNNs.
    - **[Recurrent Neural Network (RNN)](./rnn.md)**: Often combined with CNNs for tasks involving both spatial and temporal data, such as video captioning.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Convolutional_neural_network](https://en.wikipedia.org/wiki/Convolutional_neural_network)
