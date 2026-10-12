# python-basics-25N-BCON2138-fibonacci
basic fibonacci program
# Fibonacci Series Generator 🐍

A simple Python project that generates the Fibonacci series up to a specified number of terms. This project demonstrates the use of variables, loops, lists, and functions in Python.

## 📌 Project Description

The Fibonacci Series Generator is a Python program that generates the first `n` numbers of the Fibonacci sequence.

In this sequence, each number is the sum of the two preceding numbers, starting with `0` and `1`.

**Example:** `0, 1, 1, 2, 3, 5, 8, 13, 21, 34`

## ✨ Features

- Generates the Fibonacci series for a specified number of terms.
- Uses a simple and efficient iterative approach.
- Implements a Python function to generate the sequence.
- Stores the generated numbers in a list.
- Beginner-friendly code with no external dependencies.

## 🛠️ Requirements

- Python 3.x
- A code editor or IDE (optional).

**Dependencies:** No external libraries are required.

## 📥 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   ```

2. Navigate to the project directory:

   ```bash
   cd YOUR-REPOSITORY
   ```

3. Verify that Python is installed:

   ```bash
   python --version
   ```

## 🚀 Usage

Run the Python file from your terminal:

```bash
python fibonacci.py
```

The program generates and prints the first 10 Fibonacci numbers by default.

To generate a different number of terms, change the argument passed to the `fibonacci()` function in `fibonacci.py`.

## 💡 Example

**Code:**

```python
def fibonacci(n):
    a, b = 0, 1
    series = []

    for _ in range(n):
        series.append(a)
        a, b = b, a + b

    return series

print(fibonacci(10))
```

**Output:**

```text
[0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

## 📂 Project Structure

```text
fibonacci-project/
│
├── fibonacci.py
└── README.md
```

## 📄 License

This project is available under the MIT License. If you choose this license, add a `LICENSE` file containing the full MIT License text to your repository.

---

Made with ❤️ using Python.
