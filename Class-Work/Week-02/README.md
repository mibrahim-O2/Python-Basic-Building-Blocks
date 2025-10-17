# 🐍 Python Notes - Week 02

## 📘 Topic: Variables, Naming Conventions & Operators

### 🔹 Variable Declaration / Naming
A variable can have a short name (`x`, `y`) or a more descriptive name (`age`, `car_name`, `total_volume`).

#### Rules for Python Variables:
- Must start with a **letter** or an **underscore (`_`)**  
- Cannot start with a **number**  
- Can only contain **alphanumeric characters & underscores** (`A-z`, `0-9`, `_`)  
- **Case-sensitive** (`age`, `Age`, and `AGE` are different variables)  
- Cannot be any of the **Python keywords**

---

### 🧩 Multi-Word Variable Names
When a variable name contains multiple words, these are common naming styles:

| Style | Example | Description |
|--------|----------|-------------|
| **Camel Case** | `myVariableName = "Muhammad Ibrahim"` | Each word except the first starts with a capital letter |
| **Pascal Case** | `MyVariableName = "Muhammad Ibrahim"` | Each word starts with a capital letter |
| **Snake Case** | `my_variable_name = "Muhammad Ibrahim"` | Words are separated by underscores |

---

### 🧠 Two Ways to Store Values in Data
1. **Assignment Operator**  
2. **User Input**

> **Note:** A variable cannot be assigned on the right-hand side because constant values cannot store variables due to memory allocation.

---

## ⚙️ Python Programs

### 🔸 Swapping Two Numbers
[GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-02/Swapping.ipynb)

#### 🔹 Using Third Variable
File: `swapping_with_third_variable.py`

```python
N1 = int(input("Enter first No: "))
N2 = int(input("Enter Second No: "))
print("Values before Swapping:")
print("N1 =", N1, ", N2 =", N2)

temp = N1
N1 = N2
N2 = temp

print("Values after Swapping:")
print("N1 =", N1, ", N2 =", N2)

