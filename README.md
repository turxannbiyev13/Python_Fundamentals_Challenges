# Python Fundamentals: Core Structures & Libraries

This repository serves as a comprehensive showcase of foundational Python programming and core data manipulation libraries. It includes clean, optimized, and structurally sound solutions for challenges covering basic control mechanisms and mathematical array computing.

---

## 📂 Repository Structure

* **`Practice_Control_Structures.ipynb`**: Focused on functions, conditional statements (`if-elif-else`), and loop optimizations (`while`, `for`).
* **`Practice_NumPy.ipynb`**: Focused on vectorization, multi-dimensional array operations, and matrix slicing techniques using the NumPy library.

---

## 🚀 Key Implementation Highlights

### 1. Control Structures & Functions
* **Single Exit Point Principle:** Avoided multiple `return` statements inside functions by assigning values to a single variable and returning it at the very end of the block to improve code readability and debugging efficiency.
* **Infinite Loop Prevention:** Structured `while` loops carefully with proper counter updates to ensure safe execution.

### 2. NumPy Array Manipulations
* **Boolean Masking & Filtering:** Efficiently isolated and filtered specific values (e.g., retrieving odd or even elements from an array) using condition-based direct mapping without writing explicit python loops.
* **Vectorized Mathematics:** Utilized built-in NumPy broadcasting mechanics for fast mathematical operations across large data structures.
* **Matrix Reshaping & Slicing:** Demonstrated practical multi-dimensional grid manipulation and indexing methods.

---

## 📋 Core Challenge Breakdown

### Python Basics
1.  **Even or Odd Validator (`check_even_odd`)**: Utilizes a single tracking variable (`status`) to safely return evaluation results.
2.  **Cumulative Summation (`sum_upto_n`)**: Computes total sum from 1 up to $n$ using a `while` loop with edge-case protection against negative inputs.
3.  **Targeted FizzBuzz (`fizz_buzz`)**: Direct mathematical evaluation mapping inputs efficiently without interim iteration overhead.

### NumPy Mechanics
1.  **Array Structuring:** Array generation, multi-dimensional indexing, and data type conversions.
2.  **Element-wise Conditionals:** Fast boolean index tracking across structural boundaries.
3.  **Statistical Aggregations:** Utilizing built-in methods for computing matrix sums, means, and dimensions smoothly.

---

## 🛠️ How to Run
You can preview and run any interactive notebook directly in Google Colab by opening the respective file and clicking the **Open in Colab** badge located at the top!
