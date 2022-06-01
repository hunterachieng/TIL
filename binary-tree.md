# TREE DATASTRUCTURES
These comprise of nodes, edges, branches, and leaves

Trees are non-linear data structures which are arranged heirachicaly such as a family tree or a company organizational structure.

The top most element of a tree is the root/ parent.

The data is stored inside nodes which are connected with edges.

The bottom most part of a tree contains the leaves which are nodes without children.

#### Height of a tree

The height of a tree is calculated by the length of the longest path to a leaf.

#### Depth of a tree

Depth is calculated by finding the path to the root of the tree.




# Binary Tree
A binary tree is a tree dta stucture where a parent node can have at most 2 children.

Each node consits of three items:
```
Data item
Address of left child
Address of right child
```

## Types of Binary Tree

### Full Binary Tree

Each parent/internal node has either 2 child nodes or none at all

### Perfect Binary Tree

All child nodes have exactly two children and the leaf nodes are at the same level

### Complete Binary Tree

A complete binay tree is similar to a perfect binary tree but with several differences:

```
Leaf nodes lean towards the left
The last leaf node can be by itself and does not need its right sibling
Every level must be filled

```
### Degenerate/ pathological tree

This is a binary tree that has only one child element, either the left or right.

### Skewed binary tree

It is a degenerate tree which is dominated by either the left or right nodes.

Includes:
```
Left-skewed binary tree
Right-skewed binary tree

```
### Balanced Binary Tree

This is a binary tree in which the difference between the height of the left and the right subtree node is either 0 or 1.

