# Python Tkinter Calculator

A simple, easy-to-use graphical calculator built with Python and the Tkinter library. This project provides a clean interface for performing basic arithmetic operations.



---

## Features

* **Standard Arithmetic Operations**: Perform addition (`+`), subtraction (`-`), multiplication (`*`), and division (`/`).
* **Decimal Support**: Includes a decimal point (`.`) for calculations with floating-point numbers.
* **Clear Function**: A 'C' button to easily clear the current entry and start a new calculation.
* **User-Friendly Interface**: A clean and intuitive layout made with Tkinter's grid system.
* **Error Handling**: Displays "Error" for invalid mathematical expressions (e.g., division by zero).

---

## Requirements

* **Python 3.x**
* **Tkinter**: This library is included with most standard Python installations, so you usually do not need to install it separately.

---

## How to Run

1.  **Clone the repository or download the `calculator.py` file.**
    ```sh
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```
2.  **Navigate to the project directory** in your terminal.
3.  **Run the script** using Python:
    ```sh
    python calculator.py
    ```
    This will launch the calculator in a new window.

---

## Code Overview

* **`button_click(value)`**: Appends the clicked button's value to the entry field.
* **`evaluate()`**: Calculates the result of the expression in the entry field using Python's `eval()` function.
* **`clear()`**: Deletes all text from the entry field.

The main part of the script sets up the Tkinter root window, creates the display entry, and dynamically generates the number and operator buttons in a grid layout.
