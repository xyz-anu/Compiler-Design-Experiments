# Compiler Design - Experiments and Practical Implementations

---

## Welcome to My Compiler Design Explorations!

This repository contains a collection of hands-on experiments and projects completed as part of the **Compiler Design** course. Through practical implementations in C++ and related tools, I explored fundamental compiler modules including lexical analysis, syntax analysis, semantic analysis, intermediate code generation, and control flow management.

Whether this is your first exposure to compilers or an attempt to deepen understanding, this repository guides through key compiler components accompanied by sample code and explanations.

---

# Table of Contents

- [About Compiler Design](#about-compiler-design)  
- [Experiment Summaries](#experiment-summaries)  
- [Key Concepts](#key-concepts)  
- [How to Use This Repository](#how-to-use-this-repository)  
- [Contact](#contact)  

---

## About Compiler Design

A **compiler** is a software that translates high-level programming code written by humans into machine-readable code (like assembly or binary). The compilation process includes multiple phases such as lexical analysis, parsing, semantic analysis, optimization, and code generation.

This course focused on implementing major components of a compiler, illustrating how programming languages are processed internally—from reading source code to generating intermediate and final code suitable for execution.

---

## Experiment Summaries

### 1. File Handling to Count Lines, Words, Operators, and Special Characters

- Implemented a C++ program to read a source code file and count its **lines**, **words**, **operators** (such as +, -, *, /), and **special characters**.
- This mimics part of the **lexical analysis** phase where the source code is tokenized into meaningful symbols.

---

### 2. Elimination of Single-line and Multi-line Comments

- Developed a program to **remove comments** (both single-line `//` and multi-line `/* ... */`) from source code.
- This is a preprocessing step in compilation that cleans the code for further processing.

---

### 3. Lexical Analysis Implementation

- Built a simplified **lexer** that reads a C++ code file and identifies **keywords**, **identifiers**, **special symbols**, and **operators**.
- Essential for breaking down source code into tokens for syntax analysis.

---

### 4. Elimination of Left Recursion and Left Factoring

- Created a program to detect and eliminate **left recursion** and perform **left factoring** on grammar rules.
- These grammar transformations are necessary for creating parsers like **LL(1)** parsers that cannot handle left recursion directly.

---

### 5. Implementation of First and Follow Functions for LL(1) Grammar

- Implemented algorithms to compute **First** and **Follow** sets for a given context-free grammar.
- These sets help build the **predictive parsing table** for efficient top-down parsing.

---

### 6. Working of Top-Down Parsers (Predictive Parsing)

- Developed a program demonstrating a **top-down parser** using parsing tables constructed from First and Follow sets.
- It parses input strings to verify if they belong to a language defined by the grammar.

---

### 7. Implementation of LR(0) Parser (Bottom-Up Parsing)

- Created an **LR(0) parser** implementation that performs **shift-reduce parsing** to analyze strings.
- LR parsers are powerful bottom-up parsers that handle a broad class of grammars suitable for real-world programming languages.

---

### 8. Annotated Abstract Syntax Tree (AST) Construction

- Built data structures representing an **annotated syntax tree** for expressions with assignments and binary operations.
- ASTs are critical data structures representing program structure for further semantic analysis and optimization.

---

### 9. Intermediate Code Generation Using Three Address Code (TAC)

- Implemented a simple generator for **Three Address Code**, an intermediate representation between source code and machine code.
- TAC breaks complex expressions into simpler instructions with temporary variables, facilitating easier optimization and code generation.

---

### 10. Control Flow Graph (CFG) Demonstration

- Implemented a **Control Flow Graph** representing basic blocks and their execution flow in a program.
- CFGs are central to optimization and analysis phases in compilers by modeling the execution paths within programs.

---

## Key Concepts Explained

- **Lexical Analysis:** The first compile phase, converting raw source code into tokens.
- **Comments Removal:** Preprocessing to eliminate unnecessary parts for compilation.
- **Parsing & Grammar Transformations:** Techniques like **left recursion elimination** and **left factoring** prepare grammars for parser compatibility.
- **First and Follow Sets:** Core sets used to guide predictive parsing decisions.
- **Top-Down Parsing:** Parsing input from the start symbol downward using grammar rules.
- **Bottom-Up Parsing (LR Parsers):** Parsing by constructing parse trees from leaves (input symbols) upwards.
- **Abstract Syntax Trees (AST):** Hierarchical tree representations of program statements and expressions.
- **Intermediate Code (TAC):** A simplified, three-address code form facilitating translation and optimization.
- **Control Flow Graph (CFG):** A graph of basic blocks and control flow, aiding in program analysis.

---

## How to Use This Repository

1. **Explore each experiment folder** for source files and comments explaining the logic.  
2. **Compile and run C++ programs** using any standard C++ compiler (like g++).  
3. Use these programs as educational tools to understand how each compiler phase works.  
4. Modify grammar inputs and source files to experiment with different examples.  

---

## Contact

- **Developer:** Anushka Harshavadan Nevgi  
- **LinkedIn:** [Anushka Nevgi(https://www.linkedin.com/in/anushka-nevgi/)]  
- **Email:** anushkanevgi2910@gmail.com  

---

Thank you for exploring my Compiler Design repository!  
Feel free to fork, star, or open issues with questions or suggestions.

---

*Happy compiling!*  
**- Anushka H. Nevgi**

