# 📅 Day 1: Python Basics & Linear Algebra  
**Date**: [11 Feb 2025]  

👋 Welcome to Day 1 of my **AI Learning Journey**! Today, I refreshed my Python fundamentals and explored core linear algebra concepts. Below are the details, code examples, and resources for learners to follow along.  

---

## 🐍 Python Refresher  
### **Topics Covered**  
- Understanding Python syntax and working with variables.
- Exploring basic data types: strings, numbers, lists, and dictionaries.
- Using comments, type casting, and performing basic operations.

**Quick Notes & Examples:**
**Example 1**
# Variables and Data Types
name = "Deep"
age = 24
is_learning = True

print(f"My name is {name}, I am {age} years old.")  
# Output: My name is Deep, I am 24 years old.

**Example 2**
# Type Casting
num_str = "10"
num_int = int(num_str)  # Converting string to integer
print(num_int + 5)  # Output: 15

**Example 3**
# Lists and Dictionaries
fruits = ["Apple", "Banana", "Cherry"]
person = {"name": "Deep", "age": 24}

print(fruits[0])  # Output: Apple
print(person["name"])  # Output: Deep

---

## 📐 Linear Algebra  
### **Topics Covered**  
- Vectors and their transformations.
- Matrix operations and how they modify data.
- Linear independence and the concept of span.

**Quick Notes & Examples:**
**Example 1 - Vectors & Scalars:**
python
import numpy as np  
vector = np.array([3, 4])  # 2D vector  
scalar = 2  
scaled_vector = scalar * vector  # [6, 8]  

**Example 2 - Linear Combinations:**
python

v1 = np.array([1, 0])  
v2 = np.array([0, 1])  
combo = 2*v1 + 3*v2  # Result: [2, 3]  

**Example 3 - Matrix Magic:**
python

# Rotate a vector 90 degrees  
matrix = np.array([[0, -1], [1, 0]])  
vector = np.array([1, 0])  
transformed = matrix @ vector  # [0, 1]  
print("Rotated vector:", transformed)  

---
### **Key Insight**  
- **Matrices** are linear transformations! For example, multiplying a vector by a rotation matrix rotates it in 2D space.  

---

## 🧠 Reflection  
### **What I Learned**  
- Python’s simplicity makes it perfect for rapid prototyping.  
- Matrices are not just grids of numbers—they *transform space*.  

---

⭐ **Explore the Resources**:  
- [Python Basics](python-basics/resources.md)  
- [Linear Algebra](linear-algebra/notes.md)  
