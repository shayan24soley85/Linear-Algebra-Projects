# Linear Algebra Assignments & Practical Implementations

## Overview

This repository contains two independent practical assignments completed for the Linear Algebra course. The work bridges theoretical concepts in linear algebra with Python-based computational applications, including facial recognition, PageRank analysis, and image compression using Singular Value Decomposition (SVD).

## Repository Structure

```
├── Assignment_1_Eigen_Everything/
│   ├── notebooks/          # Eigenvalues, Eigenvectors, Face Recognition, and PageRank
│   └── ...
├── Assignment_2_SVD/
│   ├── notebooks/          # Singular Value Decomposition (SVD) and Image Compression
│   ├── input_image.jpg     # Target image for SVD compression
│   └── ...
└── README.md
```

## Assignment Details

### 1. Assignment 1: Eigen-Everything (Face Recognition & PageRank)
* **Topics Covered:** Eigenvalues, eigenvectors, spectral properties, and matrix factorizations.
* **Key Implementations:**
  * **Eigenfaces & Facial Recognition:** Applied eigenvalue decomposition and principal components to facial image datasets for dimensionality reduction and recognition.
  * **PageRank Algorithm:** Implemented the iterative PageRank link analysis model using transition matrices and eigenvalue/eigenvector formulations to rank web pages.

### 2. Assignment 2: SVD & Image Compression
* **Topics Covered:** Singular Value Decomposition (SVD) and matrix approximation.
* **Key Implementations:**
  * **Low-Rank Image Approximation:** Loaded an input image (`input_image.jpg`), converted it into a numerical matrix, and applied SVD to reconstruct the image using a truncated number of singular values, demonstrating data compression and quality tradeoffs.

## Technologies & Tools

* **Programming Language:** Python 3.x
* **Libraries:** NumPy, SciPy, Matplotlib, OpenCV/PIL (depending on image handling)
* **Environment:** Jupyter Notebook

## AI Assistance Disclosure

In accordance with academic transparency, parts of the code structuring, optimization, and documentation within these assignments were developed and refined with the assistance of artificial intelligence (AI) tools.
