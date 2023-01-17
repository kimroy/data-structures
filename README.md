# Data Structures

## Array

- An array is a container which is used to hold a fixed number of items.
- The array will consist of an **index** and an **element**.
- The **index** is where the position where the **element** exists in the array.
- Time Complexity:
  - Access: `O(1)`
  - Search: `O(n)`
  - Insert: `O(n)`
  - Remove: `O(n)`

## Linked List

- A linked list is a linear sequence of nodes which contain links to following nodes.
- The first element in the linked list is known as the **head** and the last is known as the **tail**.
- **Singly linked list**: Is a linked list with one pointer to the next node where the last node points at `null`.
- **Doubly linked list**: Is a linked list with two pointers one to the next node and one to the previous node. The first node previous is `null` and the last node next is `null`.
- **Circular linked list**: Is a linked list with one pointer to the next node where the last node points to the first node in the linked list.
- Time Complexity:
  - Access: `O(n)`
  - Search: `O(n)`
  - Insert: `O(1)`
  - Remove: `O(1)`

## Stack

- A stack follows the Last In First Out (LIFO) principle.
- It is used to store elements and allows operations such as push (adding an element to the top of the stack) and pop (removing the top element from the stack).
- Time Complexity:
  - Access: `O(n)`
  - Search: `O(n)`
  - Insert: `O(1)`
  - Remove: `O(1)`

## Queue

- A queue follows the First In First Out (FIFO) principle.
- It is used to store elements and allows operations such as enqueue (adding an element to the back of the queue) and dequeue (removing the front element from the queue).
- Time Complexity:
  - Access: `O(n)`
  - Search: `O(n)`
  - Insert: `O(1)`
  - Remove: `O(1)`

## Tree

- A tree is a data structure that consists of nodes which are connected by edges.

## Binary Tree

- A binary tree is a tree data structure where each node has at most two children.
- A binary tree is considered **full** if and only if each node has either 0 or 2 children.
- A binary tree is considered **perfect** if and only if each node have two children and all the leaves have the same depth.

## Binary Search Tree

- A BST is a type of binary tree where it maintains the properties of BT in addition to every value in the left-sub tree must be less than the root value. And every value in the right-sub tree must be greater or equal to the root value.
- Time Complexity:
  - Access: `O(logn)`
  - Search: `O(logn)`
  - Insert: `O(logn)`
  - Remove: `O(logn)`

## Heap

- A heap a special case of a balanced binary tree where the value of the root node is less than, greater than, or equal to either of it's children.
- It can be implemented in a max or min variation which dictates the root nodes less than or greater than condition.
- If **min** heap, then all children nodes are greater than the root node.
- If **max** heap, then all children node are less than the root node.
- Time Complexity:
  - Access Max/Min: `O(1)`
  - Remove Max/Min: `O(logn)`
  - Insert: `O(logn)`

## Graph

- A graph consists of a set of vertices and edges that connect them.
- Graphs are used to represent networks and relationships between objects.
- **Undirected Graph**: Is a graph in which the adjacency relation is symmetric. If there is an edge from node a to node b inversely there is a relation from node b to node a. [a=>b] means [b=>a]
- **Directed Graph**: Is a graph in which the adjacency relation is not symmetric. If the is an edge from node a to node b that does not indicate a relation from node b to node a. [a=>b] does not mean [b=>a]