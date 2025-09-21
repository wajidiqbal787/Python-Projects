# Python Assignment — Question 01

## Overview
This repository contains a Python program that demonstrates **string concatenation** and **f-string formatting** to display a person's details in two different ways.

## Objective
- Print a greeting header.
- Display a person's **name**, **age**, and **role**.
- Use **two methods**:
  1. **String concatenation**
  2. **f-string** with a newline before the role.

---

## Python Code Example

```python
print("\n--------------- Greeting ---------------")
name = "Wajid Iqbal"
age = "3467"
role = "Python Developer"
info = "My Name is " + name + " I am " + age + " years Old and My Role is " + role + "."
infoo = f"My Name is {name} I am {age} years Old \nand My Role is {role}."
print(info)
print(infoo)
