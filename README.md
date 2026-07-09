# Tkinter Calculator

A simple calculator application built using **Python** and **Tkinter**. The calculator provides a graphical user interface (GUI) capable of performing basic arithmetic operations along with a few scientific operations.

## Features

* User-friendly GUI
* Addition (+)
* Subtraction (-)
* Multiplication (*)
* Division (/)
* Modulus (%)
* Exponent (**)
* Square operation (x²)
* Multiply by π (×3.14)
* Parentheses support
* Backspace button
* Clear (AC) button
* Error handling for invalid expressions

## Technologies Used

* Python 3
* Tkinter
* AST Module

## Project Structure

```
tkinter-calculator/
│
├── calculator.py
├── README.md
├── requirements.txt
├── LICENSE
├── .gitignore
├── screenshots/
│   └── calculator.png
└── assets/
```

## Installation

Clone the repository.

```bash
git clone https://github.com/Anikgarg05/tkinter-calculator.git
```

Move into the project directory.

```bash
cd tkinter-calculator
```

Run the application.

```bash
python calculator.py
```

## How It Works

The calculator creates a GUI using Tkinter. Button presses insert numbers and operators into the input field. The entered mathematical expression is safely parsed using Python's AST module before evaluation. Results are displayed instantly, and invalid expressions are handled gracefully by displaying an error message.

## Future Improvements

* Scientific calculator mode
* Keyboard support
* Dark mode
* Calculation history
* Memory functions (M+, M-, MR, MC)
* Square root and trigonometric functions
* Better UI styling

## Author

Anik Garg

## License

This project is licensed under the MIT License.
