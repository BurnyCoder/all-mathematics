# Cardinality

## Mathematical Definition

The **cardinality** of a [set](./Set.md) is a measure of the "number of elements" of the set. For a finite set, the cardinality is simply the number of elements in the set. For infinite sets, cardinality provides a way to compare the sizes of different infinite sets.

Two sets \(A\) and \(B\) have the same **cardinality** if there exists a **bijection** (a one-to-one and onto [function](./Function.md)) from \(A\) to \(B\). This is denoted as \(|A| = |B|\).

The cardinality of a set \(A\) is often denoted by \(|A|\), \(card(A)\), or \(\#A\).

Cardinalities themselves are often represented by **cardinal numbers**. For finite sets, these are the natural numbers. For infinite sets, they are the transfinite cardinal numbers, denoted by the Hebrew letter aleph (\(\aleph\)).
*   \(\aleph_0\) (aleph-null) is the cardinality of the set of natural numbers \(\mathbb{N}\).
*   \(\aleph_1\) is the next larger cardinal number, and so on.

## Description

Cardinality formalizes the intuitive notion of size. By using bijections, it allows for a rigorous comparison of set sizes without resorting to counting, which is essential when dealing with infinite sets. The groundbreaking work of Georg Cantor in the late 19th century revealed the surprising fact that there are different "sizes" of infinity.

## Subfields it's part of

*   [Set Theory](./)
*   Foundations of Mathematics

## Subfields and concepts it includes

*   **Finite and Infinite Sets:** A set is finite if its cardinality is a natural number. Otherwise, it is infinite.
*   **Countable and Uncountable Sets:**
    *   A set is **countably infinite** (or denumerable) if it has the same cardinality as the set of natural numbers (\(\aleph_0\)). The integers (\(\mathbb{Z}\)) and rational numbers (\(\mathbb{Q}\)) are countably infinite.
    *   A set is **uncountable** if it is infinite but not countably infinite. The set of real numbers (\(\mathbb{R}\)) is the most famous example of an uncountable set.
*   **Cantor's Theorem:** For any set \(A\), the cardinality of its power set \(P(A)\) (the set of all subsets of A) is strictly greater than the cardinality of \(A\).
    \[ |P(A)| > |A| \]
    This theorem implies that there is an infinite hierarchy of infinite cardinalities.
*   **Cantor's Diagonal Argument:** The classic proof technique used to show that the real numbers are uncountable.
*   **Continuum Hypothesis:** The proposition that there is no set whose cardinality is strictly between that of the integers (\(\aleph_0\)) and the real numbers. The cardinality of the real numbers is denoted by \( \mathfrak{c} \) or \(2^{\aleph_0}\). The hypothesis states that \(\aleph_1 = \mathfrak{c}\). It has been proven to be independent of the standard axioms of set theory (ZFC).
*   **Cardinal Arithmetic:** Rules for adding, multiplying, and exponentiating cardinal numbers.

## Applications

*   **Analysis:** The distinction between countable and uncountable sets is fundamental in measure theory and the theory of integration.
*   **Topology:** Cardinality is used to classify and distinguish topological spaces.
*   **Computer Science:** In computability theory, the set of all possible computer programs is countably infinite, while the set of all functions is uncountable. This implies that there are "uncomputable" functions.
*   **Foundations of Mathematics:** Provides the framework for understanding the size and structure of mathematical objects.

## More general variants

*   In category theory, the concept of the "size" of a category is more subtle and leads to notions like small and large categories.

## More concrete variants

*   The cardinality of a finite set is a non-negative integer.
*   \(\aleph_0\) (the cardinality of the natural numbers).
*   \(\mathfrak{c} = 2^{\aleph_0}\) (the cardinality of the continuum, i.e., the real numbers).

## Everything else it relates to

*   **Bijections:** The formal tool for establishing that two sets have the same cardinality.
*   **Ordinal Numbers:** Another type of transfinite number used to describe the order type of well-ordered sets. For every cardinal number, there is a corresponding initial ordinal.
*   **Power Set:** The power set operation is a way to create sets of larger cardinality.
*   **Hilbert's Hotel:** A famous thought experiment that illustrates the counter-intuitive properties of countably infinite sets.
