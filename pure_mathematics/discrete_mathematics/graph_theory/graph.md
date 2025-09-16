# Graph (Graph Theory)

- **Mathematical Definition**: In graph theory, a graph is a mathematical structure used to model pairwise relations between objects. A graph in this context is made up of **vertices** (also called nodes or points) which are connected by **edges** (also called links or lines). A simple graph is an ordered pair $G = (V, E)$ where:
    - $V$ is a set of vertices.
    - $E$ is a set of 2-element subsets of $V$, representing the edges.
  For an edge $\{u, v\}$ in $E$, the vertices $u$ and $v$ are called its endpoints.

- **Description**: Graph theory is a major branch of discrete mathematics. Graphs are one of the most ubiquitous models in computer science and applied mathematics, used to represent networks of all kinds, from social networks and computer networks to molecular structures and dependencies in a project.

- **Subfields it's part of**:
    - [Graph Theory](https://en.wikipedia.org/wiki/Graph_theory): A graph is the fundamental object of study in graph theory.
    - [Discrete Mathematics](https://en.wikipedia.org/wiki/Discrete_mathematics): Graph theory is a core pillar of discrete mathematics.
    - [Combinatorics](https://en.wikipedia.org/wiki/Combinatorics): Graph theory is closely related to combinatorics, and many graph problems are combinatorial in nature (e.g., counting paths or colorings).

- **Subfields and concepts it includes**:
    - **Vertex and Edge**: The fundamental components of a graph.
    - **Path**: A sequence of edges connecting a sequence of vertices.
    - **Cycle**: A path that starts and ends at the same vertex.
    - **Connectivity**: A measure of how connected a graph is.
    - **Graph Coloring**: An assignment of labels (colors) to vertices such that no two adjacent vertices share the same color.
    - **Planar Graph**: A graph that can be drawn on a plane without any edges crossing.

- **Applications**:
    - **Computer Science**: Modeling computer networks, social networks (e.g., Facebook, Twitter), and the structure of websites (the World Wide Web). Used in algorithms for pathfinding (e.g., GPS navigation), scheduling, and data compression.
    - **Chemistry and Biology**: Representing molecules, protein-protein interaction networks, and evolutionary trees.
    - **Operations Research**: Modeling and solving problems in logistics, transportation, and supply chain management.
    - **Linguistics**: Modeling the structure of language (syntactic trees).

- **More Concrete Variants**:
    - **Directed Graph (Digraph)**: A graph where edges have a direction (represented by ordered pairs of vertices).
    - **Weighted Graph**: A graph where a number (weight) is assigned to each edge.
    - **Tree**: A connected graph with no cycles.
    - **Bipartite Graph**: A graph whose vertices can be divided into two disjoint sets such that every edge connects a vertex in the first set to one in the second set.

- **More General Variants**:
    - **Hypergraph**: A generalization of a graph in which an edge can join any number of vertices.
    - **Matroid**: An abstract structure that captures and generalizes the notion of linear independence in vector spaces and cycles in graphs.

- **Related Concepts**:
    - **[Set](../../foundations_of_mathematics/set_theory/set.md)**: A graph is defined in terms of sets of vertices and edges.
    - **[Matrix](../linear_algebra/matrix.md)**: A graph can be represented by a matrix (e.g., an adjacency matrix or an incidence matrix).
    - **[Algorithm](../../../computer_science/algorithms_and_data_structures/algorithm.md)**: Many fundamental algorithms are designed to solve problems on graphs.

- **Wikipedia**: [https://en.wikipedia.org/wiki/Graph_(discrete_mathematics)](https://en.wikipedia.org/wiki/Graph_(discrete_mathematics))
