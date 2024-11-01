# HashMap Implementation in Python

This directory contains a Python implementation of HashMaps, featuring multiple techniques for efficient collision handling, memory management, and rehashing. The notebook explores fundamental concepts of HashMaps and demonstrates real-world solutions to common collision scenarios.

## Features

### 1. **Hashing Function**
   - Uses a basic summation of Unicode values of characters in the key to generate an index for storing data efficiently.

### 2. **Collision Handling Techniques**
   - **Chaining Method**: Utilizes linked lists to handle collisions by storing multiple items at the same index.
   - **Linear Probing**: Resolves collisions by searching for the next available slot in a sequential manner. Defined as:  
      \[ h'(x) = [h(x) + f(i)] \]  
      where \( f(i) = i \), and \( i = 0, 1, 2, \ldots \)
   - **Quadratic Probing**: Increments the probing sequence quadratically to avoid clustering. Defined as:  
      \[ h'(x) = [h(x) + f(i)] \]  
      where \( f(i) = i^2 \), and \( i = 0, 1, 2, \ldots \)

### 3. **Advanced Techniques**
   - **Double Hashing**: Reduces clustering further by applying a second hash function. The probing formula is:  
      \[ h'(x) = [h(x) + i \times h_2(x)] \]  
      where \( h_2(x) = 1 + (h(x) \% (m - 1)) \)
   - **Rehashing**: Dynamically doubles the table size and redistributes entries when the table becomes full, ensuring efficient memory use.

## Usage

- Import the `HashMap` class into your project to utilize its powerful data storage and retrieval capabilities.
- Experiment with different collision handling techniques to best suit your data's distribution.

## Requirements

- Python 3.x
- Recommended: Jupyter Notebook or Google Colab for interactive exploration.

---

This project demonstrates HashMap fundamentals and is a part of a broader Data Structures and Algorithms learning initiative.
