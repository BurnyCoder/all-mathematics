# Long Short-Term Memory (LSTM)

- **Mathematical Definition**: Long Short-Term Memory (LSTM) is a type of Recurrent Neural Network (RNN) architecture that uses a gating mechanism to regulate the flow of information, enabling it to learn long-term dependencies. The key components are the cell state ($C_t$) and three gates: forget ($f_t$), input ($i_t$), and output ($o_t$).

The updates at each time step $t$ are calculated as follows:
$$
\begin{align*}
f_t &= \sigma(W_f \cdot [h_{t-1}, x_t] + b_f) \quad \text{(Forget Gate)} \\
i_t &= \sigma(W_i \cdot [h_{t-1}, x_t] + b_i) \quad \text{(Input Gate)} \\
\tilde{C}_t &= \tanh(W_C \cdot [h_{t-1}, x_t] + b_C) \quad \text{(New Candidate Values)} \\
C_t &= f_t \odot C_{t-1} + i_t \odot \tilde{C}_t \quad \text{(Cell State Update)} \\
o_t &= \sigma(W_o \cdot [h_{t-1}, x_t] + b_o) \quad \text{(Output Gate)} \\
h_t &= o_t \odot \tanh(C_t) \quad \text{(Hidden State Update)}
\end{align*}
$$
  where $x_t$ is the input, $h_{t-1}$ is the previous hidden state, $C_{t-1}$ is the previous cell state, $W$ and $b$ are weight matrices and bias vectors, $\sigma$ is the sigmoid function, and $\odot$ denotes element-wise multiplication.

- **Description**: LSTMs, introduced by Hochreiter & Schmidhuber in 1997, were designed to overcome the vanishing gradient problem that affects traditional RNNs. The cell state acts as a conveyor belt, carrying information through the sequence with minimal linear transformations, while the gates—composed of sigmoid neural network layers and element-wise multiplication operations—control what information is added to or removed from the cell state.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): A key model for sequential data in machine learning.
    - [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning): A fundamental architecture in deep learning for sequence modeling.
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence): Powers many AI applications involving sequence understanding.
    - [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing): Extensively used for tasks like translation, text generation, and sentiment analysis.

- **Subfields and concepts it includes**:
    - **Gating Mechanism**: The core innovation of LSTMs, allowing for better control of information flow and memory.
    - **Cell State**: The internal memory of the LSTM unit that preserves information over long periods.
    - **[Recurrent Neural Network (RNN)](./rnn.md)**: LSTM is a specialized and more powerful type of RNN.
    - **[Linear Algebra](../../pure_mathematics/linear_algebra/)**: The entire architecture is built upon matrix and vector operations.

- **Applications**:
    - **Natural Language Processing (NLP)**: Machine translation, speech recognition, language modeling, sentiment analysis.
    - **Time Series Prediction**: Financial forecasting, weather prediction.
    - **Handwriting Recognition and Generation**.
    - **Music Generation**.

- **More Concrete Variants**:
    - **Gated Recurrent Unit (GRU)**: A simplified version of the LSTM with fewer parameters, combining the forget and input gates into a single "update gate".
    - **Peephole LSTMs**: A variation where the gate layers are allowed to look at the cell state.
    - **Bidirectional LSTM**: Processes the sequence in both forward and backward directions to incorporate both past and future context.

- **More General Variants**:
    - **[Recurrent Neural Network (RNN)](./rnn.md)**: LSTMs are a specific, more advanced implementation of the RNN concept.
    - **[Artificial Neural Network](./artificial_neural_network.md)**: A more general class of models to which LSTMs belong.

- **Related Concepts**:
    - **[Gradient Descent](./gradient_descent.md)**: Used to train LSTMs.
    - **Vanishing Gradient Problem**: The problem that LSTMs were specifically designed to solve.
    - **[Transformer](./transformer.md)**: A popular, more recent alternative to LSTMs for many sequence-based tasks, particularly in NLP.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Long_short-term_memory](https://en.wikipedia.org/wiki/Long_short-term_memory)
