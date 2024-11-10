# Stack and Queue Implementations in Python
This repository contains my implementations of Stack and Queue in Python, leveraging the collections.deque class for efficient and straightforward data structure handling.
## Overview
### Stack Implementation
The Stack follows a Last In, First Out (LIFO) approach. In this project, I implemented common operations like:

  - Push: Adds an element to the top of the stack.
  - Pop: Removes the last added element.
  - Peek: Allows viewing elements from the end of the stack.

### Applications:

1. String Reversal: Using a stack to reverse strings.
2. Balanced Parentheses Checker: Validates if parentheses {}, (), and [] are balanced within a string.

### Queue Implementation
The Queue follows a First In, First Out (FIFO) structure, ideal for sequential order processing. Key functionalities include:
 - Enqueue: Adds an element to the start of the queue.
 - Dequeue: Removes an element from the end.
### Applications:

1. Food Order Management System: A multithreaded system simulating a real-time ordering and serving process.
2. Binary Number Generator: Generates binary numbers from 1 to 10 using queue operations.

## Python Class Options for Stack and Queue
In Python, we have multiple ways to implement Stack and Queue structures:
 - list: Basic list-based implementation, but not ideal for complex queue operations due to efficiency.
 - collections.deque: A double-ended queue optimized for both Stack and Queue operations.
 - queue.LifoQueue: Specifically designed for LIFO operations in multi-threaded environments.
