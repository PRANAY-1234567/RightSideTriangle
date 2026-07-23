# Right-Aligned Half Pyramid Pattern in Python

## 📌 Overview

This project is a simple Python program that prints a **right-aligned half pyramid** using the `*` (asterisk) character.

The program uses a `for` loop to generate each row. Leading spaces are printed before the stars so that the pyramid is aligned to the right.

This project is ideal for beginners learning **loops**, **string multiplication**, and **pattern programming** in Python.

---

## 🚀 Features

* Prints a right-aligned half pyramid
* Uses a single `for` loop
* Demonstrates string multiplication for formatting
* Easy-to-understand and beginner-friendly code
* Customizable number of rows

---

## 🛠️ Technologies Used

* Python 3

---

## 📂 Project Structure

```text
├── right_aligned_half_pyramid.py
└── README.md
```

---

## 💻 Source Code

```python
rows = 5

for i in range(1, rows + 1):
    print(" " * (rows - i) + "*" * i)
```

---

## ▶️ How to Run

### Clone the Repository

```bash
git clone https://github.com/your-username/python-right-half-pyramid.git
cd python-right-half-pyramid
```

### Run the Program

```bash
python right_aligned_half_pyramid.py
```

---

## 📋 Sample Output

```text
    *
   **
  ***
 ****
*****
```

---

## 🧠 Concepts Covered

* `for` Loop
* Pattern Programming
* String Multiplication
* String Concatenation
* Console Output Formatting

---

## 🔍 How It Works

1. Set the total number of rows.
2. Loop from **1** to the number of rows.
3. For each row:

   * Print the required number of leading spaces using:

     ```python
     " " * (rows - i)
     ```
   * Print the required number of stars using:

     ```python
     "*" * i
     ```
4. Combine both strings to create a right-aligned half pyramid.

---

## 📐 Pattern Logic

For `rows = 5`:

| Row | Spaces | Stars | Output  |
| --: | -----: | ----: | ------- |
|   1 |      4 |     1 | `    *` |
|   2 |      3 |     2 | `   **` |
|   3 |      2 |     3 | `  ***` |
|   4 |      1 |     4 | ` ****` |
|   5 |      0 |     5 | `*****` |

---

## ⏱️ Complexity Analysis

| Operation        | Complexity |
| ---------------- | ---------- |
| Time Complexity  | **O(n²)**  |
| Space Complexity | **O(1)**   |

Where **n** is the number of rows. Each row prints a combination of spaces and stars.

---

## 🔮 Future Improvements

* Accept the number of rows from the user
* Print an inverted half pyramid
* Create a full pyramid pattern
* Generate diamond and hollow star patterns
* Allow users to choose different symbols instead of `*`

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

* How loops generate patterns
* Using string multiplication for formatting
* Aligning output with spaces
* Basic pattern programming techniques
* Writing clean and readable Python code

---

## 👨‍💻 Author

**Pranay Jadhao**

Electronics & Telecommunication Engineer

Aspiring Software Engineer | Python | Java | SQL | Data Analytics

---

## 📄 License

This project is open-source and available for educational and learning purposes.

<img width="503" height="784" alt="image" src="https://github.com/user-attachments/assets/84751889-f9c4-4f42-a107-6c07cbae8a4c" />
