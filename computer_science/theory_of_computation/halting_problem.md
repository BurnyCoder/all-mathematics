# Halting Problem

- **Mathematical Definition**: In computability theory, the halting problem is the problem of determining, from a description of an arbitrary computer program and an input, whether the program will finish running (halt) or continue to run forever. Formally, let $H(p, i)$ be a function which is defined as:
    $$
    H(p, i) = \begin{cases}
    \text{"halts"} & \text{if program } p \text{ halts on input } i \\
    \text{"does not halt"} & \text{if program } p \text{ does not halt on input } i
    \end{cases}
    $$
    The halting problem is the problem of determining if there is an algorithm that can compute the function $H$ for any given program $p$ and input $i$. The conclusion is that such a general algorithm does not exist, meaning the function $H$ is not computable. The set of pairs $(p, i)$ for which program $p$ halts on input $i$, known as the halting set $K = \{ (p, i) \mid \text{program } p \text{ halts on input } i \}$, is recursively enumerable but not recursive.

- **Description**: The halting problem is a decision problem that is undecidable. This means that it is impossible to construct a single algorithm that can always correctly decide whether any given program will halt on a given input. Alan Turing proved this in 1936 using a proof by contradiction. The essence of the proof is that any algorithm claimed to solve the halting problem can be fed a "pathological" program that causes it to contradict itself. This result is a fundamental limit on what can be known about computer programs through mechanical means.

- **Subfields it's part of**:
    - [Computability Theory](https://en.wikipedia.org/wiki/Computability_theory): It is one of the first and most famous examples of an undecidable problem, making it a cornerstone of the field.
    - [Theory of Computation](https://en.wikipedia.org/wiki/Theory_of_computation): It establishes fundamental limits on algorithmic computation.
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics): It demonstrates the limits of what can be decided within formal systems.
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic): It is deeply connected to Gödel's incompleteness theorems and questions of decidability in logic.
    - [Computer Science](https://en.wikipedia.org/wiki/Computer_science): It has profound implications for software engineering, program verification, and artificial intelligence, showing that certain properties of programs cannot be determined automatically.

- **Subfields and concepts it includes**:
    - **[Undecidability](https://en.wikipedia.org/wiki/Undecidable_problem)**: The core property of the halting problem is that it is undecidable.
    - **[Turing Machine](./turing_machine.md)**: The problem is formally stated using the Turing machine as the universal model of computation.
    - **[Algorithm](../../computer_science/algorithms_and_data_structures/algorithm.md)**: The problem is about the non-existence of a general algorithm.
    - **[Proof by Contradiction](https://en.wikipedia.org/wiki/Proof_by_contradiction)**: The standard proof of the undecidability of the halting problem uses a diagonal argument, which is a form of proof by contradiction.

- **Applications**:
    - **Theoretical Computer Science**: The halting problem is a key tool for proving that other problems are undecidable through reduction. Many problems in computer science can be shown to be equivalent to the halting problem.
    - **Software Verification**: It implies that no automated tool can check for all possible infinite loops in a program. This motivates the use of restricted programming languages or design patterns in critical systems where termination must be guaranteed.
    - **Philosophy**: It contributes to discussions about the limits of mechanical processes and artificial intelligence, and whether human thought can be fully captured by computation.

- **More Concrete Variants**:
    - **Halting on a specific input**: This is the standard formulation of the problem.
    - **Decidable cases**: For restricted models of computation, like deterministic finite automata or linear bounded automata, the halting problem is decidable.

- **More General Variants**:
    - **The Totality Problem**: The problem of determining if a given Turing machine halts on *all* inputs is also undecidable.
    - **Rice's Theorem**: A generalization which states that any non-trivial property of the function computed by a Turing machine is undecidable. The halting problem is a specific instance of a non-trivial property (halting on a given input).
    - **Oracle Machines**: A Turing machine with an oracle for the halting problem can solve the halting problem for standard Turing machines, but it cannot solve its own halting problem. This leads to a hierarchy of undecidability.

- **Related Concepts**:
    - **[Turing Machine](./turing_machine.md)**: The halting problem is a fundamental question about the limits of what Turing machines (and thus all computers) can compute.
    - **[Gödel's Incompleteness Theorems](../../foundations_of_mathematics/logic/godels_incompleteness_theorems.md)**: The undecidability of the halting problem is the computational equivalent of Gödel's incompleteness theorems, both of which show inherent limitations of formal systems.
    - **[Church-Turing Thesis](https://en.wikipedia.org/wiki/Church%E2%80%93Turing_thesis)**: This thesis states that anything computable by an algorithm can be computed by a Turing machine. It gives the halting problem its broad significance beyond just Turing machines.
    - **[Undecidable Problem](https://en.wikipedia.org/wiki/Undecidable_problem)**: The halting problem is the most famous example of an undecidable problem.
    - **[Algorithm](../algorithms_and_data_structures/algorithm.md)**: The problem demonstrates that not all well-defined problems can be solved by an algorithm.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Halting_problem](https://en.wikipedia.org/wiki/Halting_problem)
