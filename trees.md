# Trees
```
a tree is a widely used data structure that represents a hierarchical structure consisting of nodes. It is a collection of connected nodes, where each node has a value and can have zero or more child nodes. The node at the top is called the root, and each node can have an arbitrary number of child nodes connected to it.

The structure of a tree follows a branching pattern, similar to a real-life tree. Each node (except the root) is connected to exactly one parent node
```
## important Terminology in tree:
```
Node - A Tree node is a component which may contain its own values, and references to other nodes
Root - The root is the node at the beginning of the tree
K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
Left - A reference to one child node, in a binary tree
Right - A reference to the other child node, in a binary tree
Edge - The edge in a tree is the link between a parent and child node
Leaf - A leaf is a node that does not have any children
Height - The height of a tree is the number of edges from the root to the furthest leaf
```
**We prioritize going through the depth (height) of the tree first while doing a depth-first traverse. The order in which we search for and print the root can vary depending on the depth first traversal approach used.**

## Here are three methods for depth first traversal:
```
1.Pre-order: root >> left >> right

2.In-order: left >> root >> right

3.Post-order: left >> right >> root
```
**Breadth First
Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.**
## K-ary Trees
```
If a node can have more than two child nodes, the tree that contains them is referred to as a K-ary Tree. K in this form of tree denotes the most number of offspring each Node is permitted to have.
```
## Binary Search Trees
```
A Binary Search Tree (BST) is a particular kind of tree with a building connected to it. All values that are smaller than the root are arranged to the left in a BST, and all values that are larger than the root are arranged to the right.
```