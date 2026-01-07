# 🧩 Fundamental Booster – Interactive Personal Data Collector (Python)

![Banner](./images/Screenshot-2026-01-07-181456.png)

> **Course / Program:** Fundamental Booster – Python (Data Science)  \
> **Organization:** Red & White Skill Education  \
> **Tagline:** *Shaping skills for scaling higher…!!!*

---

## 📌 Project Overview

This project is a **beginner-friendly Python console application** that collects personal information from the user, processes it using **core Python concepts**, and displays the results in a clean, formatted way.

The main goal of this project is to demonstrate a strong understanding of:
- `print()` and `input()` functions
- Data types and variables
- Type casting (`int`, `float`, `str`)
- Arithmetic operators
- Built-in functions: `type()` and `id()`

---

## 🎯 Objective

Create an **Interactive Personal Data Collector** application in Python that:
- Takes user input (name, age, height, favourite number)
- Stores data using appropriate data types
- Performs calculations (birth year from age)
- Displays values along with their **data types and memory addresses**
- Prints a friendly summary at the end

---

## 🧠 Concepts Used (Step-by-Step)

### 1️⃣ Welcome Message

```python
print("Welcome to the Interactive Personal Data Collector!\n")
```
- Uses `print()` to display instructions and guide the user.

---

### 2️⃣ Collecting User Input

```python
name = input("Please enter your name: ")
age = int(input("Please enter your age: "))
height = float(input("Please enter your height in meters: "))
fav_number = int(input("Please enter your favourite number: "))
```

- `input()` is used to collect data from the user
- Type casting ensures correct data types:
  - `age` → `int`
  - `height` → `float`
  - `fav_number` → `int`

---

### 3️⃣ Displaying Collected Information

```python
print("\nThank you! Here is the information we collected:\n")
```

- Improves user experience with clean formatting

---

### 4️⃣ Using `type()` and `id()` Functions

```python
print("Name:", name, "(Type:", type(name), ", Memory Address:", id(name), ")")
print("Age:", age, "(Type:", type(age), ", Memory Address:", id(age), ")")
print("Height:", height, "(Type:", type(height), ", Memory Address:", id(height), ")")
print("Favourite Number:", fav_number, "(Type:", type(fav_number), ", Memory Address:", id(fav_number), ")")
```

- `type()` → shows the data type of each variable
- `id()` → shows the memory address of each variable

---

### 5️⃣ Arithmetic Operation (Birth Year Calculation)

```python
current_year = 2026
birth_year = current_year - age
```

- Uses subtraction operator (`-`)
- Demonstrates real-world calculation using user input

---

### 6️⃣ Final Output Message

```python
print("\nYour birth year is approximately:", birth_year, "(based on your age of", age, ")")
print("\nThank you for using the Personal Data Collector. Goodbye!")
```

- Displays processed results in a friendly and readable format

---

## 🖥️ Example Console Output

![Program Output](./images/python-pr-01-output.png.png)

---

## 📂 Project Structure

```text
Fundamental-Booster/
│
├── pr-01.py                  # Main Python source code
├── README.md                 # Project documentation
└── images/
    ├── Screenshot-2026-01-07-181456.png
    ├── Screenshot-2026-01-07-181502.png
    ├── Screenshot-2026-01-07-181511.png
    ├── Screenshot-2026-01-07-181918.png
    └── python-pr-01-output.png.png
```

---

## 🧾 Code Screenshot

![Code Screenshot](./images/Screenshot-2026-01-07-181918.png)

---

## 📝 Assumptions

- Current year is assumed as **2026**
- Birth year is an approximation based only on age
- Input provided by the user is valid (no error handling added yet)

---

## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/Fundamental-Booster.git
   ```
2. Navigate to the project folder
   ```bash
   cd Fundamental-Booster
   ```
3. Run the Python file
   ```bash
   python pr-01.py
   ```

---

## ✅ Learning Outcomes

- Clear understanding of Python basics
- Hands-on experience with user input and output
- Confidence in using data types and built-in functions
- Improved code readability and formatting skills

---

## 🙌 Acknowledgment

This project is completed as part of the **Fundamental Booster – Python (Data Science)** program by **Red & White Skill Education**.

> **Quality is our Motto.**  \
> **BRING ON YOUR CODING ATTITUDE 💻🔥**

---

⭐ *If you like this project, don’t forget to star the repository!*

