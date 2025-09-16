# Transformer

- **Mathematical Definition**: The core of the Transformer model is the self-attention mechanism. For an input sequence represented by a matrix $X$, the mechanism computes Query ($Q$), Key ($K$), and Value ($V$) matrices by multiplying $X$ with learned weight matrices $W_Q, W_K, W_V$. The output is calculated as:
$$ \text{Attention}(Q, K, V) = \text{softmax}\left(\frac{QK^T}{\sqrt{d_k}}\right)V $$
  where $d_k$ is the dimension of the key vectors. This formula allows the model to weigh the importance of different parts of the input sequence. Transformers use **Multi-Head Attention**, which applies the attention mechanism multiple times in parallel to jointly attend to information from different representation subspaces. To incorporate sequence order, **Positional Encodings** are added to the input embeddings, as the model architecture itself does not have a notion of sequence. The overall architecture is typically an **encoder-decoder** stack, where each layer contains a multi-head attention module and a position-wise **feed-forward network**.

- **Description**: The Transformer is a deep learning model architecture introduced in the 2017 paper "Attention Is All You Need". It has become the dominant architecture for natural language processing (NLP) tasks and is increasingly used in other domains like computer vision. Unlike recurrent neural networks (RNNs) that process data sequentially, the Transformer processes the entire input sequence at once using a self-attention mechanism, allowing for significant parallelization and capturing long-range dependencies more effectively.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): Transformers are a class of models developed within machine learning.
    - [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning): It is a deep neural network architecture, representing a key breakthrough in deep learning.
    - [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence): The capabilities of Transformers have significantly advanced the state-of-the-art in AI.
    - [Natural Language Processing](https://en.wikipedia.org/wiki/Natural_language_processing): The architecture was originally designed for and has revolutionized NLP tasks.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science): It is a significant contribution to the field of computer science, particularly in the area of AI and algorithms.

- **Subfields and concepts it includes**:
    - **Self-Attention**: A mechanism that allows the model to weigh the importance of different words in an input sequence when processing a specific word.
    - **Multi-Head Attention**: An extension of self-attention that runs the attention mechanism in parallel multiple times, allowing the model to jointly attend to information from different representation subspaces.
    - **Positional Encoding**: Since the model contains no recurrence, positional encodings are added to the input embeddings to give the model information about the relative or absolute position of the tokens in the sequence.
    - **Encoder-Decoder Architecture**: A structure where an encoder maps an input sequence to a continuous representation, which the decoder then uses to generate an output sequence.
    - **Feed-Forward Network**: Each layer in the encoder and decoder contains a fully connected feed-forward network.
    - **[Linear Algebra](../../pure_mathematics/linear_algebra/)**: The attention mechanism and feed-forward layers rely heavily on matrix multiplications.
        - **[Vector Space](../../pure_mathematics/linear_algebra/vector_space.md)**: Words and tokens are represented as vectors (embeddings) in a high-dimensional space.
        - **[Matrix](../../pure_mathematics/linear_algebra/matrix.md)**: Self-attention and other key operations are heavily based on matrix manipulations.

- **Applications**:
    - **Natural Language Processing (NLP)**: Machine translation, text summarization, question answering, sentiment analysis, and language generation (e.g., GPT).
    - **Computer Vision**: Image classification, object detection, and image generation (e.g., Vision Transformer (ViT), DALL-E).
    - **Bioinformatics**: Protein structure prediction (e.g., AlphaFold).
    - **Audio Processing**: Speech recognition and music generation.

- **More Concrete Variants**:
    - **BERT (Bidirectional Encoder Representations from Transformers)**: An encoder-only model that learns deep bidirectional representations from unlabeled text.
    - **GPT (Generative Pre-trained Transformer)**: A decoder-only model, famous for its ability to generate human-like text.
    - **T5 (Text-to-Text Transfer Transformer)**: An encoder-decoder model that treats every NLP problem as a "text-to-text" problem.
    - **Vision Transformer (ViT)**: An adaptation of the Transformer architecture for computer vision tasks.

- **More General Variants**:
    - **[Artificial Neural Network](./artificial_neural_network.md)**: The Transformer is a specific type of neural network architecture.
    - **Sequence-to-Sequence (Seq2Seq) Models**: A class of models that map an input sequence to an output sequence. The original Transformer was proposed as a new architecture for Seq2Seq tasks.

- **Related Concepts**:
    - **[Artificial Neural Network](./artificial_neural_network.md)**: Transformers are a type of ANN.
    - **[Gradient Descent](./gradient_descent.md)**: Used to train Transformer models by minimizing a loss function.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)](https://en.wikipedia.org/wiki/Transformer_(machine_learning_model))
