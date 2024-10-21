Matrix Calculator
This project is a Matrix Calculator developed as part of the PROGRAMMING FOR PROBLEM SOLVING course (CSF101) for the Bachelor of Computer Science and Engineering degree at DIT University, Dehradun.

Project Overview
The Matrix Calculator is a user-friendly application designed to perform basic matrix operations including addition, subtraction, multiplication, and transposition. It supports matrices of various dimensions and provides clear outputs for each operation.

Project Objectives
Design and Implement a matrix calculator using the C programming language.
Implement Functions for matrix addition, subtraction, multiplication, and transposition.
Develop a User-Friendly Interface for inputting matrices and selecting desired operations.
Validate User Input and handle invalid matrix dimensions or operations.
Display Clear and Concise Output for each matrix operation.
Features
Matrix Operations: Addition, subtraction, multiplication, and transposition.
User Input: Accepts matrix dimensions and operation selection.
Input Validation: Ensures valid matrix dimensions and operations.
Output Format: Provides clear and concise display of matrix operation results.
Requirements
Programming Language: C
Development Environment: Any C compiler (e.g., GCC, Clang)
Libraries: Standard C libraries
Implementation
Method
Matrix addition involves adding corresponding elements of two matrices of the same dimensions. The resulting matrix has the same dimensions as the input matrices.

Example Code
c
Copy code
void matrixAddition(int mat1[][3], int mat2[][3], int result[][3], int row, int col) {
    for (int i = 0; i < row; i++) {
        for (int j = 0; j < col; j++) {
            result[i][j] = mat1[i][j] + mat2[i][j];
        }
    }
}
Example Usage
Given two matrices:

csharp
Copy code
Matrix 1:
[1 2 3]
[4 5 6]
[7 8 9]

Matrix 2:
[9 8 7]
[6 5 4]
[3 2 1]
Adding these matrices using the matrixAddition function will result in:

csharp
Copy code
Resultant Matrix:
[10 10 10]
[10 10 10]
[10 10 10]
Conclusion
The Matrix Calculator project demonstrates the implementation of basic matrix operations in C. It supports various matrix dimensions and provides clear and organized output for each operation, making it a useful tool for mathematical calculations and educational purposes.

