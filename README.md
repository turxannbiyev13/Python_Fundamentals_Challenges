# Python Fundamentals: Control Structures & Functions

This repository contains optimal and **"Pythonic"** solutions for core Python challenges covering functions, conditional statements (`if-elif-else`), and loops (`while`, `for`). 

The main objective of these tasks is to write clean, readable, and efficient code following professional development standards (e.g., adhering to Single Exit Point principles where applicable).

---

## 🚀 Key Implementation Highlights

* **Single Exit Point Principle:** Avoided multiple `return` statements inside functions by assigning values to a single variable and returning it at the very end of the function block. This improves code readability and debugging efficiency.
* **Infinite Loop Prevention:** Structured `while` loops carefully with proper counter updates to ensure safe execution.
* **Direct Mathematical Evaluation:** Optimized traditional sequential logic problems (like custom FizzBuzz variants) to evaluate specific inputs efficiently without unnecessary overhead.

---

## 📋 Challenge Breakdown & Functions

### 1. Even or Odd Validator (`check_even_odd`)
* **Objective:** Takes an integer and determines if it's even or odd.
* **Pythonic Approach:** Utilizes a single tracking variable (`status`) to return the result at the end of the block.

### 2. Cumulative Summation with While Loop (`sum_upto_n`)
* **Objective:** Computes the total sum from 1 up to $n$ (inclusive) using a `while` loop. 
* **Edge Case Handling:** Returns `0` immediately if the input $n$ is negative or zero, protecting the loop from executing unexpectedly.

### 3. Targeted FizzBuzz Evaluation (`fizz_buzz`)
* **Objective:** Evaluates divisibility by 3, 5, or both for a specific target integer $n$.
* **Pythonic Approach:** Returns a single consolidated string string directly mapping the final evaluated result without printing interim iterations unnecessarily.

### 4. Collection Filtering (`get_even_numbers`)
* **Objective:** Iterates through a given list of numbers using a `for` loop to filter out and return only even integers into a clean, new collection.

### 5. String Reversal Utility (`reverse_string`)
* **Objective:** Demonstrates the use of Python's fast and highly efficient slicing mechanics (`[::-1]`) to reverse text input smoothly.

---

## 🛠️ How to Run
You can preview and run the interactive notebook directly in Google Colab by clicking the **Open in Colab** badge located at the top of the repository file!
