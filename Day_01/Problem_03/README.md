# 🔍 Python Input Type Checker

This simple Python script helps you understand the **data type returned by the `input()` function** in Python.

## 🧠 Purpose

When taking user input in Python using the `input()` function, it's important to know that it always returns a value of type **`str` (string)** — even if you type a number.

This script lets you:
- Enter a value using `input()`
- Automatically check and print its data type

## 📜 Code

```python
# Check the type of variable assigned using input () function

a = input("Enter the value of a: ")
print(type(a))
