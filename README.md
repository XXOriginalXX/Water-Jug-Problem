# Water Jug Problem Solver (BFS Implementation)

This project solves the classic **Water Jug Problem** using the **Breadth-First Search (BFS)** algorithm. The problem is to determine if it is possible to measure exactly `z` liters of water using two jugs of capacities `x` and `y` liters, respectively.

## Problem Statement

Given two jugs with capacities `x` and `y` liters, and an infinite water supply, the goal is to measure exactly `z` liters of water. The operations allowed are:
1. Fill Jug 1.
2. Fill Jug 2.
3. Empty Jug 1.
4. Empty Jug 2.
5. Pour water from Jug 1 to Jug 2.
6. Pour water from Jug 2 to Jug 1.

The BFS algorithm ensures that the solution, if it exists, is found with the minimum number of operations.

## Features

- Uses BFS to explore all possible states and operations.
- Ensures the shortest solution path (minimum cost) is found.
- Avoids revisiting previously encountered states to improve efficiency.
- Provides detailed output, including the steps to reach the solution and the number of operations (cost).

## How to Use

### Input:

You can change the jug capacities (`x`, `y`) and the target water amount (`z`) in the code. For example:

```python
x = 4  # Capacity of Jug 1
y = 3  # Capacity of Jug 2
z = 2  # Target amount of water to be measured
