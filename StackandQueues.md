# Stack and Queues
Stacks and queues are two fundamental data structures used in computer science and programming to organize and manage data.

## Stacks:
```
A stack is a linear data structure that follows the Last-In-First-Out (LIFO) principle. It can be visualized as a stack of plates where the last plate added is the first one to be removed. The two primary operations performed on a stack are:

Push: It adds an element to the top of the stack. The new element becomes the most recently added and is placed above all the existing elements.
Pop: It removes the top element from the stack. The element that was added last is the first one to be removed.
In addition to the push and pop operations, stacks often include a third operation:

Peek (or Top): It retrieves the top element from the stack without removing it. It allows you to access the element at the top of the stack without modifying the stack's contents.
Stacks can be implemented using arrays or linked lists. The size of a stack can be fixed or dynamic, depending on the implementation.

Common real-world examples of stacks include the call stack used in programming to manage function calls, undo/redo functionality in text editors, and the back button in web browsers.
```

## Queues:
```
A queue is also a linear data structure, but it follows the First-In-First-Out (FIFO) principle. It can be visualized as a queue of people waiting in line, where the first person who joins the queue is the first one to be served. The primary operations performed on a queue are:

Enqueue: It adds an element to the end (rear) of the queue.
Dequeue: It removes the element from the front (head) of the queue. The element that has been in the queue for the longest time is the first one to be removed.
Similarly to stacks, queues may include a third operation:

Peek (or Front): It retrieves the element at the front of the queue without removing it.
Queues can also be implemented using arrays or linked lists. Like stacks, the size of a queue can be fixed or dynamic.

Common real-world examples of queues include waiting in line at a ticket counter, print spooler in an operating system, and message queues in computer networks.
```
Both stacks and queues have their specific use cases. Stacks are typically used in scenarios where the last-in-first-out order is required, such as managing function calls, while queues are useful when a first-in-first-out order is needed, like handling tasks in a synchronized manner.






