# Graphs and Trees

Graphs are a versatile, non-linear data structure used to model a wide array of real-world problems. They consist of nodes (or vertices) and edges connecting them, which can represent network systems, dependencies, and more. Trees are a type of graph, but trees have special constraints that set them apart from graphs such as being connected, acyclic, and having a unique node known as the root.

## Common Algorithms

### Depth-First Search (DFS)

Depth-first search is an algorithm for traversing a graph. It explores as far as possible along each branch before backtracking. When using depth-first search on a binary tree, there are 3 possible traversal types:
1. Preorder: The root node is visited first, followed by recursive visits to the left and then the right subtree. This order is useful for serializing or cloning a tree.
2. Inorder: Starts with the left subtree, visits the root node next, and finishes with the right subtree. This order is useful for binary search trees where it retrieves elements in their sorted order.
3. Postorder: Visits the left subtree first, then the right subtree, and the root node last. This order is useful for deleting or freeing nodes and space of the tree post-computation.

#### Backtracking

Backtracking algorithms are typically implemented with depth-first search. These backtracking algorithms are particularly good at solving problems that involve combinatorics, and they take an exhaustive approach to solving problems meaning that all valid combinations are attempted. However, this also means that backtracking algorithms are slow, and there may be other more optimized solutions to the problem.

### Breadth-First Ssearch (BFS)

Breadth-first search is an algorithm for traversing a graph in level-order. This means that rather than exploring as far as possible along each branch before backtracking like depth-first search, breadth-first search instead visits the nodes that are connected to the current node with an edge. Level-order traversal is useful for finding the shortest path in an unweighted graph.
