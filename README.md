# Python_Programs

This repository contains a collection of Python programs and Jupyter notebooks that I have implemented while learning programming fundamentals and problem-solving.  
Each topic is explained briefly, and the corresponding notebook can be opened directly in **Google Colab** or previewed on **GitHub**.
# 🐍 Python Notes - Week 01 (Summary)

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

# 🐍 Python Notes - Week 02 (Summary)

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

## ✨ Why Both GitHub & Colab Links?

In this repository, every notebook has **two links**:  

- 📄 **View on GitHub** – Quickly preview the notebook and code without leaving GitHub. Useful if you just want to **read or review**.  
- 🚀 **Open in Colab** – Instantly run, edit, and experiment with the code in Google Colab (no installation or setup required).  

👉 This approach helps students in two ways:  
- Study the **logic** directly on GitHub.  
- Practice **hands-on coding** on Colab.  

---

## Topics Covered

### 1. **Basics of Python**
- **User Input** – How to take input from the user.  
  📄 [View on GitHub](./User_Input.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/User_Input.ipynb)  

- **Type Casting** – Converting between data types (int, float, str, etc.).  
  📄 [View on GitHub](./Type_Casting.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Type_Casting.ipynb)  

- **Operators** – Arithmetic, comparison, logical, and assignment operators.  
  📄 [View on GitHub](./Operators.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Operators.ipynb)  

---

### 2. **Control Structures**
- **Conditional Statements** – Using `if`, `elif`, and `else`.  
  📄 [View on GitHub](./Control_Structures.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Control_Structures.ipynb)  

- **Repetitive Structures (Loops)** – Understanding loops in Python.  
  📄 [View on GitHub](./Repititve_Structure.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Repititve_Structure.ipynb)  

- **Extra Practice on Loops** – Additional exercises.  
  📄 [View on GitHub](./Repitive_Structure.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Repitive_Structure.ipynb)  

---

### 3. **Loops & Iteration**
- **For Loops & Range** – Iteration using `for` loops with `range()`.  
  📄 [View on GitHub](./Range%26ForLoop.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Range%26ForLoop.ipynb)  

- **Nested While Loops** – Using multiple `while` loops and loop control (`break`, `continue`).  
  📄 [View on GitHub](./Nested_WhileLoop.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Nested_WhileLoop.ipynb)  

---

### 4. **Functions**
- **Functions** – Defining, calling, and using parameters and return values.  
  📄 [View on GitHub](./Functions.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Functions.ipynb)  

- **Recursion** – Recursive functions like factorial and Fibonacci.  
  📄 [View on GitHub](./Recursion.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Recursion.ipynb)  

---

### 5. **Data Structures**
- **Strings** – String operations, methods, and manipulations.  
  📄 [View on GitHub](./String_Functions.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/String_Functions.ipynb)  

- **Lists** – Creating, indexing, slicing, updating, and iterating lists.  
  📄 [View on GitHub](./List.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/List.ipynb)  

- **Dictionaries** – Key–value storage, updating, and retrieving data.  
  📄 [View on GitHub](./Dictionary.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Dictionary.ipynb)  

- **Swapping Values** – Different ways of swapping values in Python.  
  📄 [View on GitHub](./Swapping.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Swapping.ipynb)  

---

### 6. **Problem-Solving Programs**
- **Converter Programs** – Examples like unit and temperature converters.  
  📄 [View on GitHub](./Converter.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Converter.ipynb)  

- **Assignment 01** – Practice problems covering basics of Python.  
  📄 [View on GitHub](./Assignment01.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Assignment01.ipynb)  

- **Midterm Practice** – Problem-solving exercises for midterm preparation.  
  📄 [View on GitHub](./Middterm.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/Middterm.ipynb)  

---

### 7. **Object-Oriented Programming (OOP)**
- **OOP Basics** – Introduction to classes, objects, attributes, and methods.  
  📄 [View on GitHub](./OOP.ipynb) | 🚀 [Open in Colab](https://colab.research.google.com/github/mibrahim-O2/Python_Programs/blob/main/OOP.ipynb)  

---

> ⚠️ **Important:**  
> You can open and edit these notebooks in **Google Colab** for practice.  
> However, any changes you make will **only affect your copy in Colab** —  
> the original files in this GitHub repository will remain unchanged.

---

## How to Use
Clone the repository and open the notebooks using **Google Colab** or **Jupyter Notebook**:

```bash
git clone https://github.com/mibrahim-O2/Python_Programs.git
cd Python_Programs
jupyter notebook
