
# Sorting-Algorithms

A C++ console application demonstrating three common sorting algorithms.

## Algorithms Included

1. Bubble Sort
2. Selection Sort
3. Insertion Sort

## Features

- Accepts an array of integers from the user
- Allows the user to choose a sorting algorithm
- Displays the sorted array
- Uses separate functions for each algorithm

## Technologies Used

- C++
- Standard Template Library (vector)

## Time Complexity

| Algorithm | Best Case | Average Case | Worst Case |
|---|---|---|---|
| Bubble Sort | O(n)* | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |

*The Bubble Sort implementation here does not use an early-stop optimization, so its best-case time is O(n²).

## How to Run

Compile:

    g++ main.cpp -o sorting

Run on Windows:

    sorting.exe

Run on Linux or macOS:

    ./sorting

## Learning Outcomes

This project demonstrates arrays, vectors, functions, loops,
conditional statements, swapping, and sorting techniques.
