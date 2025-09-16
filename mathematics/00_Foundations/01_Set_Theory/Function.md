# Function

## Mathematical Definition

A **function** is a relation between a set of inputs (the **domain**) and a set of permissible outputs (the **codomain**) with the property that each input is related to exactly one output.

Let \(A\) and \(B\) be sets. A function \(f\) from \(A\) to \(B\), denoted \(f: A \to B\), is a subset of the Cartesian product \(A \times B\) such that for every element \(a \in A\), there is exactly one element \(b \in B\) for which \((a, b)\) is in the subset.

This is often written as \(f(a) = b\), where \(b\) is the unique element of \(B\) assigned by \(f\) to the element \(a\) of \(A\).

*   **Domain of \(f\):** The set \(A\).
*   **Codomain of \(f\):** The set \(B\).
*   **Image (or Range) of \(f\):** The subset of \(B\) consisting of all values \(f(a)\) for \(a \in A\). It is denoted as \(f(A)\) or \(\text{Im}(f)\).

## Description

A function is a rule that assigns each input a single output. It is a fundamental concept in mathematics and is essential for formulating physical relationships in the sciences. The concept of a function can be thought of as a machine that takes an input and produces an output.

## Subfields it's part of

*   [Set Theory](./../01_Set_Theory)
*   Foundations of Mathematics
*   Calculus
*   Algebra
*   Analysis
*   Virtually all fields of mathematics.

## Subfields and concepts it includes

*   **Injective (One-to-One) Function:** A function \(f: A \to B\) is injective if for any two distinct elements \(a_1, a_2 \in A\), their images are distinct, i.e., \(f(a_1) \neq f(a_2)\).
*   **Surjective (Onto) Function:** A function \(f: A \to B\) is surjective if its image is equal to its codomain, i.e., for every \(b \in B\), there is at least one \(a \in A\) such that \(f(a) = b\).
*   **Bijective Function:** A function is bijective if it is both injective and surjective.
*   **Function Composition:** Given two functions \(f: A \to B\) and \(g: B \to C\), the composition \(g \circ f\) is a function from \(A\) to \(C\) defined by \((g \circ f)(a) = g(f(a))\).
*   **Inverse Function:** If a function \(f: A \to B\) is bijective, it has an inverse function \(f^{-1}: B \to A\) such that \(f^{-1}(b) = a\) if and only if \(f(a) = b\).
*   **Identity Function:** For a set \(A\), the identity function \(\text{id}_A: A \to A\) is defined by \(\text{id}_A(a) = a\) for all \(a \in A\).
*   **Graph of a Function:** The set of all ordered pairs \((a, f(a))\) for \(a \in A\).

## Applications

*   **Modeling Relationships:** Functions are used to model relationships between quantities in science, engineering, and economics. For example, the position of an object as a function of time.
*   **Computer Science:** Functions are a fundamental building block of most programming languages.
*   **Calculus:** The study of calculus is centered around functions, exploring concepts like limits, derivatives, and integrals of functions.
*   **Algebra:** In abstract algebra, functions (called homomorphisms) are used to study the relationships between algebraic structures.
*   **Cryptography:** Hash functions are a key component of modern cryptography.

## More general variants

*   **Relation:** A relation is a set of ordered pairs, which is a generalization of a function where an input can be related to multiple outputs.
*   **Partial Function:** A function that is defined only for a subset of its domain.
*   **Multivalued Function:** A "function" that may produce multiple outputs for a single input (more accurately described as a relation).
*   **Morphism:** In category theory, a morphism is a structure-preserving map between two mathematical structures, which is a generalization of a function.
*   **Functor:** A mapping between categories, which can be thought of as a function between categories.

## More concrete variants

*   **Polynomial Functions:** e.g., \(f(x) = ax^2 + bx + c\)
*   **Trigonometric Functions:** e.g., \(\sin(x), \cos(x), \tan(x)\)
*   **Exponential Functions:** e.g., \(f(x) = a^x\)
*   **Logarithmic Functions:** e.g., \(f(x) = \log_b(x)\)
*   **Linear Functions:** e.g., \(f(x) = mx + c\)
*   **Constant Function:** A function that outputs the same value for all inputs.
*   **Recursive Functions:** Functions defined in terms of themselves, used in computability theory.
*   **Vector-Valued Functions:** Functions whose output is a vector.
*   **Functions of several variables:** e.g., \(f(x, y) = x^2 + y^2\)

## Everything else it relates to

*   **Set:** The domain, codomain, and range of a function are sets. A function itself is defined as a specific kind of set of ordered pairs.
*   **Cardinality:** Bijective functions are used to define when two sets have the same cardinality.
*   **Equations:** Solving an equation \(g(x) = h(x)\) can be viewed as finding the inputs where two functions have the same output.
*   **Transformations:** In geometry, functions are used to describe transformations like rotations, reflections, and translations.
