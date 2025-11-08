# Python_Programs

This repository contains a collection of Python programs and Jupyter notebooks that I have implemented while learning programming fundamentals and problem-solving.  
Each topic is explained briefly, and the corresponding notebook can be opened directly in **Google Colab** or previewed on **GitHub**.
# 🐍 Week-01 Summary

## 🖥️ Computer & Programming  
- **Computer:** Electronic device that processes and stores data.  
- **Program:** Set of instructions for a computer to perform tasks.  
- **Computer Programming:** Process of writing instructions (programs) for computers.  

## 💬 Languages & Translators  
- **Language:** System of communication using grammar and vocabulary.  
- **Translator:** Converts programming instructions into binary/machine code.  
- **High‑Level Language:** Human‑readable (e.g., Python, Java).  
- **Assembly Language:** Translates between high‑level and machine language.  
- **Compiler‑Based Language:** Converts code to machine code before execution (e.g., C, C++).  
- **Interpreter‑Based Language:** Executes code line by line (e.g., Python, JavaScript).  

## ⚙️ Compiler & Interpreter  
- **Compiler:** Converts full source code into machine code.  
- **Interpreter:** Executes code one instruction at a time without compiling.  

## ⏱️ Compile Time vs Run Time  
- **Compile Time:** Code translation and error checking before execution.  
- **Run Time:** Execution phase where instructions are carried out and runtime errors occur.  
- **Key Difference:** Compile time detects syntax/semantic errors; runtime handles execution and dynamic errors.  

## ⚠️ Errors  
- **Syntax Error:** Code structure mistakes (e.g., missing parentheses).  
- **Compile Time Error:** Found during compilation (e.g., undeclared variables).  
- **Run Time Error:** Occurs while running (e.g., division by zero).  

## 🔤 Case Sensitivity & Syntax  
- **Case‑Sensitive:** Languages that distinguish between uppercase and lowercase (e.g., Python, Java).  
- **Syntax:** Rules that define valid code structure.  
  - Example: `print("Hello, World!")` in Python.  

## 🧱 Character Set, Reserved Words & Keywords  
- **Character Set:** Collection of symbols a computer can process.  
- **Reserved Words:** Reserved by the language; not usable as identifiers.  
- **Keywords:** Words with special meaning in the language (e.g., `def`, `if`, `return`).  
- **Special Words:** Context‑specific terms (e.g., `self` in Python).  

## 💾 Memory  
- **Memory:** Space where data is stored during program execution.  
- **Key Points:**  
  - Stores variables and temporary data.  
  - Each data piece has a unique address.  
  - Managed logically by the OS to prevent leaks.  

## 🔢 Data Types  
- **int:** Whole numbers (e.g., 1, ‑5).  
- **float:** Decimal numbers (e.g., 3.14).  
- **str:** Text values (e.g., "Hello").  
- **bool:** Logical values (True/False).  

## 🧮 Variables  
- **Variables:** Named memory locations to store data that can change during program execution.  

---

### 📂 Additional Resources  
Access the Week 01 class work repository here:  
[Week 01 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-01)  

---

# 🐍 Week-02 Summary

## 📘 Topic: Variables, Naming Conventions & Operators

### 🔹 Variable Declaration / Naming
- Variables can be short (`x`, `y`) or descriptive (`age`, `car_name`, `total_volume`).  
- **Rules for Python Variables:**  
  - Must start with a **letter** or **underscore (`_`)**  
  - Cannot start with a **number**  
  - Can only contain **alphanumeric characters & underscores** (`A-z`, `0-9`, `_`)  
  - **Case-sensitive** (`age`, `Age`, `AGE` are different)  
  - Cannot be any **Python keyword**

---

### 🧩 Multi-Word Variable Names
| Style | Example | Description |
|-------|---------|-------------|
| **Camel Case** | `myVariableName = "Muhammad Ibrahim"` | Each word except the first starts with a capital letter |
| **Pascal Case** | `MyVariableName = "Muhammad Ibrahim"` | Each word starts with a capital letter |
| **Snake Case** | `my_variable_name = "Muhammad Ibrahim"` | Words separated by underscores |

---

