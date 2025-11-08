# 🐍 Python Notes - Week 06

## 📘 Topic: Functions, Dictionary, Range & For Loop in Python

---

### 🔹 Functions

A **function** is a block of code that runs only when it is called. Functions can accept data known as **parameters** and can return data as a result.

#### 🔹 Creating Functions

A function in Python is defined using the `def` keyword.

**Syntax:**

```python
def Function_Name(p1, p2, p3, ...):
    statements
```

#### 🔹 Function Call

Call a function using its name followed by parentheses.

**Syntax:**

```python
Function_Name(a1, a2, a3, ...)
```

* `p` = parameters (variables) in function definition
* `a` = arguments (values) passed to function

Arguments are information passed into functions. You can pass multiple arguments separated by commas.

#### 🔹 Parameters vs Arguments

* **Parameter:** Variable listed in function definition.
* **Argument:** Value sent to function during call.

#### 🔹 Number of Arguments

By default, a function must be called with the correct number of arguments.

#### 🔹 Keyword Arguments

Arguments can be passed using `key=value` syntax, so order does not matter.

#### 🔹 Return Values

Use `return` statement to return a value from a function.

**Example: Average of Three Numbers**

```python
def avg(n1, n2, n3):
    sum = n1 + n2 + n3
    average = sum / 3
    return average

result = avg(10, 20, 30)
print(result)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Functions.ipynb)

#### 🔹 Calculator Using Functions

Define five functions: addition, subtraction, multiplication, division, and average. Show menu for user choice.

```python
# Define the arithmetic functions
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        return "Error: Cannot divide by zero!"
    return a / b

def average(a, b):
    return (a + b) / 2

# Main program loop
while True:
    print("\n===== Calculator Menu =====")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Average")
    print("0. Exit")

    choice = input("\nEnter your choice (0-5): ")

    if choice == '0':
        print("Goodbye!")
        break

    if choice not in ['1','2','3','4','5']:
        print("Invalid choice! Try again.")
        continue

    num1 = int(input("Enter first number: "))
    num2 = int(input("Enter second number: "))

    if choice == '1':
        print("Sum:", add(num1, num2))
    elif choice == '2':
        print("Difference Result:", subtract(num1, num2))
    elif choice == '3':
        print("Multiplication Result:", multiply(num1, num2))
    elif choice == '4':
        print("Division Result:", divide(num1, num2))
    elif choice == '5':
        print("Average Result:", average(num1, num2))
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Assignment.ipynb)

---

### 🔹 Dictionaries

A **dictionary** stores data in **key:value** pairs.

* Ordered, changeable, and no duplicate keys.
* Values can be any data type.
* Access items using keys.

**Example:**

```python
faculty = {
    "name": "Ma'am Farhat",
    "course": "Python",
    "year": "3rd",
    "semester": "2nd"
}
print(faculty.keys())
print(faculty.values())
print(faculty.items())

faculty["name"] = "Ma'am Farhat Naureen"
print(faculty)

faculty["department"] = "Computer Science"
print(faculty)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Dictionary.ipynb)

---

### 🔹 Python Collections

1. **List:** Ordered, changeable, allows duplicates.
2. **Tuple:** Ordered, unchangeable, allows duplicates.
3. **Set:** Unordered, unindexed, no duplicates.
4. **Dictionary:** Ordered**, changeable, no duplicate keys.

---

### 🔹 Range Function

`range()` generates a sequence of numbers.

**Syntax:**

```python
range(start, stop, step)
```

* `start`: optional, default 0
* `stop`: required, not included in output
* `step`: optional, default 1

**Example: Square of first 7 numbers**

```python
for el in range(1,8):
    print(el*el, end=" ")
```

Output: `1 4 9 16 25 36 49`

---

### 🔹 For Loop

Used for iterating over a sequence (list, tuple, dictionary, set, string). Works as an iterator.

**Example: Print odd numbers from a list**

```python
L = [1,2,3,4,5,6,7,8,9,10]
for el in L:
    if el % 2 != 0:
        print(el)
```

**For Loop with Else:**

```python
L = [1,3,5,7,9]
for el in L:
    print(el)
else:
    print("Loop ended here")
```

**Printing in single line with space or comma**

```python
L = [1,2,3,4,5]
for el in L:
    print(el, end=" ") # with space
```

---

### 🔹 Multiplication Table Using Range

```python
n = int(input("Enter a number: "))
for el in range(1,11):
    print(n, "*", el, "=", n*el)
```

📎 [GitHub Link]( https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Range%26ForLoop.ipynb)
