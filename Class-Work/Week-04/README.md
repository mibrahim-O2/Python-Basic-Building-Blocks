# 🐍 Python Notes - Week 04

## 📘 Topic: Multiple Alternate, Nested If & Lists in Python

---

### 🔹 Multiple Alternate

📎 [Control Structures - GitHub Link](https://github.com/ibraheem-02/Python_Programs/blob/main/Control_Structures.ipynb)

When we have **more than two conditions** to check, we use the **if–elif–else** structure.
It allows the program to evaluate multiple conditions sequentially and execute the block of code corresponding to the first `True` condition.

---

#### 🧠 Concept:

* The `if` block executes if its condition is `True`.
* If the first condition is `False`, Python checks the next `elif`.
* If none of the conditions are `True`, the `else` block executes.
* Only **one** block executes in a multiple alternate structure.

---

#### 🧩 Example:

**Program to find the largest of three numbers using else-if:**

```python
n1 = int(input("Enter 1st no: "))
n2 = int(input("Enter 2nd no: "))
n3 = int(input("Enter 3rd no: "))

if n1 > n2 and n1 > n3:
    print("1st no is largest")
elif n2 > n1 and n2 > n3:
    print("2nd no is largest")
else:
    print("3rd no is largest")
```

✅ **Output Example:**

```
Enter 1st no: 7
Enter 2nd no: 3
Enter 3rd no: 9
3rd no is largest
```

---

### 🔹 Nested If Statement

A **nested if statement** means having an `if` statement inside another `if` or `else` block.
It allows checking multiple conditions in a hierarchical manner.

---

#### 🧠 Concept:

* Used when one decision depends on another.
* Makes logical grouping of related conditions.

---

#### 🧩 Example:

**Program to find the largest of three numbers using nested if:**

```python
n1 = int(input("Enter 1st no: "))
n2 = int(input("Enter 2nd no: "))
n3 = int(input("Enter 3rd no: "))

if n1 > n2:
    if n1 > n3:
        print("1st no is largest")
    else:
        print("3rd no is largest")
else:
    if n2 > n3:
        print("2nd no is largest")
    else:
        print("3rd no is largest")
```

---

### 🔹 Lists in Python

📎 [Lists - GitHub Link](https://github.com/ibraheem-02/Python_Programs/blob/main/List.ipynb)

A **list** is a built-in data structure in Python that stores an **ordered collection of elements**.
Lists are **mutable**, meaning they can be changed after creation.
They can store **different data types** together (e.g., strings, integers, floats).

---

#### 🧩 Example:

```python
student = ["M Ibrahim", 94, 3.5]
print(student)
print(type(student))
```

**Output:**

```
['M Ibrahim', 94, 3.5]
<class 'list'>
```
### or
# List

**List:** A list is a data structure in Python that is a mutable, or changeable, ordered sequence of elements.  
Lists are created using square brackets. Stores different type of data type at a time.  

**Example:**  
```python
list = [ "Ibrahim" , 20 , 9.75 ]

---

### 🔹 List Properties

* **Ordered:** Items have a defined sequence and maintain it.
* **Changeable:** You can modify, add, or remove elements.
* **Allow Duplicates:** Lists can contain duplicate values.
* **Indexed:** Items can be accessed using indexes starting from `0`.

---

### 🔹 Common List Operations

| Operation                   | Description                          | Example                   |
| --------------------------- | ------------------------------------ | ------------------------- |
| `list.append(value)`        | Adds item at the end                 | `list.append(10)`         |
| `list.insert(index, value)` | Inserts item at given position       | `list.insert(0, 5)`       |
| `list.sort()`               | Sorts list in ascending order        | `list.sort()`             |
| `list.sort(reverse=True)`   | Sorts list in descending order       | `list.sort(reverse=True)` |
| `list.reverse()`            | Reverses list order                  | `list.reverse()`          |
| `list.remove(value)`        | Removes first occurrence of item     | `list.remove(5)`          |
| `list.pop(index)`           | Removes item at index (default last) | `list.pop(2)`             |

---

#### 🧩 Example Program:

```python
list = [3, 2, 6, 1]
print("List before operations:", list)

list.append(15)
print(list)

list.insert(0, 1)
print(list)

list.sort()
print("Sorted in Ascending order:", list)

list.sort(reverse=True)
print("Sorted in Descending order:", list)

list.reverse()
print("Reversed List:", list)

list.remove(1)
print("After removing 1st element:", list)

list.pop(2)
print("After popping index 2:", list)
```

---

### 🔹 Sorting Strings in List

```python
list1 = ["Ibraheem", "Ali", "Rehman"]

list1.sort()
print("Ascending Order:", list1)

list1.sort(reverse=True)
print("Descending Order:", list1)
```

---

### 🔹 Check if a List is Palindrome

A **palindrome** list reads the same backward and forward.

#### 🧩 Using Slicing:

```python
List = [1, 2, 3, 2, 1]
if List == List[::-1]:
    print("List is Palindrome")
else:
    print("List is not Palindrome")
```

#### 🧩 Using `copy()` and `reverse()`:

```python
List = [1, 2, 3, 2, 1]
List1 = List.copy()
List1.reverse()
if List == List1:
    print("List is Palindrome")
else:
    print("List is not Palindrome")
```

✅ **Output:**

```
List is Palindrome
```

---

## 🧭 Summary

In this week, you learned:

* How to use **multiple alternate (if–elif–else)** for multi-condition checks.
* How **nested if** structures work.
* The concept of **lists**, their properties, and built-in methods.
* How to perform **sorting, reversing, and palindrome checking** using lists.



