# 🧮 Smart Matrix Solver  
A simple and clean **2x2 Matrix Calculator** made using **Streamlit** and **NumPy**.  
This app allows you to perform basic matrix operations such as **Addition**, **Subtraction**, **Matrix Multiplication**, and **Scalar Multiplication**.

---

## 📌 Features
- Enter values for **Matrix A (2×2)**  
- Enter values for **Matrix B (2×2)**  
- Perform the following operations:  
  - ➕ Matrix Addition  
  - ➖ Matrix Subtraction  
  - ✖️ Matrix Multiplication  
  - 🔢 Scalar Multiplication  
- Clean and easy-to-use UI  
- Works directly in the browser using Streamlit  

---

## 📐 Formula Used

### Matrix A & Matrix B:
\[
A = \begin{bmatrix} a & b \\ c & d \end{bmatrix}, \quad  
B = \begin{bmatrix} e & f \\ g & h \end{bmatrix}
\]

### Matrix Multiplication:
\[
AB = \begin{bmatrix}
(a \cdot e + b \cdot g) & (a \cdot f + b \cdot h) \\
(c \cdot e + d \cdot g) & (c \cdot f + d \cdot h)
\end{bmatrix}
\]

---

## 🚀 How to Run

Make sure Python is installed.

### 1️⃣ Install required libraries:
```bash
pip install streamlit numpy
