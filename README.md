# 🧮 C Scientific Calculator

A feature-rich, console-based scientific calculator implemented in **C**. Designed with modular functions, robust input validation, and support for continuous sequential calculations.

## 🚀 Key Features

* **Basic Arithmetic Operations:** Supports Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/`), Power (`^`), and Modulo (`%`).
* **Unary Functions:** 
  * Square Root (`q`)
  * Natural Logarithm - ln (`l`)
  * Logarithm Base 10 - log10 (`L`)
  * Reciprocal - 1/x (`r`)
  * Absolute Value (`a`)
* **Trigonometric Functions:** Supports Sine (`s`), Cosine (`c`), and Tangent (`t`) with flexible angle modes for both **Degrees (`d`)** and **Radians (`r`)**.
* **Continuous Calculation Loop:** Allows users to perform sequential operations on the current result until terminated.
* **Error Handling:** Built-in safeguards against division by zero, negative square roots, undefined logarithms, and invalid inputs.

## 📂 Code Architecture & Functions
* `main()`: Manages the continuous input-output loop and state updates.
* `print_guide()`: Displays the interactive user manual and operation syntax at startup.
* `unary_func()`: Handles single-operand mathematical calculations with domain validation.
* `trigo_func()`: Handles trigonometric operations and unit conversions.
* `power_mod_func()`: Handles exponential and modulo operations.
* `simple_func()`: Executes standard binary arithmetic.

## 🛠️ How to Run

1. Make sure you have a C compiler installed (such as GCC).
2. Clone the repository or download the source file.
3. Compile and execute the program using your terminal:
   ```bash
   gcc scientific-calculator.c -o calculator -lm
   ./calculator
