# Sparse Matrix Operations

## Overview

This project implements sparse matrix operations (addition, subtraction, and multiplication) as part of a Data Structures and Algorithms assignment. The matrices are stored efficiently in memory by only keeping track of non-zero elements, which is useful when dealing with large matrices where most elements are zero.

The project is implemented in Python, and custom functions have been written to handle reading from files, performing matrix operations, and saving the results back to files. Standard libraries are **not used** for handling matrices or advanced data structures.

## Features

- **Sparse Matrix Representation**: Only stores non-zero elements to optimize memory usage.
- **Matrix Operations**: Supports addition, subtraction, and multiplication of sparse matrices.
- **Error Handling**: Detects and handles input file format errors, mismatched matrix dimensions, and other edge cases.

## Project Structure

The project is organized as follows:

```bash
/dsa/
  └── sparse_matrix/
      ├── code/
      │   └── src/
      │       ├── sparse_matrix.py  # Contains the SparseMatrix class and matrix operations
      │       └── main.py           # The main program to handle user input and run operations
      └── sample_inputs/
          ├── matrix1.txt           # Sample input matrix 1
          ├── matrix2.txt           # Sample input matrix 2
          └── result.txt            # Output file for the result matrix

## Features
- **Optimized Memory Usage**: Only non-zero elements of the matrix are stored.
- **Matrix Operations**: Supports addition, subtraction, and multiplication of sparse matrices.
- **Input Validation**: Detects invalid file formats and throws appropriate exceptions.

## Prerequisites
- **Python 3.x** must be installed on your system.
- No external Python libraries are used, as per the assignment’s requirements.

## How to Run the Code

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/sparse_matrix.git
   cd sparse_matrix/code/src
