# Proof Techniques

## Mathematical Definition

A **mathematical proof** is a deductive argument for a mathematical statement, showing that the stated assumptions logically guarantee the conclusion. A proof is a sequence of statements, each of which is either an axiom, a hypothesis, or is derived from previous statements by rules of inference.

There are several standard methods for constructing a proof, known as **proof techniques**.

## Description

Proof is the primary method by which mathematical knowledge is established. Different proof techniques provide different strategies for demonstrating the truth of a mathematical statement. Choosing the right technique is a key part of the art of doing mathematics.

## Subfields it's part of

*   [Logic](./)
*   Foundations of Mathematics
*   Proof Theory
*   All fields of mathematics.

## Subfields and concepts it includes

### Direct Proof
The conclusion is established by logically combining the axioms, definitions, and earlier theorems. It is the most straightforward form of proof. To prove a conditional statement \(P \to Q\), one assumes that \(P\) is true and uses that assumption to show that \(Q\) must also be true.

### Proof by Mathematical Induction
Used to prove that a property holds for all natural numbers. It consists of two steps:
1.  **Base Case:** Show that the property holds for the first number (usually 0 or 1).
2.  **Inductive Step:** Show that if the property holds for any one natural number \(n\) (the inductive hypothesis), then it must also hold for its successor, \(n+1\).
These two steps together establish that the property holds for all natural numbers.

### Proof by Contradiction (Reductio ad Absurdum)
To prove a proposition \(P\), one assumes that its negation, \(\neg P\), is true. Then, using this assumption, one derives a logical contradiction (a statement of the form \(Q \land \neg Q\)). Since the assumption has led to a contradiction, the assumption must be false, and therefore the original proposition \(P\) must be true.

### Proof by Contrapositive (Proof by Contraposition)
To prove a conditional statement \(P \to Q\), one can prove its logically equivalent **contrapositive**, which is \(\neg Q \to \neg P\). This involves assuming that \(\neg Q\) is true and showing that this leads to the conclusion that \(\neg P\) is also true.

### Proof by Construction (Constructive Proof)
A method of proof that demonstrates the existence of a mathematical object by providing a method for creating it. For example, to prove that there exists an even prime number, one can construct the number 2 and show that it is both even and prime.

### Proof by Exhaustion (Proof by Cases)
The conclusion is established by dividing it into a finite number of cases and proving each one separately.

### Nonconstructive Proof (Existence Proof)
A proof that establishes that a certain mathematical object must exist without explaining how to find it. Often proceeds by contradiction. For example, one can prove there exist two irrational numbers \(a\) and \(b\) such that \(a^b\) is rational, without identifying what \(a\) and \(b\) are.

## Applications

*   **Verifying Mathematical Truth:** The primary application is to establish the truth of theorems in all areas of mathematics.
*   **Computer Science:** Formal verification of software and hardware relies on proof techniques. Proof assistants are software tools that help in the development of formal proofs. The concept of a constructive proof is central to the theory of computation.
*   **Philosophy:** Used to analyze the structure and validity of arguments.

## More general variants

*   **Proof Theory:** The branch of mathematical logic that treats proofs as formal mathematical objects, facilitating their analysis by mathematical techniques.
*   **Automated Theorem Proving:** The use of computer programs to automatically produce formal proofs.

## Everything else it relates to

*   **Axiomatic Systems:** Proofs are constructed within a system of axioms (e.g., ZFC for set theory, Peano axioms for arithmetic).
*   **Inference Rules:** The specific rules that allow one to move from one statement to another in a proof (e.g., *Modus Ponens*).
*   **Intuitionistic Logic:** A school of thought in the philosophy of mathematics that emphasizes constructive proofs and rejects proof by contradiction for existence proofs.
*   **Gödel's Incompleteness Theorems:** These theorems place fundamental limits on what can be proven within any sufficiently powerful formal axiomatic system.
