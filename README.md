# binary_trees
In computer science, a binary tree is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child. A recursive definition using just set theory notions is that a (non-empty) binary tree is a tuple (L, S, R), where L and R are binary trees or the empty set and S is a singleton set containing the root.

### Types of Binary Trees

Tree terminology is not well-standardized and so varies in the literature.

A rooted binary tree has a root node and every node has at most two children.

A full binary tree

An ancestry chart which can be mapped to a perfect 4-level binary tree.
A full binary tree (sometimes referred to as a proper or plane or strict binary tree) is a tree in which every node has either 0 or 2 children. Another way of defining a full binary tree is a recursive definition. A full binary tree is either:
A single vertex.
A tree whose root node has two subtrees, both of which are full binary trees.
A perfect binary tree is a binary tree in which all interior nodes have two children and all leaves have the same depth or same level. An example of a perfect binary tree is the (non-incestuous) ancestry chart of a person to a given depth, as each person has exactly two biological parents (one mother and one father). Provided the ancestry chart always displays the mother and the father on the same side for a given node, their sex can be seen as an analogy of left and right children, children being understood here as an algorithmic term.
A complete binary tree is a binary tree in which every level, except possibly the last, is completely filled, and all nodes in the last level are as far left as possible. It can have between 1 and 2h nodes at the last level h. A perfect tree is therefore always complete but a complete tree is not necessarily perfect. An alternative definition is a perfect tree whose rightmost leaves (perhaps all) have been removed. Some authors use the term complete to refer instead to a perfect binary tree as defined above, in which case they call this type of tree (with a possibly not filled last level) an almost complete binary tree or nearly complete binary tree. A complete binary tree can be efficiently represented using an array.

A complete binary tree (that is not full)
In the infinite complete binary tree, every node has two children (and so the set of levels is countably infinite). The set of all nodes is countably infinite, but the set of all infinite paths from the root is uncountable, having the cardinality of the continuum. That's because these paths correspond by an order-preserving bijection to the points of the Cantor set, or (using the example of a Stern–Brocot tree) to the set of positive irrational numbers.
A balanced binary tree is a binary tree structure in which the left and right subtrees of every node differ in height by no more than 1. One may also consider binary trees where no leaf is much farther away from the root than any other leaf. (Different balancing schemes allow different definitions of "much farther".)
A degenerate (or pathological) tree is where each parent node has only one associated child node. This means that the tree will behave like a linked list data structure.
