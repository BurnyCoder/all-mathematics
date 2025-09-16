# Support Vector Machine (SVM)

- **Mathematical Definition**: A support vector machine is a supervised learning model used for classification and regression analysis. For a classification task, an SVM constructs a hyperplane or set of hyperplanes in a high-dimensional space, which can be used for classification. A good separation is achieved by the hyperplane that has the largest distance to the nearest training data point of any class (so-called **functional margin**). This is known as maximizing the margin. For a given training dataset of $n$ points of the form $(\mathbf{x}_i, y_i)$, where $y_i$ is either 1 or -1, the SVM finds the maximum-margin hyperplane by solving the optimization problem:
$$ \min_{\mathbf{w}, b} \frac{1}{2} ||\mathbf{w}||^2 $$
  subject to $ y_i(\mathbf{w} \cdot \mathbf{x}_i - b) \ge 1 $ for all $i=1, \dots, n$.
  The **kernel trick** allows SVMs to perform non-linear classification by implicitly mapping their inputs into high-dimensional feature spaces.

- **Description**: SVMs are a powerful and versatile class of machine learning models. The core idea is to find the "best" boundary that separates different classes of data. The "best" boundary is the one that is as far away as possible from the data points of all classes. The data points that are closest to the boundary are called "support vectors" and are the most critical elements of the dataset.

- **Subfields it's part of**:
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)
    - [Statistical Learning Theory](https://en.wikipedia.org/wiki/Statistical_learning_theory)
    - [Optimization](https://en.wikipedia.org/wiki/Mathematical_optimization)
    - [Kernel Methods](https://en.wikipedia.org/wiki/Kernel_method)

- **Subfields and concepts it includes**:
    - **Hyperplane**: A subspace of one dimension less than its ambient space. In 2D, a line; in 3D, a plane.
    - **Margin**: The distance between the separating hyperplane and the closest data points.
    - **Support Vectors**: The data points that lie closest to the decision boundary.
    - **Kernel Trick**: A technique to apply SVMs to non-linear data by using a kernel function to compute the dot product of the data points in a higher-dimensional space without explicitly transforming them.
    - **Hinge Loss**: A common loss function used for training SVMs.
    - **[Linear Algebra](../../pure_mathematics/linear_algebra/)**: The concepts of hyperplanes, vectors, and dot products are central to SVMs.
        - **[Vector Space](../../pure_mathematics/linear_algebra/vector_space.md)**: The data points are treated as vectors in a high-dimensional space.
    - **[Topology](../../pure_mathematics/topology/)**:
        - **[Metric Space](../../pure_mathematics/topology/metric_space.md)**: The margin is defined by a distance metric between the separating hyperplane and the support vectors.

- **Applications**:
    - **Bioinformatics**: Classifying proteins and genes.
    - **Text Classification**: Categorizing documents.
    - **Image Recognition**: Used for tasks like face detection.
    - **Handwriting Recognition**.

- **More Concrete Variants**:
    - **Linear SVM**: An SVM that uses a linear separating hyperplane.
    - **Kernel SVM**: An SVM that uses the kernel trick to handle non-linear data (e.g., with a polynomial or radial basis function (RBF) kernel).

- **More General Variants**:
    - **Support Vector Regression (SVR)**: An adaptation of SVMs for regression problems.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Support_vector_machine](https://en.wikipedia.org/wiki/Support_vector_machine)
