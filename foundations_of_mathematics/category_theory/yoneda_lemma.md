# Yoneda Lemma

- **Mathematical Definition**: Let $\mathcal{C}$ be a locally small category, and let $F: \mathcal{C} \to \mathbf{Set}$ be a functor from $\mathcal{C}$ to the category of sets. For any object $A$ in $\mathcal{C}$, the Yoneda lemma states that there is a one-to-one correspondence between the set of natural transformations from the hom-functor $h_A = \text{Hom}(A, -)$ to $F$, and the set $F(A)$. This correspondence is natural in both $A$ and $F$.
  
  The isomorphism is given by:
  \[ \text{Nat}(\text{Hom}(A, -), F) \cong F(A) \]
  
  - Given a natural transformation $\Phi: \text{Hom}(A, -) \to F$, the corresponding element in $F(A)$ is $u = \Phi_A(\text{id}_A)$, where $\text{id}_A$ is the identity morphism on $A$.
  - Given an element $u \in F(A)$, the corresponding natural transformation $\Phi_u: \text{Hom}(A, -) \to F$ is defined for an object $X$ in $\mathcal{C}$ and a morphism $f: A \to X$ by $\Phi_u(f) = (Ff)(u)$.

- **Description**: The Yoneda lemma is a fundamental result in category theory that establishes a deep connection between objects of a category and functors on that category. It essentially states that an object is completely determined by the network of morphisms from it to all other objects in the category. This allows for the embedding of any locally small category into a category of functors, which is often a more structured and convenient setting to work in. It is a vast generalization of Cayley's theorem from group theory.

- **Subfields it's part of**:
    - [Category Theory](./category.md): It is one of the most important results in elementary category theory.
    - [Foundations of Mathematics](../README.md): As a core result within category theory, it plays a role in foundational studies.

- **Subfields and concepts it includes**:
    - **Yoneda Embedding**: A direct and crucial corollary of the Yoneda lemma. It is a functor $Y: \mathcal{C} \to \mathbf{Set}^{\mathcal{C}^{\text{op}}}$ (the category of presheaves on $\mathcal{C}$) that is full and faithful, meaning it embeds $\mathcal{C}$ into the functor category.
    - **Representable Functor**: The lemma is key to understanding representable functors. A functor is representable if it is naturally isomorphic to a hom-functor. The Yoneda lemma implies that the representation of such a functor (the representing object) is unique up to a unique isomorphism.

- **Applications**:
    - **Mathematics**:
        - [Algebraic Geometry](https://en.wikipedia.org/wiki/Algebraic_geometry): The philosophy of treating schemes and varieties as functors of points (the "functor of points" approach) is a direct application of the Yoneda perspective.
        - [Representation Theory](https://en.wikipedia.org/wiki/Representation_theory): It provides a powerful way to study objects by considering the modules or representations associated with them.
    - **Computer Science**:
        - [Functional Programming](https://en.wikipedia.org/wiki/Functional_programming): The Yoneda lemma has applications in theoretical computer science, particularly in the semantics of programming languages and in functional programming, for example in the formulation of continuation-passing style (CPS) and the understanding of data structures like lenses. The concept of a "Yoneda embedding" for data types allows for certain performance optimizations.

- **More Concrete Variants**:
    - **[Cayley's Theorem](https://en.wikipedia.org/wiki/Cayley's_theorem)**: In group theory, Cayley's theorem states that every group is isomorphic to a subgroup of a permutation group. This can be seen as a special case of the Yoneda lemma applied to a category with a single object.

- **More General Variants**:
    - **Enriched Category Theory**: The Yoneda lemma can be generalized to the context of enriched categories, where the hom-sets are objects in a monoidal category other than **Set**.

- **Related Concepts**:
    - **[Functor](./category.md)**: The lemma relates objects to hom-functors.
    - **[Natural Transformation](./category.md)**: It establishes a bijection with a set of natural transformations.
    - **[Representable Functor](./category.md)**: It is central to the theory of representable functors.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Yoneda_lemma](https://en.wikipedia.org/wiki/Yoneda_lemma)
