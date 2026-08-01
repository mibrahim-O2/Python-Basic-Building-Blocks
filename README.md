<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=150&section=header&text=Python%20Learning%20Journey&fontSize=34&fontColor=FFD43B&animation=fadeIn&fontAlignY=42"/>

<br/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="140" height="140"/>

</div>

<div align="center">
  
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=16&duration=2800&pause=1000&color=3776AB&center=true&vCenter=true&width=650&lines=Fundamentals+%E2%86%92+Loops+%E2%86%92+Functions+%E2%86%92+OOP;Weekly+Notes+%2B+Notebooks+%2B+Practice+Programs" alt="Typing SVG"/>

<br/>

<img src="https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B&labelColor=0d1b2a">
<img src="https://img.shields.io/badge/Notebooks-Jupyter-FFD43B?style=for-the-badge&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a">
<img src="https://img.shields.io/badge/License-MIT-3776AB?style=for-the-badge&labelColor=0d1b2a">

</div>

This repository contains a collection of Python programs and Jupyter notebooks that I have implemented while learning programming fundamentals and problem-solving. Each topic is explained briefly, and the corresponding notebook can be opened directly in **Google Colab** or previewed on **GitHub**.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=2" width="100%"/>

## Table of Contents

| Week | Topic |
|:---:|---|
| [01](#week-01--computer--programming-fundamentals) | Computer & Programming Fundamentals |
| [02](#week-02--variables-naming-conventions--operators) | Variables, Naming Conventions & Operators |
| [03](#week-03--type-casting-user-input-strings--control-structures) | Type Casting, User Input, Strings & Control Structures |
| [04](#week-04--multiple-alternate-nested-if--lists) | Multiple Alternate, Nested If & Lists |
| [05](#week-05--repetitive-structures-loops) | Repetitive Structures (Loops) |
| [06](#week-06--functions-dictionary-range--for-loop) | Functions, Dictionary, Range & For Loop |
| [07](#week-07--advanced-functions-recursion--file-handling) | Advanced Functions, Recursion & File Handling |
| [08](#week-08--object-oriented-programming-oop) | Object Oriented Programming (OOP) |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:FFD43B,100:0d1b2a&height=2" width="100%"/>

## Week 01 — Computer & Programming Fundamentals

### Computer & Programming
- **Computer:** Electronic device that processes and stores data.
- **Program:** Set of instructions for a computer to perform tasks.
- **Computer Programming:** Process of writing instructions (programs) for computers.

### Languages & Translators
- **Language:** System of communication using grammar and vocabulary.
- **Translator:** Converts programming instructions into binary/machine code.
- **High-Level Language:** Human-readable (e.g., Python, Java).
- **Assembly Language:** Translates between high-level and machine language.
- **Compiler-Based Language:** Converts code to machine code before execution (e.g., C, C++).
- **Interpreter-Based Language:** Executes code line by line (e.g., Python, JavaScript).

### Compiler & Interpreter
- **Compiler:** Converts full source code into machine code.
- **Interpreter:** Executes code one instruction at a time without compiling.

### Compile Time vs Run Time
- **Compile Time:** Code translation and error checking before execution.
- **Run Time:** Execution phase where instructions are carried out and runtime errors occur.
- **Key Difference:** Compile time detects syntax/semantic errors; runtime handles execution and dynamic errors.

### Errors
- **Syntax Error:** Code structure mistakes (e.g., missing parentheses).
- **Compile Time Error:** Found during compilation (e.g., undeclared variables).
- **Run Time Error:** Occurs while running (e.g., division by zero).

### Case Sensitivity & Syntax
- **Case-Sensitive:** Languages that distinguish between uppercase and lowercase (e.g., Python, Java).
- **Syntax:** Rules that define valid code structure.
  - Example: `print("Hello, World!")` in Python.

### Character Set, Reserved Words & Keywords
- **Character Set:** Collection of symbols a computer can process.
- **Reserved Words:** Reserved by the language; not usable as identifiers.
- **Keywords:** Words with special meaning in the language (e.g., `def`, `if`, `return`).
- **Special Words:** Context-specific terms (e.g., `self` in Python).

### Memory
- **Memory:** Space where data is stored during program execution.
- **Key Points:**
  - Stores variables and temporary data.
  - Each data piece has a unique address.
  - Managed logically by the OS to prevent leaks.

### Data Types
- **int:** Whole numbers (e.g., 1, -5).
- **float:** Decimal numbers (e.g., 3.14).
- **str:** Text values (e.g., "Hello").
- **bool:** Logical values (True/False).

### Variables
- **Variables:** Named memory locations to store data that can change during program execution.

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-01"><img src="https://img.shields.io/badge/Week_01_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=1" width="100%"/>

## Week 02 — Variables, Naming Conventions & Operators

### Variable Declaration / Naming
- Variables can be short (`x`, `y`) or descriptive (`age`, `car_name`, `total_volume`).
- **Rules for Python Variables:**
  - Must start with a **letter** or **underscore (`_`)**
  - Cannot start with a **number**
  - Can only contain **alphanumeric characters & underscores** (`A-z`, `0-9`, `_`)
  - **Case-sensitive** (`age`, `Age`, `AGE` are different)
  - Cannot be any **Python keyword**

### Multi-Word Variable Names

| Style | Example | Description |
|---|---|---|
| Camel Case | `myVariableName = "Muhammad Ibrahim"` | Each word except the first starts with a capital letter |
| Pascal Case | `MyVariableName = "Muhammad Ibrahim"` | Each word starts with a capital letter |
| Snake Case | `my_variable_name = "Muhammad Ibrahim"` | Words separated by underscores |

### Two Ways to Store Values
1. **Assignment Operator**
2. **User Input**

> **Note:** A variable cannot be assigned on the right-hand side as constants cannot store variables due to memory allocation.

### Python Programs

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-02/Swapping.ipynb"><img src="https://img.shields.io/badge/Swapping_Two_Numbers-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-02/Operators.ipynb"><img src="https://img.shields.io/badge/Operators-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-02"><img src="https://img.shields.io/badge/Week_02_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:FFD43B,100:0d1b2a&height=1" width="100%"/>

## Week 03 — Type Casting, User Input, Strings & Control Structures

### Type Casting
- **Converts a variable from one type to another**.
- **Explicit:** Programmer manually converts using functions.
- **Implicit:** Python automatically converts to avoid data loss.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/Type_Casting.ipynb"><img src="https://img.shields.io/badge/Type_Casting-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### User Input
- Use `input(prompt)` to get data from the user.
- Programs can take input and perform operations like average, comparison, etc.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/User_Input.ipynb"><img src="https://img.shields.io/badge/User_Input-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Strings
- Strings are enclosed in `' '` or `" "`; multiline strings use triple quotes.
- Functions: concatenation, length, indexing, capitalize, replace, find, count.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/String_Functions.ipynb"><img src="https://img.shields.io/badge/String_Functions-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Control Structures
- **Flow of execution:** Sequential (default), Selection (conditional).
- **Selection Flow:** `if`, `elif`, `else` for single, double, or multiple conditions.
- Only the first `True` condition executes its block.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-03/Control_Structures.ipynb"><img src="https://img.shields.io/badge/Control_Structures-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-03"><img src="https://img.shields.io/badge/Week_03_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=1" width="100%"/>

## Week 04 — Multiple Alternate, Nested If & Lists

### Multiple Alternate
- Use **if–elif–else** to evaluate multiple conditions sequentially.
- Only the first `True` block executes.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-04/Control_Structures%20(1).ipynb"><img src="https://img.shields.io/badge/Control_Structures-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Nested If
- An `if` inside another `if`/`else` to handle hierarchical decisions.
- Checks multiple conditions in a logical order.

### Lists in Python
- **Ordered, mutable, indexed, allows duplicates.**
- Can store mixed data types.
- **Common Operations:** append, insert, sort, reverse, remove, pop, palindrome check.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-04/List.ipynb"><img src="https://img.shields.io/badge/Lists-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Summary
- Multiple alternate (`if–elif–else`) and nested if for conditional logic.
- Lists: creation, properties, operations, sorting, reversing, palindrome check.

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-04"><img src="https://img.shields.io/badge/Week_04_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:FFD43B,100:0d1b2a&height=1" width="100%"/>

## Week 05 — Repetitive Structures (Loops)

### Python Loops
- **while loops:** Execute as long as a condition is `True`.
- **for loops:** Iterate over a sequence of elements.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb"><img src="https://img.shields.io/badge/While_%26_For_Loops-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Sum of Numbers
- Using **while loop** with unknown or known iterations.
- Can exit loop using **negative input** or fixed count.

### Continue & Break
- **continue:** Skip current iteration.
- **break:** Exit loop completely.

### Else with While
- Executes after loop ends naturally (condition is False).

### Printing Numbers
- Odd numbers from 1–100 using while loop in multiple ways.
- Multiplication table using loop.

### Nested While Loops
- Loop inside another loop for repeated operations.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Nested_WhileLoop.ipynb"><img src="https://img.shields.io/badge/Nested_While_Loop-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-05"><img src="https://img.shields.io/badge/Week_05_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=1" width="100%"/>

## Week 06 — Functions, Dictionary, Range & For Loop

### Functions
- **Block of code executed when called**; can accept parameters and return values.
- **Create:** `def Function_Name(params): statements`
- **Call:** `Function_Name(args)`
- Supports **keyword arguments** and **return values**.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Functions.ipynb"><img src="https://img.shields.io/badge/Functions-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Assignment.ipynb"><img src="https://img.shields.io/badge/Calculator_Assignment-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Dictionaries
- Stores data in **key:value** pairs; ordered, changeable, no duplicate keys.
- Access via keys, values, or items.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Dictionary.ipynb"><img src="https://img.shields.io/badge/Dictionary-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### Python Collections
- **List:** Ordered, changeable, allows duplicates
- **Tuple:** Ordered, unchangeable, allows duplicates
- **Set:** Unordered, unindexed, no duplicates
- **Dictionary:** Ordered, changeable, no duplicate keys

### Range Function
- Generates number sequences: `range(start, stop, step)`
- Example: squares of first 7 numbers using `for el in range(1,8): print(el*el)`

### For Loop
- Iterates over sequences (list, tuple, string, etc.)
- Can use `else` after loop, print in single line with `end=" "`
- Example: multiplication table using `for el in range(1,11): print(n,"*",el,"=",n*el)`

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-06/Range%26ForLoop.ipynb"><img src="https://img.shields.io/badge/Range_%26_For_Loop-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-06"><img src="https://img.shields.io/badge/Week_06_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:FFD43B,100:0d1b2a&height=1" width="100%"/>

## Week 07 — Advanced Functions, Recursion & File Handling

### Advanced Functions
- **Default Parameters:** Assign default values to parameters.
- **Arbitrary Arguments (\*args):** Accept variable number of arguments as a tuple.
- **Keyword Arguments:** Pass arguments using `key=value` syntax.
- **Pass Statement:** Placeholder for empty functions, loops, or conditionals.

### Recursion
- A function calling itself with **base case** and **recursive case**.
- Example: Factorial calculation.

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-07/Recursion.ipynb"><img src="https://img.shields.io/badge/Recursion-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

### File Handling
- Perform operations: create, open, read, write, close.
- **Open Syntax:** `file = open(File_Name, mode)`
- **Modes:** `"r"` read, `"w"` write, `"a"` append, `"x"` create; `"t"` text, `"b"` binary.

**Examples:**
- Reading a file: `file.read()`, `file.readline()`
- Writing a file: `file.write("text")`
- Appending to a file: `file.write("text")`
- Always close file: `file.close()`

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-07"><img src="https://img.shields.io/badge/Week_07_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=1" width="100%"/>

## Week 08 — Object Oriented Programming (OOP)

### Overview

Object Oriented Programming (OOP) in Python allows modeling real-world entities using **objects**, enabling **data encapsulation, inheritance, polymorphism, and abstraction**. OOP overcomes limitations of procedural programming such as poor real-world modeling and unrestricted access to global data.

### Key Differences: Procedural vs OOP

| Feature | Procedural | OOP |
|---|---|---|
| Unit | Function | Class |
| Approach | Top-down | Bottom-up |
| Adding new data/function | Difficult | Easy |
| Focus | Functions | Both data & functions |

### Fundamental OOP Concepts
- **Inheritance:** Reuse and extend base class functionality.
- **Polymorphism:** Same method/operator behaves differently in different contexts.
- **Encapsulation:** Restrict direct access to data; expose via methods.
- **Abstraction:** Hide implementation details; expose only essential features.

### Learning Resources

<p align="center">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-08/OOP_Python.ipynb"><img src="https://img.shields.io/badge/OOP_Programs-FFD43B?style=flat-square&logo=jupyter&logoColor=3776AB&labelColor=0d1b2a"></a>
</p>

<p align="right">
<a href="https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/tree/main/Class-Work/Week-08"><img src="https://img.shields.io/badge/Week_08_Class_Work-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:FFD43B,100:0d1b2a&height=2" width="100%"/>

## Covered Topics

This repository contains Python programming notes covering the basics through advanced topics, structured week by week.

<p align="center">
<img src="https://img.shields.io/badge/Python_Basics-3776AB?style=flat-square&labelColor=0d1b2a">
<img src="https://img.shields.io/badge/Variables%2C_Data_Types_%26_Operators-FFD43B?style=flat-square&labelColor=0d1b2a&color=FFD43B">
<img src="https://img.shields.io/badge/Loops_%26_Control_Structures-3776AB?style=flat-square&labelColor=0d1b2a">
<img src="https://img.shields.io/badge/Lists_%26_Dictionaries-FFD43B?style=flat-square&labelColor=0d1b2a&color=FFD43B">
<img src="https://img.shields.io/badge/Functions_%26_Recursion-3776AB?style=flat-square&labelColor=0d1b2a">
<img src="https://img.shields.io/badge/File_Handling-FFD43B?style=flat-square&labelColor=0d1b2a&color=FFD43B">
<img src="https://img.shields.io/badge/Object--Oriented_Programming-3776AB?style=flat-square&labelColor=0d1b2a">
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=2" width="100%"/>

<div align="center">

<img src="https://github.com/mibrahim-O2.png" width="120" height="120" style="border-radius:50%;"/>

### Muhammad Ibrahim
**BSCS Student — Institute of Mathematics and Computer Science (IMCS)**
**University of Sindh, Jamshoro**

<sub>These notes and notebooks were completed as part of the <b>Python for Data Science</b> course during my BSCS studies.</sub>

<br/>

<img src="https://img.shields.io/badge/GitHub-mibrahim--O2-3776AB?style=flat-square&logo=github&logoColor=FFD43B&labelColor=0d1b2a"><a href="https://github.com/mibrahim-O2"></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1b2a,50:3776AB,100:0d1b2a&height=1" width="100%"/>

## License

This project is licensed under the MIT License.

## How to Use

Clone the repository and open the notebooks using **Google Colab** or **Jupyter Notebook**:

```bash
git clone https://github.com/mibrahim-O2/Python_Programs.git
cd Python_Programs
jupyter notebook
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,50:FFD43B,100:0d1b2a&height=100&section=footer"/>
</div>
