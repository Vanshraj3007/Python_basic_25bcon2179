# Factorial Calculator in Python

## 📌 Overview

This project demonstrates how to calculate the factorial of a number using Python. It uses a `for` loop to multiply all integers from `1` to the specified number and stores the result in a variable.

## 🚀 Features

- Simple and beginner-friendly Python code.
- Uses a `for` loop for iterative calculation.
- Demonstrates basic programming concepts such as variables, loops, and multiplication.
- Easy to understand and modify for different input values.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Platform:** Google Colab / Python IDE

## 📂 Code

```python
n = 5
fact = 1

for i in range(1, n + 1):
    fact = fact * i

print("Factorial of", n, "is", fact)
```

## 🧠 How It Works

1. **Initialize the number:** Set `n = 5`, the number whose factorial is to be calculated.
2. **Initialize the factorial:** Set `fact = 1` to store the result.
3. **Iterate through the numbers:** The `for` loop runs from `1` to `n`, inclusive.
4. **Calculate the factorial:** Multiply `fact` by each value of `i` in every iteration.
5. **Display the result:** Print the calculated factorial.

## ▶️ Example Output

```text
Factorial of 5 is 120
```

## 📖 Mathematical Concept

The factorial of a non-negative integer \(n\), represented as \(n!\), is the product of all positive integers from `1` to `n`.

For example:

\[
5! = 5 \times 4 \times 3 \times 2 \times 1 = 120
\]

By definition:

\[
0! = 1
\]

## ⚙️ How to Run

1. Clone or download this repository.
2. Open the Python file in your preferred code editor or Google Colab.
3. Run the program.
4. Change the value of `n` to calculate the factorial of another non-negative integer.

## 🔮 Possible Improvements

- Accept user input instead of using a fixed value.
- Add input validation for negative numbers.
- Implement factorial calculation using recursion or a built-in Python function.

## 👨‍💻 Author

**Vanshraj Singh**

## 📄 License

This project is available for educational and learning purposes. You may modify it to explore basic Python programming concepts.
