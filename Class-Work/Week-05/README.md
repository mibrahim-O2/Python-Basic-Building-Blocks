# 🐍 Python Notes - Week 05

## 📘 Topic: Repetitive Structures (Loops) in Python

---

### 🔹 Python Loops

Python has two primitive loop commands:

1. **while loops**
2. **for loops**

Loops are used to execute a set of statements repeatedly based on a condition.

---

### 🔹 While Loop

The **while loop** executes a block of code as long as the condition is `True`.

#### 🧩 Example 1: Print the diagonal of stars (number of lines from user)

```python
n = int(input("Enter the number of lines: "))
count = 1
while count <= n:
    print("*****")
    count += 1
print("Out of loop")
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

#### 🧩 Example 2: Print fixed 5 lines of stars

```python
count = 1
while count <= 5:
    print("*****")
    count += 1
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Sum of Numbers Using While Loop (Unknown Iterations)

Take numbers from user and add them using while loop; the number of repetitions is unknown. Exit the loop when a negative number is entered.

```python
sum = 0
x = int(input("Enter a number: "))
while x >= 0:
    sum += x
    x = int(input("Enter a number: "))
print("Sum =", sum)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

Alternative implementation using `if` inside the loop:

```python
sum = 0
x = 1
while x >= 0:
    x = int(input("Enter a number: "))
    if x >= 0:
        sum += x
print("Sum =", sum)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Sum of Numbers Using While Loop (Known Iterations)

Take four numbers from user and add them using while loop; the number of repetitions is known.

```python
sum = 0
n = 1
while n <= 4:
    x = int(input("Enter a number: "))
    sum += x
    n += 1
print("Sum =", sum)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Continue and Break Statements

* **continue:** Stops the current iteration and continues with the next iteration.
* **break:** Stops the loop completely, even if the while condition is `True`.

#### 🧩 Example: Sum only even numbers, ignore odd numbers, exit on negative

```python
sum = 0
n = 1
while n > 0:
    n = int(input("Enter a number: "))
    if n < 0:
        break
    elif n % 2 != 0:
        continue
    else:
        sum += n
print("Sum =", sum)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Else Statement with While Loop

The `else` statement can be used with while loops to run a block of code once when the loop condition is no longer true.

#### 🧩 Example: Sum numbers until negative input, then else executes

```python
sum = 0
n = int(input("Enter a number: "))
while n > 0:
    sum += n
    n = int(input("Enter a number: "))
else:
    print("Loop ended here")
print("Sum =", sum)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Printing Odd Numbers from 1 to 100

#### Method 1:

```python
c = 1
while c <= 100:
    if c % 2 == 1:
        print(c)
    c += 1
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

#### Method 2 (using continue):

```python
c = 1
while c <= 100:
    if c % 2 == 0:
        c += 1
        continue
    print(c)
    c += 1
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

#### Method 3 (increment by 2):

```python
c = 1
while c <= 100:
    print(c)
    c += 2
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Printing Multiplication Table

```python
c = 1
n = int(input("Enter the number: "))
while c <= 10:
    print(n, "*", c, "=", n*c)
    c += 1
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Repititve_Structure.ipynb)

---

### 🔹 Nested While Loops

A **nested loop** is a loop inside another loop. This allows repeated operations for each iteration of the outer loop.

#### 🧩 Example: Nested sum calculation

```python
sum = 0
c2 = 1
while c2 <= 4:
    c = 1
    while c <= 5:
        sum += c
        c += 1
    c2 += 1
print("Final sum is:", sum)
```

📎 [GitHub Link](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-05/Nested_WhileLoop.ipynb)

