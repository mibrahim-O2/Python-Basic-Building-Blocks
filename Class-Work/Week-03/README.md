# 🐍 Python Notes - Week 03

## 📘 Topic: Type Casting, Input from User, Strings & Control Structures

---

### 🔹 Type Casting

Type casting, or type conversion, refers to converting a variable from one data type to another in Python.  
For example, if you have a variable containing a string number such as `"27"`, you may need to convert it to an integer before performing arithmetic operations. Otherwise, Python will interpret `"27"` as a string and add it to other strings instead of performing arithmetic.

📎 [Type Casting - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/Type_Casting.ipynb)

Python provides two types of type casting:
1. **Explicit Type Casting** – The programmer manually converts one data type into another.  
2. **Implicit Type Casting** – Python automatically converts one data type to another to prevent data loss or errors.

**Explicit Type Casting:**  
Explicit conversion requires you to use built-in Python functions to convert a value from one type to another manually. When you specify explicit type casting, you have full control over the data type you want.  
The explicit type casting is performed as per the requirement and avoids type mismatches in Python.

**Implicit Type Casting:**  
In implicit type casting, Python handles the conversion of data types automatically.  
This process usually occurs when different types need to be used together in an expression.  
Python converts the lower precision type to a higher precision type to avoid data loss.  
This process ensures that operations run smoothly without requiring manual intervention.

---

### 🔹 Input from User

The `input()` function allows user input.

**Syntax:**  
`input(prompt)`  

**prompt:** A string representing a default message before the input.

📎 [Example on Google Colab](https://colab.research.google.com/drive/1AgnWL5QXtiLUtiPv9Uxc89seYhWrZ06t#scrollTo=OPmxzOBg1dQo)

You can write programs that:
- Take two numbers as input and print the average of those numbers.  
- Compare two numbers and return `True` if the first is greater than or equal to the second, otherwise `False`.

---

### 🔹 Strings in Python

📎 [String Functions - GitHub Link](https://github.com/ibraheem-02/Python_Programs/blob/main/String_Functions.ipynb)

Strings in Python are surrounded by either single quotation marks or double quotation marks.  
`'hello'` is the same as `"hello"`.  

Assigning a string to a variable is done with the variable name followed by an equal sign and the string.  
We can also assign a multiline string to a variable by using three quotes.  

A string can contain both single and double quotes by enclosing the text in triple quotes (`'''` or `"""`).  

---

### 🔹 String Functions

Python provides several useful functions and operations for working with strings:

- **Concatenation:** Joining two or more strings together.  
- **Length of String:** Finding the number of characters in a string.  
- **Indexing:** Accessing specific characters in a string using index positions.  
- **Capitalize:** Capitalizing the first letter of a string.  
- **Replace:** Replacing specific characters or words in a string.  
- **Find:** Searching for the first occurrence of a specific character or word and returning its index.  
- **Count:** Counting how many times a specific character appears in a string.  

If a searched letter or word is not found, the `find()` function returns `-1` because it’s not a valid index.

---

### 🔹 Control Structure: Flow of Execution of Program

📎 [Control Structures - GitHub Link](https://github.com/ibraheem-02/Python_Programs/blob/main/Control_Structures.ipynb)

Control structures determine the **flow of execution** of a program.  
They allow developers to control how and when certain parts of code are executed.

There are two main types of flow in Python programs:

---

#### 1. Sequential Flow
Sequential flow (also called linear flow) means that every statement is executed one by one in order.  
This is the default flow of execution in Python.

---

#### 2. Selection Flow
Selection flow is a programming concept where different sections of code are executed based on conditions.  
It allows programs to make decisions, which is fundamental in creating dynamic and interactive applications.

In Python, selection flow is implemented using **if**, **elif**, and **else** statements.

---

### 🔸 Single Alternate
Executes a block of code only if a specific condition is true.

**Syntax:**  
`if (condition):`  
 `statement`

---

### 🔸 Double Alternate
Executes one block if a condition is true and another block if it is false.

**Syntax:**  
`if (condition):`
    `statement`
`else:`
    `statement`

  # 🔸 Multiple Alternate

Used when there are **multiple conditions** to evaluate sequentially.  
Python checks each condition one by one until one is `True`.  
If none of them are true, the `else` block executes.

---

### 🧠 Concept
The `if-elif-else` structure allows you to handle multiple decision branches in your program.  
Only the first condition that evaluates to `True` will execute its corresponding code block — the rest are skipped.

---

### 🧩 Syntax
```python
if (condition):
    statement
elif (condition):
    statement
else:
    statement



