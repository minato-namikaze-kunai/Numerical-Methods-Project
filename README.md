# 📦 GUI Numerical Methods Assignments

This repository contains three interactive Streamlit applications built to demonstrate and visualize key topics in Numerical Methods, each as a separate Python script.

---

## ✅ Assignment 1 – Matrix Computations & Visualization

**File:** `GUI_assignment1.py`

An interactive web app to:

* Compute eigenvalues, determinant, condition number, and characteristic polynomial of a matrix
* Perform LU decomposition and power method
* Compute the inverse of a matrix (using Gauss-Jordan elimination)
* Solve linear systems Ax = b and verify solutions
* Compare results against standard numpy methods

Includes default matrix and option to input custom matrices.

---

## ✅ Assignment 2 – Gauss-Legendre Polynomial Visualizer

**File:** `GUI_assignment2.py`

An app to visualize Gauss-Legendre polynomials and their Gaussian quadrature properties:

* Calculate roots and weights using two methods:

  * Jacobi matrix method
  * Companion matrix method
* Visualize roots and weights on plots
* Compare results from both methods side by side
* Display recurrence relations and mathematical derivations

---

## ✅ Assignment 3 – Solving ODEs and BVPs

**File:** `GUI_assignment3.py`

An app to explore multiple numerical and analytical methods for solving ODEs and boundary value problems (BVPs):

* Explicit Euler and Implicit Euler methods (using shooting method)
* Finite difference method to solve BVPs
* Calculation of the Jacobi matrix and eigenvalues (using UL method)
* Analytical solutions with symbolic computation
* Plots and side-by-side comparisons of numerical vs analytical solutions

---

## 🚀 How to run

```bash
pip install streamlit numpy scipy sympy matplotlib pandas
streamlit run GUI_assignment1.py
# or
streamlit run GUI_assignment2.py
# or
streamlit run GUI_assignment3.py
```

---

## ✏️ Author / Notes

Developed as part of Numerical Methods coursework to explore practical implementations, visualization, and comparison of methods.
