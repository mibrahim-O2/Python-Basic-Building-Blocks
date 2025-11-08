# 🐍 Python Notes - Week 08

## 📘 Topic: Object Oriented Programming (OOP) in Python

---

### 🔹 Procedural Programming

* Procedural Programming is based on structured programming and calling procedures (routines, subroutines, or functions).
* A procedural program is divided into functions, each with a clearly defined purpose and interface.
* Functions can be called by other procedures or themselves during execution.

**Problems with Procedural Programming:**

* **Unrestricted Access:** Functions have unrestricted access to global data.
* **Real World Modeling:** Unrelated functions and data provide a poor model of the real world.
* **Difficulty in creating new data types:** Traditional languages do not allow easy creation of new data types.

---

### 🔹 What is Object Oriented Programming (OOP)?

* OOP uses **objects** to represent real-life entities like students, desks, mobiles, etc.
* Objects aim to implement real-world concepts like inheritance, hiding, and polymorphism.
* **Main Aim:** Bind data and functions together so data can only be accessed by specific methods.
* **Key Features:**

  * **Data Hiding:** Data is hidden inside the object and accessible only by member functions.
  * **Encapsulation:** Bundling data and functions in a single entity called an object.

**Procedural vs OOP:**

| Feature                  | Procedural | OOP                     |
| ------------------------ | ---------- | ----------------------- |
| Unit                     | Function   | Class                   |
| Approach                 | Top-down   | Bottom-up               |
| Adding new data/function | Difficult  | Easy                    |
| Focus                    | Functions  | Both data and functions |

---

### 🔹 OOP Fundamental Building Blocks
**Four fundamental building blocks/components/concepts/features:**

* Inheritance
* Polymorphism
* Encapsulation
* Abstraction

### Inheritance

* Creating new classes from existing class(es).
* New classes: derived/child/sub classes
* Existing classes: base/super classes
  **Advantages:**
* Existing classes remain unchanged; additional features can be added in derived classes
* Base class code need not be rewritten
* Variables and methods of base class usable in child class
* Provides reusability

**Types of Inheritance:**

1. Single Inheritance: child class inherits from single parent
2. Multi-Inheritance: child class inherits from multiple parents
3. Multi-Level Inheritance: class inherits from parent, and parent inherits from another parent
---
 
### 🔹 Basic Structure of Python Class

```python
class Student:
    name = "Ali"
    DOB = "1 jan 2009"

s1 = Student()
print(s1.name)
s2 = Student()
print(s2.name)
```

#### 🔹 Constructor

* Special method invoked automatically when an object is created.

```python
class Student:
    def __init__(self, name, DOB):
        self.name = name
        self.DOB = DOB

s1 = Student("Ali","1 jan 2009")
print(s1.name, s1.DOB)
```

**Example:**

```python
class Teacher:
    def __init__(self,name,salary):
        self.name = name
        self.salary = salary

T1 = Teacher("Sara", 105000)
print(T1.name, T1.salary)
```

---

### 🔹 Inheritance Example in Python

```python
# Main class
class Person:
    def __init__(self, name, age, gender):
        self.name = name
        self.age = age
        self.gender = gender

# Subclasses
class Student(Person):
    def __init__(self, name, age, gender, student_id):
        super().__init__(name, age, gender)
        self.student_id = student_id

class Teacher(Person):
    def __init__(self, name, age, gender, subject):
        super().__init__(name, age, gender)
        self.subject = subject

class Employee(Person):
    def __init__(self, name, age, gender, department):
        super().__init__(name, age, gender)
        self.department = department

# Objects
student = Student("Muhammad Ibrahim", 20, "Male", "CSE/94")
teacher = Teacher("Maam Farhat Naureen", 40, "Female", "Python")
employee = Employee("Ahmed", 40, "Male", "HR")

print("Student Information")
print("Name:", student.name)
print("Age:", student.age)
print("Gender:", student.gender)
print("Student ID:", student.student_id)
```

---

### 🔹 Polymorphism

* Means "many forms". Achieved via method overloading or overriding.
* **Operator Overloading Example:**

```python
print(5 + 10)
print(7.5 + 9.11)
print("IMCS" + ",UOS")
print([1,2,3] + [4,5,6])
```

**Complex Number Example:**

```python
class Complex:
    def __init__(self,real,imag):
        self.real = real
        self.imag = imag
    def display(self):
        print(self.real,"i+",self.imag,"j")
    def add(self,num2):
        return Complex(self.real + num2.real, self.imag + num2.imag)
```

---

### 🔹 Method Overloading
* Multiple methods in same class with same name but different parameters
* Python uses default arguments and variable length argument lists
 
**Default Arguments Example:**

```python
class Calculator:
    def add(self,x,y=None):
        if y is None:
            return x
        else:
            return x+y
c1 = Calculator()
print(c1.add(10))
print(c1.add(10,20))
```

**Variable Length Arguments Example:**

```python
class Calculator:
    def add(self,*args):
        total = 0
        for num in args:
            total += num
        return total
c1 = Calculator()
print(c1.add(10))
print(c1.add(10,20))
print(c1.add(10,20,30))
```

---

### 🔹 Method Overriding

* Subclass provides specific implementation for an inherited method.

```python
class Vehicle:
  def __init__(self,brand,model):
    self.brand = brand
    self.model = model

  def move(self):
    print("Move")

class Car(Vehicle):
  pass

class Plane(Vehicle):
  def move(self):
    print("Fly")

car1 = Car("Toyota","Camry")
plane1 = Plane("Boeing","747")

for el in (car1,plane1):
  print(el.brand,el.model)
  el.move()
```

**Animal Example:**

```python
class Animal:
  def speak(self):
    print("Generic animal sounds")

class Dog(Animal):
  def speak(self):
    print("Dog barks")

class Cat(Animal):
  def speak(self):
    print("Cat meows")

a = Animal()
d = Dog()
c = Cat()

a.speak()
d.speak()
c.speak()
```
---
[View Full OOP Programs on GitHub](https://github.com/mibrahim-O2/Python-Basic-Building-Blocks/blob/main/Class-Work/Week-08/OOP_Python.ipynb)
---
