# Create a new project directory
mkdir hello_calculator && cd hello_calculator

# Create the Python script
cat > hello_calculator.py <<EOF
# Print a welcome message
print("Hello, World!")

# Define two numbers
a = 10
b = 3

# Perform all basic arithmetic operations
print("Addition:", a, "+", b, "=", a + b)
print("Subtraction:", a, "-", b, "=", a - b)
print("Multiplication:", a, "*", b, "=", a * b)
print("Division:", a, "/", b, "=", a / b)
print("Floor Division:", a, "//", b, "=", a // b)
print("Modulus:", a, "%", b, "=", a % b)
print("Exponentiation:", a, "**", b, "=", a ** b)
EOF

# Create the README.md file
cat > README.md <<EOF
# Hello World & Basic Calculator 🧮

This is a beginner-friendly Python script that starts by printing **"Hello, World!"** and then demonstrates all basic arithmetic operations using two numbers.

## 🔧 What It Does

The script performs the following:

- ✅ Prints "Hello, World!"
- ➕ Addition
- ➖ Subtraction
- ✖️ Multiplication
- ➗ Division
- 🧮 Floor Division
- 🔁 Modulus
- ⚡ Exponentiation

## 🧠 Example Output

\`\`\`
Hello, World!
Addition: 10 + 3 = 13
Subtraction: 10 - 3 = 7
Multiplication: 10 * 3 = 30
Division: 10 / 3 = 3.333...
Floor Division: 10 // 3 = 3
Modulus: 10 % 3 = 1
Exponentiation: 10 ** 3 = 1000
\`\`\`

## 🚀 How to Run

1. Make sure you have Python installed.
2. In this directory, run:

\`\`\`bash
python hello_calculator.py
\`\`\`

---

Happy Coding! 😄
EOF

# Show success message
echo "✅ Project created. Run it using: python hello_calculator.py"
