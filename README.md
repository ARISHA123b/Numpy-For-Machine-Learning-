# NumPy for Machine Learning & Data Science Practice

Welcome to my portfolio repository featuring practical implementations and exercises using **NumPy**. This repository serves as a documentation of my journey mastering array manipulation, vectorized operations, and linear algebra fundamentals crucial for Machine Learning algorithms.

---

## 🧩 About NumPy (Numerical Python)

**NumPy** is the fundamental package for scientific computing in Python. It is the foundational library that powers almost the entire Python Data Science and Machine Learning ecosystem (including Pandas, Scikit-Learn, TensorFlow, and PyTorch).

### Why NumPy Matters for Machine Learning:
* **The `ndarray`:** Unlike standard Python lists, NumPy's N-dimensional array stores data in contiguous memory blocks, allowing for blazing-fast operations.
* **Vectorization:** It allows us to perform mathematical operations on whole arrays instantly without writing slow Python `for` loops.
* **Linear Algebra Ready:** ML algorithms are pure math underneath. NumPy provides the raw power needed for matrix multiplications, dot products, and vector transformations.

---

## 📂 Repository Structure

* 📂 **`numpy-basics/`** — Core concepts including array creation, multi-dimensional slicing, indexing, and data types.
* 📂 **`numpy-for-ml/`** — Practical applications tailored for machine learning workflows (e.g., matrix multiplications, norm calculations, data normalization).

---

## 🧠 Key Concepts Covered

### 1. Fundamentals of NumPy
* Creating arrays from scratch (`np.zeros`, `np.ones`, `np.arange`, `np.linspace`).
* Understanding array attributes (`shape`, `ndim`, `dtype`).
* Advanced indexing, boolean masking, and conditional filtering.

### 2. Vectorized Math & Linear Algebra
* Avoiding slow Python loops by leveraging **vectorization** and **broadcasting**.
* Matrix operations: Element-wise math, dot products (`np.dot`), and matrix multiplication (`@`).
* Calculating vector magnitudes (norms) using `np.linalg.norm`.
* Computing geometric relationships like angles between high-dimensional vectors using `np.arccos()`.

### 3. Machine Learning Utility Functions
* Feature scaling/normalization techniques (Min-Max Scaling, Standard Score normalization).
* Handling missing or noisy data transformations.

---

## 🚀 How to Run the Notebooks

Since these notebooks were created using **Google Colab**, you can run them directly in the cloud without installing anything on your local machine:

1. Click on any `.ipynb` notebook file inside this repository.
2. If available, click the **"Open in Colab"** badge at the top of the file.
3. Alternatively, download the notebook files and upload them to your own [Google Colab dashboard](https://colab.research.google.com/).

---

## 🛠️ Tech Stack & Requirements
* Python 3.x
* NumPy
* Matplotlib (for visual verifications and plotting)
