# Compiler Design Simulator

*An interactive web based compiler simulator that visualizes all six major phases of a compiler, allowing students and developers to understand the complete compilation process step by step.*

---

## 📌 Table of Contents

- [Overview](#overview)
- [Project Objective](#project-objective)
- [Features](#features)
- [Compiler Phases](#compiler-phases)
- [Technology Stack](#technology-stack)
- [System Architecture](#system-architecture)
- [Application Screenshots](#application-screenshots)
- [Supported Language Features](#supported-language-features)
- [Error Handling](#error-handling)
- [Testing](#testing)
- [Future Improvements](#future-improvements)
- [Conclusion](#conclusion)
- [Role & Contribution](#role--contribution)
- [Author](#author)

---

## 📖 Overview

The **Compiler Design Simulator** is a browser-based educational application developed to demonstrate the complete compilation process through an interactive graphical interface.

The simulator accepts source code written in a simplified C like language and processes it through all six classical compiler phases. Users can execute each phase individually or run the full pipeline while observing intermediate outputs such as tokens, syntax trees, symbol tables, intermediate code, optimized code, and pseudo machine code.

This project was developed as part of the **Compiler Construction course** to provide a practical understanding of compiler design concepts.

---

## 🎯 Project Objective

The main objectives of this project are:

- Simulate all six standard phases of a compiler
- Visualize the compilation process step-by-step
- Generate intermediate outputs at every stage
- Provide educational insight into compiler internals
- Detect lexical, syntax, and semantic errors
- Demonstrate code optimization techniques
- Generate pseudo machine code from source programs

---

## ✨ Features

### ⚙️ Interactive Compilation
- Run All functionality
- Step by step execution mode
- Real-time phase status indicators
- Visual compilation pipeline
- Live output generation

### 🖥️ User Interface
- Modern responsive web interface
- Source code editor with line numbers
- Six dedicated output panels
- Dark theme design
- Sample program templates

### 📊 Educational Visualization
- Color-coded token streams
- Abstract Syntax Tree (AST)
- Symbol table generation
- Three Address Code (3AC)
- Optimization annotations
- Pseudo-RISC assembly generation

---

## 🔄 Compiler Phases

### 1️⃣ Lexical Analysis
Converts source code into tokens:

- Keywords
- Identifiers
- Literals
- Operators
- Symbols

**Output:**
- Token stream
- Token statistics

---

### 2️⃣ Syntax Analysis
Builds an Abstract Syntax Tree (AST) using parsing techniques.

**Output:**
- Program structure tree
- Statement hierarchy
- Expression trees

---

### 3️⃣ Semantic Analysis
Performs semantic checks and builds symbol table.

**Checks:**
- Variable declarations
- Duplicate declarations
- Undeclared variables
- Initialization status

**Output:**
- Symbol table
- Warnings and errors

---

### 4️⃣ Intermediate Code Generation
Converts code into Three Address Code (3AC).

**Output:**
- Temporary variables
- Labels
- Conditional jumps
- 3AC instructions

---

### 5️⃣ Code Optimization
Applies optimization techniques:

- Constant folding
- Constant propagation
- Algebraic simplification

**Output:**
- Optimized intermediate code
- Optimization notes

---

### 6️⃣ Code Generation
Generates pseudo assembly code.

**Output:**
- Data segment
- Text segment
- Register allocation
- Assembly instructions

---

## 💻 Supported Language Features

### Data Types
- int
- float
- string
- char
- bool

### Statements
- Variable declarations
- Assignments
- Arithmetic expressions
- If-else statements
- While loops

### Operators
- Arithmetic (+, -, *, /)
- Relational operators
- Logical operators

---

## 🧰 Technology Stack

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla JS)

### UI Design
- CSS Variables
- Responsive layout
- Dark theme interface

### Tools
- GitHub
- VS Code

---

## 🏗️ System Architecture
Source Code
↓
Lexical Analysis
↓
Syntax Analysis
↓
Semantic Analysis
↓
Intermediate Code Generation
↓
Code Optimization
↓
Code Generation
↓
Pseudo Machine Code

---

## 📸 Application Screenshots

> Add your project screenshots here:

- Compiler Interface
- Lexer Output
- AST Visualization
- Semantic Analysis
- Three Address Code
- Optimization View
- Target Code Generation

---

## ⚠️ Error Handling

The simulator detects:

- Invalid tokens
- Duplicate variables
- Undeclared variables
- Uninitialized variables
- Semantic violations

All errors are displayed with clear messages.

---

## 🧪 Testing

| Test Case              | Description                  | Result |
|----------------------|------------------------------|--------|
| Arithmetic Expressions | Full pipeline execution     | PASS   |
| If-Else Statements     | Conditional compilation     | PASS   |
| While Loops            | Loop handling               | PASS   |
| Duplicate Variables    | Semantic error detection    | PASS   |
| Undeclared Variables   | Validation checks           | PASS   |
| Constant Folding       | Optimization testing        | PASS   |
| Complex Programs       | Full compilation pipeline   | PASS   |

---

## 🚀 Future Improvements

- Function declarations & calls
- Array support
- Pointer support
- Advanced type checking
- Global data flow analysis
- Register allocation optimization
- Assembly export feature

---

## 🎓 Conclusion

The **Compiler Design Simulator** successfully demonstrates the complete compiler pipeline in an interactive and educational way.

It bridges the gap between theory and practice by showing how source code transforms into optimized machine-level instructions.

---

## 👨‍💻 Role & Contribution

### My Contributions
- Compiler architecture design
- Lexer implementation
- Parser & AST design
- Semantic analysis module
- Three address code generation
- Optimization module
- Code generation logic
- UI design
- Testing & debugging
- Documentation

---

## Author
**Mian Shakar Afzal**

[LinkedIn](https://www.linkedin.com/in/mian-shakar-afzal-959b443a8/) | [GitHub](https://github.com/SHAKAR-AFZAL) | [Email](mailto:mianshakarafzal@gmail.com)
