# Python Beginner Projects

This repository contains two simple Python programs:

1. **Odd or Even Checker** (`Task 1.py`)
2. **Sum of Integers from 1 to 50** (`Task 2.py`)

---

## 1. Odd or Even Checker (`Task 1.py`)

### Description
This program checks whether a number entered by the user is **Odd** or **Even**.

### Code
```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print(num, "is an Even Number.")
else:
    print(num, "is an Odd Number.")
```

### Example Run
![Odd or Even Example](odd_even_example.png)

---

## 2. Sum of Integers from 1 to 50 (`Task 2.py`)

### Description
This program calculates the **sum of integers from 1 to 50** using a loop.

### Code
```python
a = 0

for i in range(51):
    a = a + i

print("The sum of numbers from 0 to 50 is:", a)
```

### Example Run
![Sum Example](sum_example.png)

---

## How to Run

1. Make sure you have **Python 3** installed.
2. Open a terminal or command prompt in the folder where the scripts are saved.
3. Run the scripts using:
   ```bash
   python Task\ 1.py
   ```
   ```bash
   python Task\ 2.py
   ```

---

✨ These projects are perfect for learning **basic conditionals and loops** in Python.
