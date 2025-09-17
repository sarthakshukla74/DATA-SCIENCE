# NumPy Functions Tutorial

This repository contains a **Google Colab notebook** demonstrating essential **NumPy functions** with practical examples.  
It is aimed at beginners learning **Python for Data Science / Machine Learning**.

---

## 📘 Topics Covered in the Notebook

### 🔹 Array Creation
- `np.array()` – Create arrays from lists
- `np.arange()` – Create arrays with a range of values
- `.reshape()` – Reshape arrays into multi-dimensional forms
- `np.zeros()`, `np.ones()` – Create arrays filled with zeros or ones
- `np.identity()` – Identity matrix

### 🔹 Array Attributes
- `.size` – Total number of elements  
- `.shape` – Dimensions (rows × columns)  
- `.ndim` – Number of dimensions  
- `.dtype` – Data type of elements  
- `.itemsize` – Memory size of one element  

### 🔹 NumPy Operations
- **Scalar Operations** – Addition, subtraction, multiplication, power, etc.  
- **Relational Operations** – Comparisons (`>`, `<`, `==`)  
- **Vectorized Operations** – Element-wise operations on arrays  
- Mathematical functions:
  - `np.max()`, `np.log()`, `np.exp()`, `np.floor()`, `np.sin()`

### 🔹 Indexing and Slicing
- 1D and 2D slicing
- Steps in slicing (`[start:end:step]`)
- Accessing specific elements
- Sub-matrices

### 🔹 Fancy Indexing
- Selecting specific rows/columns using lists
- Boolean indexing (`y[y > 4]`, `(y % 2 == 0) & (y > 4)`)

### 🔹 Aggregate Functions
- `np.max(axis=1)` – Row-wise maximums
- `np.mean(axis=0)` – Column-wise averages

### 🔹 Applied Examples
- **Mean Squared Error (MSE)** function using NumPy  
- **Student Average Scores** – Generate random marks and compute averages

---

## 🚀 Getting Started

### Open in Google Colab
Click below to run the notebook in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dA_D0yCetWshLNUvQ5ihXxz4Xv3mXDCu)

---

## 🛠️ Requirements
- Python 3.x  
- NumPy  

Install NumPy (if not available):
```bash
pip install numpy
