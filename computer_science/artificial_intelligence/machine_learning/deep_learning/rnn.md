# Recurrent Neural Network (RNN)

- **Mathematical Definition**: A Recurrent Neural Network (RNN) processes a sequence of inputs $x = (x_1, x_2, ..., x_T)$. The hidden state $h_t$ at time step $t$ is a function of the previous hidden state $h_{t-1}$ and the input at the current step $x_t$. The output $y_t$ is a function of the hidden state $h_t$. The core equations are:
$$ h_t = f(W_{hh}h_{t-1} + W_{xh}x_t + b_h) $$
$$ y_t = W_{hy}h_t + b_y $$
  where $W_{hh}, W_{xh}, W_{hy}$ are weight matrices, $b_h, b_y$ are bias vectors, and $f$ is a non-linear activation function like $\tanh$ or ReLU. The same weights are used for every time step, allowing the network to share parameters across the sequence.

- **Description**: Recurrent Neural Networks (RNNs) are a class of artificial neural networks where connections between nodes form a directed graph along a temporal sequence. This allows them to exhibit temporal dynamic behavior. Unlike feedforward neural networks, RNNs can use their internal state (memory), represented by the hidden state, to process sequences of inputs. This makes them particularly well-suited for tasks involving sequential data.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): RNNs are a fundamental model in machine learning for sequence data.
    - [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning): As they are typically composed of multiple layers, they are a core component of deep learning.
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence): RNNs contribute to building intelligent systems that can understand and process sequential information.
    - [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing): A primary application area for RNNs due to the sequential nature of language.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science): The design and analysis of RNNs are topics within computer science.

- **Subfields and concepts it includes**:
    - **Backpropagation Through Time (BPTT)**: The algorithm used to train RNNs by unrolling the network through time and applying standard backpropagation.
    - **Vanishing/Exploding Gradients**: A major challenge in training RNNs on long sequences, where gradients can become infinitesimally small or infinitely large.
    - **Sequential Data**: The type of data that RNNs are designed to model, such as text, speech, and time series.
    - **[Linear Algebra](../../pure_mathematics/linear_algebra/)**: The core operations are matrix-vector multiplications.
        - **[Vector Space](../../pure_mathematics/linear_algebra/vector_space.md)**: Inputs, hidden states, and outputs are represented as vectors.
        - **[Matrix](../../pure_mathematics/linear_algebra/matrix.md)**: The learned parameters of the model are stored in matrices.

- **Applications**:
    - **Natural Language Processing (NLP)**: Language modeling, machine translation, speech recognition, sentiment analysis.
    - **Time Series Analysis**: Stock market prediction, weather forecasting, and anomaly detection.
    - **Video Analysis**: Action recognition and video captioning.
    - **Music Generation**: Composing musical pieces.

- **More Concrete Variants**:
    - **[Long Short-Term Memory (LSTM)](./lstm.md)**: A sophisticated type of RNN that uses gating mechanisms to overcome the vanishing gradient problem and learn long-term dependencies.
    - **Gated Recurrent Unit (GRU)**: A simpler variant of LSTM that also uses gating mechanisms.
    - **Bidirectional RNN**: Processes the input sequence in both forward and backward directions to capture context from both past and future steps.

- **More General Variants**:
    - **[Artificial Neural Network](./artificial_neural_network.md)**: RNNs are a specific architecture of ANNs designed for sequential data.
    - **Sequence-to-Sequence (Seq2Seq) Models**: An architecture often built using RNNs (or LSTMs/GRUs) as encoders and decoders to map one sequence to another.

- **Related Concepts**:
    - **[Gradient Descent](./gradient_descent.md)**: The optimization algorithm used to train RNNs by minimizing a loss function.
    - **[Transformer](./transformer.md)**: A newer architecture for sequence modeling that uses self-attention instead of recurrence and has become dominant in NLP.
    - **[Convolutional Neural Network (CNN)](./cnn.md)**: Often used in combination with RNNs for tasks involving spatio-temporal data, like video processing.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Recurrent_neural_network](https://en.wikipedia.org/wiki/Recurrent_neural_network)
