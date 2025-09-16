# Turing Machine

- **Mathematical Definition**: A Turing machine is a mathematical model of computation that defines an abstract machine which manipulates symbols on a strip of tape according to a table of rules. Despite its simplicity, a Turing machine can be adapted to simulate the logic of any computer algorithm. A standard Turing machine is formally defined as a 7-tuple \\(M = \langle Q, \Gamma, b, \Sigma, \delta, q_0, F \rangle\\) where:
    - \\(Q\\) is a finite set of **states**.
    - \\(\Gamma\\) is a finite set of tape **symbols**.
    - \\(b \in \Gamma\\) is the **blank symbol**.
    - \\(\Sigma \subseteq \Gamma \setminus \{b\}\\) is the set of **input symbols**.
    - \\(\delta: (Q \setminus F) \times \Gamma \to Q \times \Gamma \times \{L, R\}\\) is the **transition function**.
    - \\(q_0 \in Q\\) is the **initial state**.
    - \\(F \subseteq Q\\) is the set of **final or accepting states**.

- **Description**: The Turing machine was invented in 1936 by Alan Turing. It is not a practical computing technology, but a thought experiment about the limits of mechanical computation. It provides a precise, formal definition of what it means for a function to be "computable". The **Church-Turing thesis** states that any function that can be computed by an algorithm can be computed by a Turing machine. This means that if a problem cannot be solved by a Turing machine, it cannot be solved by any computer.

- **Subfields it's part of**:
    - [Computability Theory](https://en.wikipedia.org/wiki/Computability_theory)
    - [Theory of Computation](https://en.wikipedia.org/wiki/Theory_of_computation)
    - [Foundations of Mathematics](https://en.wikipedia.org/wiki/Foundations_of_mathematics)
    - [Mathematical Logic](https://en.wikipedia.org/wiki/Mathematical_logic)

- **Subfields and concepts it includes**:
    - **State**: The internal configuration of the machine.
    - **Tape**: The machine's memory, an infinite strip of cells.
    - **Transition Function**: The "program" of the machine, which dictates its actions.
    - **Computable Function**: A function for which a Turing machine can compute the output for any given input.
    - **Halting Problem**: The undecidable problem of determining, from a description of an arbitrary computer program and an input, whether the program will finish running or continue to run forever.

- **Applications**:
    - **Theoretical Computer Science**: Used to prove fundamental limits on the power of computers. It forms the basis of complexity theory.
    - **Philosophy of Mind**: Used in arguments about whether human intelligence can be simulated by a machine.

- **More Concrete Variants**:
    - **Deterministic Turing Machine**: The standard model where the transition function specifies exactly one action for each situation.
    - **Non-deterministic Turing Machine**: A machine where the transition function may specify multiple possible actions. These are equivalent in computational power to deterministic machines but are important in complexity theory.
    - **Universal Turing Machine**: A Turing machine that can simulate any other Turing machine. This is the theoretical basis for general-purpose computers.

- **More General Variants**:
    - **Oracle Machine**: A Turing machine with a "black box" (an oracle) that can solve a specific problem in a single step.

- **Related Concepts**:
    - **[Algorithm](../../computer_science/algorithms_and_data_structures/algorithm.md)**: The Church-Turing thesis uses the Turing machine to formally define what an algorithm is.
    - **[First-Order Logic](../logic/first_order_logic.md)**: Computability theory is deeply connected to questions about the decidability of logical theories.
    - **Gödel's Incompleteness Theorems**: Turing's work on the halting problem was inspired by and closely related to Gödel's work on the limits of formal mathematical systems.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Turing_machine](https://en.wikipedia.org/wiki/Turing_machine)
