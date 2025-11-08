# 🐍 Python Notes - Week 07

## 📘 Topic: Advanced Functions, Recursion & File Handling

---

### 🔹 Default Parameter in Function

You can define default values for function parameters.

```python
def Func(n1=0, n2=0, n3=0):
    print(n1, n2, n3)

Func()       # Output: 0 0 0
Func(3,5,7)  # Output: 3 5 7
Func(1,3)    # Output: 1 3 0
```

Non-default values must come first, followed by default values.

```python
def Func(n1, n2=0, n3=0):
    print(n1, n2, n3)

Func(3,5,7)
Func(1,3)
```

Keyword arguments can be passed using `key=value` syntax to allow flexibility in order.

---

### 🔹 Arbitrary Arguments (*args)

When the number of arguments is unknown, use `*args` to receive them as a tuple.

```python
def Func(*args):
    print(args)
    size = len(args)
    print("Received", size, "elements")

Func(1,3,9,7)
Func(1,3)
```

---

### 🔹 Pass Statement

The `pass` statement is used when a function, loop, or conditional needs to exist syntactically but have no content.

```python
for i in range(10):
    pass
```

---

### 🔹 Recursion

A **recursive function** calls itself. It requires a **base case** to stop recursion and a **recursive case** to repeat.

**Example: Factorial of a Number**

```python
def fact(n):
    if n == 0:
        return 1
    return n * fact(n-1)

n = int(input("Enter a Number: "))
result = fact(n)
print("Factorial of", n, "is", result)
```

📎 [GitHub Link](https://github.com/ibraheem-02/Python_Programs/blob/main/Recursion.ipynb)

---

### 🔹 File Handling

File handling allows creating, reading, writing, and closing files.

#### 🔹 Opening a File

```python
Obj_Name = open(File_Name, mode)
```

Modes:

* `r` : Read (default)
* `a` : Append
* `w` : Write
* `x` : Create
* `t` : Text (default)
* `b` : Binary

**Example: Reading a File**

```python
F1 = open("Class_Work/File.txt", "r")
print(F1.read())
F1.close()
```

**Read Character by Character or Line by Line**

```python
F2 = open("Class_Work/File.txt", "r")
print(F2.read(10))
F2.close()

F3 = open("Class_Work/File.txt", "r")
print(F3.readline())
print(F3.readline())
F3.close()
```

---

#### 🔹 Writing to a File

**Write Mode (`w`)**

```python
F4 = open("Class_Work/File.txt", "w")
F4.write("\nThis is the new line added to the file")
F4.close()
```

**Append Mode (`a`)**

```python
F1 = open("Class_Work/File.txt", "a")
F1.write("Muhammad Khalid")
F1.close()
```

---

#### 🔹 Closing a File

Always close files to release system resources.

```python
F1.close()
```

📎 [GitHub Link for File Handling](https://github.com/ibraheem-02/Python_Programs/blob/main/File_Handling.ipynb)
