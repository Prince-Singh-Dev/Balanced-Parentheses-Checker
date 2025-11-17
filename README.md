# Balanced Parentheses Checker (C Language | DSA Project)

This project is a simple yet powerful implementation of a Balanced Parentheses Checker using the Stack Data Structure in C.
It validates whether an expression contains correctly balanced brackets:
(), {}, []

# 🚀 Project Overview

A balanced expression means:
Every opening bracket must have a matching closing bracket.
The brackets must close in correct order.
Expression like ({[]}) → Balanced
Expression like {[()]}} → Not Balanced
This project uses a stack (LIFO) to track opening brackets and ensures every closing bracket matches the correct type.

# 🧰 Features

Supports all bracket types: (), {}, []
Ignores numbers, letters, and mathematical operators
Works even for expressions with spaces using fgets()
Beginner-friendly C implementation
Demonstrates core DSA concepts:
Stack
Push / Pop operations
Matching pairs
Parsing

# 📘 How the Algorithm Works

Traverse the expression from left to right
If an opening bracket is found → push onto stack
If a closing bracket is found →
   -- Check if stack is empty (means extra closing bracket)
   -- Pop the top and check if it matches
At the end, if the stack is empty → Balanced
Otherwise → Not Balanced

# Project Structure 

|-- balanced_parentheses.c
|-- README.md

# 🧪 Sample Inputs & Outputs

| Input               | Output       |
| ------------------- | ------------ |
| `(5+6)-{5*4}+{A+B}` | Balanced     |
| `{A+(B*C)-[D/E]}`   | Balanced     |
| `(A+B]`             | Not Balanced |
| `{[(])}`            | Not Balanced |
| `(5+6)-{5*4}+{A+B`  | Not Balanced |

# 🛠️ How to Run
1️⃣ Compile the code
gcc balanced_parentheses.c -o checker

2️⃣ Run the program
./checker

3️⃣ Enter any expression
Example:
Enter an expression: (5+6)-{5*4}+{A+B}

# 🎯 Learning Outcomes

Implementing a Stack using arrays
Understanding LIFO behavior
Applying DSA to real parsing problems
Using fgets() for safe input
Implementing bracket matching logic

# 🌍 Real-World Applications

Compiler syntax checking
HTML/XML validation
IDE code analyzers
Expression evaluation engines
Parsing structured language formats

# 🤝 Contributing

Feel free to fork the repo, add improvements, and create pull requests!

# ⭐ Show Support

If you found this project helpful, don't forget to star ⭐ the repository!


At the end, if the stack is empty → Balanced

Otherwise → Not Balanced
