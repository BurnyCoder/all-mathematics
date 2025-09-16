# Lambda Calculus

- **Mathematical Definition**: The lambda calculus is a formal system in mathematical logic for expressing computation based on function abstraction and application using variable binding and substitution. It is a universal model of computation that can be used to simulate any Turing machine. It was introduced by the mathematician Alonzo Church in the 1930s as part of his research into the foundations of mathematics.

- **Description**: Lambda calculus is a minimalistic programming language that provides a theoretical framework for describing functions and their evaluation. It is based on the concept of creating anonymous functions (lambda expressions) and applying them to arguments. Despite its simplicity, it is Turing complete, meaning it can compute anything that a classical computer can.

- **Formal Definition**: The lambda calculus is defined by a set of formal rules for constructing and manipulating lambda expressions.
    - **Terms**: A lambda term is defined recursively as follows:
        1.  A variable, $x$, is a term.
        2.  If $M$ is a term and $x$ is a variable, then $(\lambda x. M)$ is a term (called a lambda abstraction).
        3.  If $M$ and $N$ are terms, then $(M N)$ is a term (called an application).
    - **Axioms and Rules of Conversion**:
        1.  **α-conversion (alpha-conversion)**: Allows the renaming of bound variables. For example, $\lambda x.x$ is equivalent to $\lambda y.y$. Formally: $\lambda x.M \leftrightarrow \lambda y.M[x:=y]$, provided that $y$ is not free in $M$.
        2.  **β-reduction (beta-reduction)**: Describes the process of function application. For example, $(\lambda x.x+1) 2$ reduces to $2+1$. Formally: $(\lambda x.M) N \rightarrow M[x:=N]$.
        3.  **η-conversion (eta-conversion)**: Relates a function to its lambda abstraction. For example, $\lambda x.(f x)$ is equivalent to $f$, if $x$ is not a free variable in $f$. Formally: $\lambda x.(M x) \leftrightarrow M$, provided that $x$ is not free in $M$.

- **Subfields it's part of**:
    - [Computability Theory](https://en.wikipedia.org/wiki/Computability_theory): It is one of the foundational models of computation, alongside Turing machines and recursive functions.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science): It forms the theoretical basis for functional programming languages.
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic): It is a key system in the study of formal languages and computability.

- **Subfields and concepts it includes**:
    - **Lambda Abstraction**: The process of creating a function from an expression by specifying its bound variables.
    - **Function Application**: The act of applying a function to an argument.
    - **Alpha Equivalence**: Renaming the bound variables of a lambda expression.
    - **Beta Reduction**: The process of applying a function to its argument, which is the main computational step in lambda calculus.
    - **Eta Conversion**: A rule that relates a function to a lambda expression that produces the same result for all arguments.

- **Applications**:
    - **Functional Programming Languages**: The design and implementation of languages like Lisp, Haskell, and ML are heavily influenced by lambda calculus.
    - **Type Theory**: It is the foundation for many systems of type theory, especially through the Curry-Howard correspondence.
    - **Proof Assistants**: Systems like Coq and Agda use typed lambda calculi as their underlying logical framework.

- **More Concrete Variants**:
    - **Untyped Lambda Calculus**: The original version of lambda calculus, which does not have a type system. It is powerful but can be inconsistent as a logical system due to paradoxes.
    - **Simply Typed Lambda Calculus**: A version of lambda calculus with a simple type system, which ensures that all programs terminate.

- **More General Variants**:
    - **Polymorphic Lambda Calculus (System F)**: Extends the simply typed lambda calculus with polymorphism, allowing for functions that can operate on values of different types.
    - **Calculus of Constructions**: A higher-order typed lambda calculus that is the basis for the Coq proof assistant.
    - **Lambda-Pi-Calculus**: A framework for defining logical systems and programming languages.

- **Related Concepts**:
    - **[Turing Machine](./turing_machine.md)**: Lambda calculus and Turing machines are equivalent in computational power (Church-Turing thesis).
    - **[Type Theory](../type_theory/type_theory.md)**: Deeply connected, with typed lambda calculi forming the basis of many type theories.
    - **Combinatory Logic**: An alternative model of computation that eliminates the need for bound variables.
    - **[First-Order Logic](../logic/first_order_logic.md)**: While different in nature, both are fundamental systems in mathematical logic.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Lambda_calculus](https://en.wikipedia.org/wiki/Lambda_calculus)
