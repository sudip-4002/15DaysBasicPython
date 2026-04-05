# Basic Variables in Python

This Python program demonstrates the basics of variables, data types, multiple assignments, type conversion, and constants.

---

## 📝 Program Features

1. **Variable Declaration**
   - Demonstrates different types of variables:
     ```python
     name = "Sudip"       # String
     age = 21             # Integer
     height = 5.7         # Float
     is_student = True    # Boolean
     ```

2. **Displaying Variable Values**
   - Prints values of the variables:
     ```python
     print("Name:", name)
     print("Age:", age)
     print("Height:", height)
     print("Is Student?", is_student)
     ```

3. **Type Checking**
   - Checks the data type of each variable using `type()`:
     ```python
     print("Type of name:", type(name))
     print("Type of age:", type(age))
     print("Type of height:", type(height))
     print("Type of is_student:", type(is_student))
     ```

4. **Multiple Assignment**
   - Assign multiple variables in a single line:
     ```python
     x, y, z = 10, 20, 30
     print("x =", x, "y =", y, "z =", z)
     ```

5. **Type Conversion**
   - Converts a string to an integer:
     ```python
     num_str = "100"
     num_int = int(num_str)
     print("Original string:", num_str, "| Type:", type(num_str))
     print("Converted to int:", num_int, "| Type:", type(num_int))
     ```

6. **Constants**
   - Demonstrates the use of constants (by convention, uppercase):
     ```python
     PI = 3.14159
     GRAVITY = 9.8
     print("PI =", PI)
     print("GRAVITY =", GRAVITY)
     ```

---

## 📌 Key Notes

- **Variable Types:**  
  Python supports `int`, `float`, `str`, `bool` and more.
  
- **Type Checking:**  
  Always check types during debugging or when converting variables.

- **Multiple Assignment:**  
  Useful for initializing several variables in a single line.

- **Type Conversion:**  
  Convert between types using `int()`, `float()`, `str()`, etc.

- **Constants:**  
  Constants are written in **uppercase** by convention and should not be changed during program execution.

---

## ✅ Output Example
