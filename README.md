# 🚀 Basic

> A collection of fundamental programming concepts and beginner-friendly code examples designed to build strong logic and coding foundations.

---

## 📌 Overview

The **Basic** repository contains simple and essential programs that help in understanding core programming concepts such as:

* Variables & Data Types
* Conditional Statements
* Loops
* Functions
* Error Handling

This repository is ideal for beginners and also serves as a quick revision resource.

---

## 🧠 Concepts Covered

* 🔢 Input / Output
* 🔁 Loops (for, while)
* 🔀 Conditional Statements (if-else)
* 🧩 Functions
* ⚠️ Exception Handling

---

## 💻 Sample Code

### 🔹 Example 1: Simple Calculator (Python)

```python id="code1"
def calculator():
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    
    print("1. Add\n2. Subtract\n3. Multiply\n4. Divide")
    choice = int(input("Choose operation: "))
    
    if choice == 1:
        print("Result:", a + b)
    elif choice == 2:
        print("Result:", a - b)
    elif choice == 3:
        print("Result:", a * b)
    elif choice == 4:
        print("Result:", a / b)
    else:
        print("Invalid choice")

calculator()
```

---

### 🔹 Example 2: Fibonacci Series

```python id="code2"
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        print(a, end=" ")
        a, b = b, a + b

fibonacci(10)
```

---

### 🔹 Example 3: Exception Handling

```python id="code3"
try:
    num = int(input("Enter number: "))
    print(10 / num)
except ZeroDivisionError:
    print("Cannot divide by zero")
except ValueError:
    print("Invalid input")
```

---

## 📂 Project Structure

```id="code4"
basic/
│── calculator.py
│── fibonacci.py
│── exception_handling.py
│── README.md
```

---

## ⚙️ How to Run

```bash id="code5"
git clone https://github.com/your-username/basic.git
cd basic
python filename.py
```

---

## 🚀 Purpose

This repository is created to:

* Strengthen programming fundamentals
* Practice logic building
* Serve as a base for advanced development

---

## 🔥 Future Improvements

* Add more problem-solving examples
* Include data structures
* Add mini-projects

---

## 👨‍💻 Author

**Vedant Kaipil**

* GitHub: https://github.com/your-username

---

## ⭐ Support

If you find this helpful, give it a ⭐ and share with others!
