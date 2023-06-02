# General

*    What is a binary tree
A binary tree is a type of hierarchical data structure that consists of nodes, where each node has at most two children, referred to as the left child and the right child. The structure resembles a tree, with the topmost node called the root.

## key terms related to binary trees:

    Root: The topmost node of the tree, which does not have a parent.
    Parent: A node that has one or more children.
    Child: The nodes directly connected to a parent node.
    Leaf: A node that has no children.
    Internal node: A node that has at least one child.
    Depth: The number of edges from the root to a particular node.
    Height: The maximum depth of any node in the tree.
    Sub-tree: A smaller tree formed by a node and its descendants.

*    What is the difference between a binary tree and a Binary Search Tree
## A binary tree is a general tree structure where each node can have at most two children, while a binary search tree is a binary tree with an ordering property that allows for efficient searching, insertion, and deletion based on the element values.

*    What is the possible gain in terms of time complexity compared to linked lists
## Binary trees offer more efficient search, insertion, and deletion operations compared to linked lists, particularly when the binary tree is balanced. However, in the worst case of an unbalanced binary tree, the time complexity can degrade to be similar to or worse than linked lists. Linked lists have a linear search time complexity, but they can offer constant-time insertion and deletion at the beginning or end of the list.

*    What are the depth, the height, the size of a binary tree
*    What are the different traversal methods to go through a binary tree
Binary trees can be traversed in different ways, including:

    Pre-order traversal: Visit the root, then recursively visit the left sub-tree, and finally recursively visit the right sub-tree.
    In-order traversal: Recursively visit the left sub-tree, visit the root, and then recursively visit the right sub-tree. This traversal produces nodes in sorted order for binary search trees.
    Post-order traversal: Recursively visit the left sub-tree, recursively visit the right sub-tree, and then visit the root.

*    What is a complete, a full, a perfect, a balanced binary tree
A complete binary tree is a binary tree in which every level, except possibly the last, is completely filled, and all nodes in the last level are as far left as possible.

A balanced binary tree is a binary tree structure in which the left and right subtrees of every node differ in height by no more than 1.

A perfect binary tree is a binary tree in which all interior nodes have two children and all leaves have the same depth or same level.