### 🧠 Two Ways to Store Values
1. **Assignment Operator**  
2. **User Input**  

> **Note:** A variable cannot be assigned on the right-hand side as constants cannot store variables due to memory allocation.

---

## ⚙️ Python Programs

### 🔸 Swapping Two Numbers
[Swapping Two Numbers - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-02/Swapping.ipynb)

### 🔹 Operators
[Operators - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-02/Operators.ipynb)

---

### 📂 Full Week 02 Repository
Access all Week 02 class work here:  
[Week 02 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-02)

---
# 🐍 Week-03 Summary

## 📘 Topic: Type Casting, User Input, Strings & Control Structures

### 🔹 Type Casting
- **Converts a variable from one type to another**.  
- **Explicit:** Programmer manually converts using functions.  
- **Implicit:** Python automatically converts to avoid data loss.  
[Type Casting - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/Type_Casting.ipynb)

### 🔹 User Input
- Use `input(prompt)` to get data from the user.  
- Programs can take input and perform operations like average, comparison, etc.  
[User Input - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/User_Input.ipynb)

### 🔹 Strings
- Strings are enclosed in `' '` or `" "`; multiline strings use triple quotes.  
- Functions: concatenation, length, indexing, capitalize, replace, find, count.  
[String Functions - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/String_Functions.ipynb)

### 🔹 Control Structures
- **Flow of execution:** Sequential (default), Selection (conditional).  
- **Selection Flow:** `if`, `elif`, `else` for single, double, or multiple conditions.  
- Only the first `True` condition executes its block.  
[Control Structures - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/Control_Structures.ipynb)

---

### 📂 Full Week 03 Repository
[Week 03 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-03)
---
# 🐍 Week-04 Summary

## 📘 Topic: Multiple Alternate, Nested If & Lists

### 🔹 Multiple Alternate
- Use **if–elif–else** to evaluate multiple conditions sequentially.  
- Only the first `True` block executes.  
[Control Structures - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-04/Control_Structures%20(1).ipynb)

### 🔹 Nested If
- An `if` inside another `if`/`else` to handle hierarchical decisions.  
- Checks multiple conditions in a logical order.

### 🔹 Lists in Python
- **Ordered, mutable, indexed, allows duplicates.**  
- Can store mixed data types.  
[List - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-04/List.ipynb)

**Common Operations:** append, insert, sort, reverse, remove, pop, palindrome check.  

---

## 🧭 Summary
- Multiple alternate (`if–elif–else`) and nested if for conditional logic.  
- Lists: creation, properties, operations, sorting, reversing, palindrome check.  

---

### 📂 Full Week 04 Repository
[Week 04 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-04)

---
# 🐍 Week-05 Summary

## 📘 Topic: Repetitive Structures (Loops) in Python

