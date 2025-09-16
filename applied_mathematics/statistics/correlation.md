# Correlation

- **Mathematical Definition**: Correlation is a statistical measure that expresses the extent to which two variables are linearly related, meaning they change together at a constant rate. The most common measure of correlation is the **Pearson correlation coefficient**, typically denoted by $\rho$ for a population and $r$ for a sample. For a sample of paired data $(x_i, y_i)$, the Pearson correlation coefficient is calculated as:
  $$ r = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2 \sum_{i=1}^{n} (y_i - \bar{y})^2}} $$
  where $n$ is the sample size, and $\bar{x}$ and $\bar{y}$ are the sample means. The value of $r$ ranges from -1 (perfect negative linear correlation) to +1 (perfect positive linear correlation), with 0 indicating no linear correlation.

- **Description**: Correlation quantifies the direction and strength of the linear relationship between two quantitative variables. A positive correlation means that as one variable increases, the other tends to increase. A negative correlation means that as one variable increases, the other tends to decrease. It is crucial to remember that **correlation does not imply causation**; two variables can be correlated without one causing the other.

- **Subfields it's part of**:
    - [Statistics](https://en.wikipedia.org/wiki/Statistics): A fundamental concept in descriptive and inferential statistics.
    - [Probability Theory](https://en.wikipedia.org/wiki/Probability_theory): Correlation is a property of the joint distribution of two random variables.
    - [Data Analysis](https://en.wikipedia.org/wiki/Data_analysis): One of the first steps in exploring relationships within a dataset.
    - [Machine Learning](https://en.wikipedia.org/wiki/Machine_learning): Used in feature selection and understanding data.

- **Subfields and concepts it includes**:
    - **Covariance**: A measure of the joint variability of two random variables. Correlation is a standardized version of covariance.
    - **Scatter Plot**: A graphical representation used to visualize the correlation between two variables.
    - **Coefficient of Determination ($r^2$)**: The square of the correlation coefficient, which represents the proportion of the variance in one variable that is predictable from the other variable.
    - [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra):
        - The correlation formula can be interpreted geometrically as the cosine of the angle between two vectors in a high-dimensional space.

- **Applications**:
    - **Finance**: To measure the correlation between the returns of different assets for portfolio diversification.
    - **Social Sciences**: To study relationships between variables like education level and income.
    - **Epidemiology**: To identify associations between risk factors and diseases.
    - **Data Science**: For exploratory data analysis and as a precursor to building predictive models.

- **More Concrete Variants**:
    - **Pearson Correlation Coefficient**: Measures the linear relationship between two continuous variables.
    - **Spearman's Rank Correlation**: A non-parametric measure of the monotonic relationship between two variables.
    - **Kendall's Tau**: Another non-parametric rank-based correlation coefficient.

- **More General Variants**:
    - **Covariance**: A more general, unnormalized measure of how two variables change together.
    - **Mutual Information**: A concept from information theory that can detect non-linear relationships between variables.

- **Related Concepts**:
    - **[Regression Analysis](../../computer_science/machine_learning/regression_analysis.md)**: While correlation measures the strength of a relationship, regression describes its nature and can be used for prediction.
    - **Causation**: A common fallacy is to confuse correlation with causation.
    - **[Random Variable](../probability_theory/random_variable.md)**: Correlation is a property of two random variables.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Correlation](https://en.wikipedia.org/wiki/Correlation)
