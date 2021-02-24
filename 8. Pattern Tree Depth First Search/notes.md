## What is this pattern
- Depth First Search (DFS) technique is used to traverse a tree.
- You can use recursion (or a stack for the iterative approach) to keep track of all the previous (parent) nodes while traversing.

## The Tree DFS pattern works by starting at the root of the tree, if the node is not a leaf you need to do three things:

- Decide whether to process the current node now (pre-order), or between processing two children (in-order) or after processing both children (post-order).
- Make two recursive calls for both the children of the current node to process them.

## How to identify the Tree DFS pattern:

- If you’re asked to traverse a tree with in-order, preorder, or postorder DFS
- If the problem requires searching for something where the node is closer to a leaf

## Problems featuring Tree DFS pattern:
- Sum of Path Numbers (medium)
- All Paths for a Sum (medium)

