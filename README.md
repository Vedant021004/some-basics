<!-- 🔥 Animated Header -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:2c5364&height=200&section=header&text=BASIC%20REPOSITORY&fontSize=40&fontColor=ffffff&animation=fadeIn"/>
</p>

<!-- ⚡ Typing Animation -->

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00F7FF&center=true&vCenter=true&width=600&lines=Learning+Programming+Basics;Building+Strong+Logic;From+Beginner+to+Developer;Practice+%7C+Code+%7C+Repeat" />
</p>

---

# 🚀 Basic

> A structured collection of beginner-friendly programs to build strong programming fundamentals.

---

## 🧠 About This Repository

```id="about001"
Focus: Core Programming Concepts
Level: Beginner → Intermediate
Goal: Strong Logic Building
```

This repository is designed to help you:

* Understand basic programming concepts
* Practice logic building
* Prepare for advanced development

---

## 🧰 Concepts Covered

* 🔢 Input / Output
* 🔁 Loops (for, while)
* 🔀 Conditional Statements
* 🧩 Functions
* ⚠️ Exception Handling

---

## 💻 Code Examples

### 🔹 Calculator Program

```python id="code1"
def calculator():
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    
    print("1.Add  2.Subtract  3.Multiply  4.Divide")
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

### 🔹 Fibonacci Series

```python id="code2"
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        print(a, end=" ")
        a, b = b, a + b

fibonacci(10)
```

---

### 🔹 Exception Handling

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

## ⚙️ Run Locally

```bash id="code5"
git clone https://github.com/your-username/basic.git
cd basic
python filename.py
```

---

## 🚀 Learning Path

```id="path001"
Start → Basics → Logic → Practice → Build Projects → Advance
```

---

## 👨‍💻 Author

**Vedant Kaipil**

---

## ⭐ Support

If this repo helps you, give it a ⭐ and keep building 🚀

---

<!-- 🔥 Animated Footer -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=120&section=footer"/>
</p>