### 🔹 Python Loops
- **while loops:** Execute as long as a condition is `True`.  
- **for loops:** Iterate over a sequence of elements.  
[While & For Loops - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

### 🔹 Sum of Numbers
- Using **while loop** with unknown or known iterations.  
- Can exit loop using **negative input** or fixed count.

### 🔹 Continue & Break
- **continue:** Skip current iteration.  
- **break:** Exit loop completely.  

### 🔹 Else with While
- Executes after loop ends naturally (condition is False).

### 🔹 Printing Numbers
- Odd numbers from 1–100 using while loop in multiple ways.  
- Multiplication table using loop.

### 🔹 Nested While Loops
- Loop inside another loop for repeated operations.  
[Nested While Loop - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Nested_WhileLoop.ipynb)

---

### 📂 Full Week 05 Repository
[Week 05 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-05)
---
# 🐍 Week-06 Summary

## 📘 Topic: Functions, Dictionary, Range & For Loop

### 🔹 Functions
- **Block of code executed when called**; can accept parameters and return values.  
- **Create:** `def Function_Name(params): statements`  
- **Call:** `Function_Name(args)`  
- Supports **keyword arguments** and **return values**.  
[Functions - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Functions.ipynb)  
[Calculator Assignment - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Assignment.ipynb)

### 🔹 Dictionaries
- Stores data in **key:value** pairs; ordered, changeable, no duplicate keys.  
- Access via keys, values, or items.  
[Dictionary - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Dictionary.ipynb)

### 🔹 Python Collections
- **List:** Ordered, changeable, allows duplicates  
- **Tuple:** Ordered, unchangeable, allows duplicates  
- **Set:** Unordered, unindexed, no duplicates  
- **Dictionary:** Ordered, changeable, no duplicate keys

### 🔹 Range Function
- Generates number sequences: `range(start, stop, step)`  
- Example: squares of first 7 numbers using `for el in range(1,8): print(el*el)`  

### 🔹 For Loop
- Iterates over sequences (list, tuple, string, etc.)  
- Can use `else` after loop, print in single line with `end=" "`  
- Example: multiplication table using `for el in range(1,11): print(n,"*",el,"=",n*el)`  
[Range & For Loop - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Range%26ForLoop.ipynb)

---

### 📂 Full Week 06 Repository
[Week 06 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-06)
---
# 🐍 Week-07 Summary

## 📘 Topic: Advanced Functions, Recursion & File Handling

### 🔹 Advanced Functions
- **Default Parameters:** Assign default values to parameters.  
- **Arbitrary Arguments (*args):** Accept variable number of arguments as a tuple.  
- **Keyword Arguments:** Pass arguments using `key=value` syntax.  
- **Pass Statement:** Placeholder for empty functions, loops, or conditionals.  

### 🔹 Recursion
- A function calling itself with **base case** and **recursive case**.  
- Example: Factorial calculation.  
[Recursion - GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-07/Recursion.ipynb)

### 🔹 File Handling
- Perform operations: create, open, read, write, close.  
- **Open Syntax:** `file = open(File_Name, mode)`  
- **Modes:** `"r"` read, `"w"` write, `"a"` append, `"x"` create; `"t"` text, `"b"` binary.  

**Examples:**  
- Reading a file: `file.read()`, `file.readline()`  
- Writing a file: `file.write("text")`  
- Appending to a file: `file.write("text")`  
- Always close file: `file.close()`

---

### 📂 Full Week 07 Repository
[Week 07 Class Work – Python Basic Building Blocks](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-07)
---
# 🐍 Week-08 Summary

## 📘 Topic: Object Oriented Programming (OOP)

---

### 🔹 Overview
Object Oriented Programming (OOP) in Python allows modeling real-world entities using **objects**, enabling **data encapsulation, inheritance, polymorphism, and abstraction**. OOP overcomes limitations of procedural programming such as poor real-world modeling and unrestricted access to global data.

---

### 🔹 Key Differences: Procedural vs OOP

| Feature                  | Procedural | OOP                     |
| ------------------------ | ---------- | ----------------------- |
| Unit                     | Function   | Class                   |
| Approach                 | Top-down   | Bottom-up               |
| Adding new data/function | Difficult  | Easy                    |
| Focus                    | Functions  | Both data & functions   |

---

### 🔹 Fundamental OOP Concepts
* **Inheritance:** Reuse and extend base class functionality.
* **Polymorphism:** Same method/operator behaves differently in different contexts.
* **Encapsulation:** Restrict direct access to data; expose via methods.
* **Abstraction:** Hide implementation details; expose only essential features.

---

### 🔹 Learning Resources
* Detailed **OOP programs** and examples: [View Full OOP Programs](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-08/OOP_Python.ipynb)

---

### 🔹 Full Repository Access
[Python-Basic-Building-Blocks Full Repo](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-08)
---

## 🏁 Covered Topics

This repository contains Python programming notes covering the basics through advanced topics, structured week by week. Topics included:

- ✅ Python Basics  
- ✅ Variables, Data Types, and Operators  
- ✅ Loops & Control Structures  
- ✅ Lists & Dictionaries  
- ✅ Functions & Recursion  
- ✅ File Handling  
- ✅ Object-Oriented Programming  

---

## 🧑‍💻 Author

**Muhammad Ibrahim** (BSCS Student)

---

## 📜 License

This project is licensed under the MIT License.

## How to Use
Clone the repository and open the notebooks using **Google Colab** or **Jupyter Notebook**:

```bash
git clone https://github.com/mibrahim-O2/Python_Programs.git
cd Python_Programs
jupyter notebook
```
---
