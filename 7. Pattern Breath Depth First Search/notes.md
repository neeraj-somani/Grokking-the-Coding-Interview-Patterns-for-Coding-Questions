## What is this pattern

- Breadth First Search (BFS) technique is used to traverse a tree
- uses a queue to keep track of all the nodes of a level before jumping onto the next level.
- The Tree BFS pattern works by pushing the root node to the queue and then continually iterating until the queue is empty. For each iteration, we remove the node at the head of the queue and “visit” that node. After removing each node from the queue, we also insert all of its children into the queue.

## How to identify the Tree BFS pattern:
- If you’re asked to traverse a tree in a level-by-level fashion (or level order traversal)

## Problems featuring Tree BFS pattern:
- Binary Tree Level Order Traversal (easy)
- Zigzag Traversal (medium)
