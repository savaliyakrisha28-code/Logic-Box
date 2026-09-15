# 📦 LogicBox (Pattern Generator & Number Analyzer)

**Author:** Krisha Savaliya  
**Course/Project:** Python Practical Assignment  

A Python-based menu-driven console application designed to practice control structures, loops (`for` and `while`), the `range()` function, and conditional statements.

---

## 🎯 Project Objectives

* **🔄 Control Structures & Loops:** Implement `for` and `while` loops for iterative operations.
* **🖥️ Menu-Driven Interface:** Provide an interactive console menu allowing users to choose between generating a pattern, analyzing a range of numbers, or exiting.
* **💡 Logical Problem Solving:** Check whether numbers in a given range are Even or Odd, calculate their sum, and output custom formatted results.

---

## ✨ Features & Functionality

### 1. 🌟 Pattern Generator
* Generates a clean right-angled triangle star pattern based on the number of rows entered by the user.
* Uses string multiplication (`"*" * i`) inside a `for` loop for efficient rendering.

### 2. 🔍 Number Analyzer
* Takes a starting number and ending number from the user.
* Iterates through the given range using `range()` and checks if each number is **Even** or **Odd**.
* Calculates and displays the total sum of all numbers in the specified range.

### 3. 🚪 Exit
* Safely terminates the program loop with a friendly goodbye message.

---

## 📋 Menu Options

```text
Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit
Enter your choice:
'''
Welcome to the Pattern Generator and Number Analyzer!

Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit
Enter your choice: 2

Enter the start of the range: 10
Enter the end of the range: 12

Number 10 is Even
Number 11 is Odd
Number 12 is Even
Sum of all numbers from 10 to 12 is: 33

Select an option:
1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit
Enter your choice: 3
Exiting the program. Goodbye!