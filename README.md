Here’s a **README.md** file that summarizes the content of the two PDFs and provides instructions for running the code:

---

# **Python Programming Lab Manual**

This repository contains code examples and lab tasks based on the **AI_Lab_1_part1.pdf** and **AI_Lab_1_part2.pdf** documents. These documents cover basic Python programming concepts, data structures, and libraries like NumPy, Pandas, and Matplotlib.

---

## **Contents**

### **1. Basic Python Concepts (AI_Lab_1_part1.pdf)**
- **Variables**: Declaration, naming conventions, and scope.
- **Operators**: Arithmetic, assignment, comparison, logical, identity, membership, and bitwise operators.
- **Conditional Statements**: `if`, `elif`, `else`, and nested conditions.
- **Loops**: `for` and `while` loops, including `break`, `continue`, and `else`.
- **Functions**: Defining functions, passing arguments, return values, and recursion.
- **Lab Tasks**:
  - Sum of odd and even numbers.
  - Smallest number in a list.
  - Sum of numbers divisible by 3 and not by 5.
  - Second highest number in a list.
  - Factorial of a number.
  - Fibonacci series.

---

### **2. Python Data Structures and Libraries (AI_Lab_1_part2.pdf)**
- **Lists**: Creation, indexing, methods (append, insert, remove, sort, etc.), and operations.
- **Tuples**: Creation, indexing, immutability, and methods (count, index).
- **Dictionaries**: Key-value pairs, accessing elements, adding/removing items, and nested dictionaries.
- **NumPy**: Array creation, accessing elements, iterating, joining, sorting, and random number generation.
- **Pandas**: Series and DataFrame creation for data manipulation.
- **Matplotlib**: Basic plotting, line graphs, scatter plots, bar graphs, histograms, and pie charts.
- **Lab Tasks**:
  - Reverse a tuple.
  - Swap two tuples.
  - Get the 4th element from the beginning and end of a tuple.
  - Count even and odd numbers in a list.

---

## **How to Use This Repository**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/python-lab-manual.git
   cd python-lab-manual
   ```

2. **Install Required Libraries**:
   Ensure you have Python installed. Then, install the required libraries:
   ```bash
   pip install numpy pandas matplotlib
   ```

3. **Run the Code**:
   - Each code snippet is provided in the repository. You can copy and paste them into a Python file (e.g., `script.py`) and run them using:
     ```bash
     python script.py
     ```
   - Alternatively, you can use a Jupyter Notebook or an IDE like PyCharm or VS Code.

4. **Lab Tasks**:
   - The lab tasks are provided as questions in the PDFs. Solutions are included in the repository. You can modify and experiment with the code to understand the concepts better.

---

## **Code Examples**

### **Basic Python Concepts**
```python
# Example: Sum of odd and even numbers
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
even_sum = sum(num for num in numbers if num % 2 == 0)
odd_sum = sum(num for num in numbers if num % 2 != 0)
print("Sum of even numbers:", even_sum)
print("Sum of odd numbers:", odd_sum)
```

### **Data Structures and Libraries**
```python
# Example: Reverse a tuple
my_tuple = (1, 2, 3, 4, 5)
reversed_tuple = my_tuple[::-1]
print("Reversed tuple:", reversed_tuple)
