# Priority-Queue
Comparison of Binary Heap, Binomial Heap, and Pairing Heap implementations in C++. Includes performance evaluation and analysis.
# Priority Queue Comparison (C++)

This project compares different implementations of priority queues:

- Binary Heap
- Pairing Heap

## Description

The goal of this project is to analyze the performance of different heap structures based on insert and delete-min operations.

## Implementation

The program is written in C++ and includes:

- Binary Heap (array-based)
- Pairing Heap (tree-based)
- Performance testing using `chrono`

## Results

Example output:

Binary Heap Time: 0.0047 seconds  
Pairing Heap Time: 0.1012 seconds  

The Binary Heap performed faster due to better memory efficiency.

## How to Run

1. Compile:
g++ main.cpp -o main

2. Run:
./main
