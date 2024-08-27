# 🧠 Eigenvalue Computation with QR Algorithms

## Overview 📚

This project explores the computation of eigenvalues using various QR algorithms, including the **Gram-Schmidt process**, **Householder transformations**, and **Givens rotations**. These methods are foundational in numerical linear algebra and are used extensively in solving eigenvalue problems, which are critical in many fields including physics, engineering, computer science, and finance.

## Background 🎓

The QR algorithm is a fundamental technique for computing the eigenvalues of a matrix. By decomposing a matrix \(A\) into an orthogonal matrix \(Q\) and an upper triangular matrix \(R\), and iteratively applying this decomposition, one can approximate the eigenvalues of \(A\).

This project provides implementations of three different methods to perform the QR decomposition:

1. **Gram-Schmidt Process**: A classical method that orthogonalizes a set of vectors.
2. **Householder Transformations**: A method that uses reflections to zero out the subdiagonal elements of a matrix.
3. **Givens Rotations**: A method that applies rotations to zero out specific elements of a matrix, suitable for sparse matrices.

## Algorithms Implemented ⚙️

### Gram-Schmidt QR Algorithm

The Gram-Schmidt process is used to orthogonalize the columns of a matrix, resulting in the matrix \(Q\). The upper triangular matrix \(R\) is then obtained by projecting the original matrix \(A\) onto the orthogonal basis formed by \(Q\).

### Householder QR Algorithm

Householder transformations are used to zero out subdiagonal elements of a matrix. This is achieved by reflecting the vectors about a hyperplane, ensuring numerical stability and reducing rounding errors.

### Givens QR Algorithm

Givens rotations are used to introduce zeros in a matrix one element at a time. This method is particularly useful for sparse matrices, where only a few rotations are needed to achieve a QR decomposition.

### Examples and tests 💡
The project includes several example scripts demonstrating how to use each of the QR algorithms. These examples cover matrices of different sizes and structures, showcasing the strengths and limitations of each method.

### Contributing 🤝
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas or report any bugs.
Feel free to contact me on my social accounts. You can find them in my bio
