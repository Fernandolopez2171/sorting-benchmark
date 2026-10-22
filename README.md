# Sorting-Benchmark

**English** | [Español](README.es.md)

## Overview

Sorting-Benchmark is a C# console application for analyzing and comparing the performance of different sorting algorithms. The project targets .NET 8 and uses a modular structure to organize the sorting implementations.

## Features

- **Random data generation**: Generates arrays of unique integers for testing the algorithms.
- **Performance analysis**: Measures the execution time of each sorting algorithm for different array sizes.
- **Multiple sorting algorithms**:
  - Bubble Sort
  - Heap Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
  - Selection Sort

## Prerequisites

- .NET 8 SDK installed on your machine.
- A development environment such as Visual Studio 2022.

## Project structure

The project is organized as follows:

### Main files

- **`Program.cs`**: Contains the main program logic, including data generation and algorithm analysis.
- **`Bubble_Sort.cs`**: Implementation of the Bubble Sort algorithm.
- **`Heap_Sort.cs`**: Implementation of the Heap Sort algorithm.
- **`Insertion_Sort.cs`**: Implementation of the Insertion Sort algorithm.
- **`Merge_Sort.cs`**: Implementation of the Merge Sort algorithm.
- **`Quick_Sort.cs`**: Implementation of the Quick Sort algorithm.
- **`Selection_Sort.cs`**: Implementation of the Selection Sort algorithm.

## Running the project

1. Clone this repository to your machine.
2. Open `Sorting-Benchmark.sln` in Visual Studio 2022.
3. Make sure the project is configured to run with .NET 8.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
