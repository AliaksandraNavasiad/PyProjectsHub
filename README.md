# PyProjectsHub
"A collection of Python projects and scripts, from beginner-friendly experiments to advanced creations. Welcome to the hub of innovation and learning!

**Both the terminal-based (Version 01) and GUI-based (Version 02) calculators are included in this repository. Choose the version that best suits your needs!**

# Basic Calculator (Version 02) 

**File:** `gui_basic_calculator.ipynb`

This is an enhanced **Python-based calculator** that now features a user-friendly graphical user interface (GUI), making calculations simpler and more intuitive.

## Features
- Designed GUI built with **Tkinter**, including:
  1. Stylish, customizable title bar with drag-and-drop functionality.
  2. Interactive input fields with placeholder text for better usability.
  3. Error handling for invalid inputs and division by zero through popup dialogs.
  4. Clear display area for results with a polished look.
  5. Button-based operations for easy and quick calculations.
- Supports four basic operations:
  1. Addition
  2. Subtraction
  3. Multiplication
  4. Division

## How to Use
1. Clone or download this repository to your local system.
2. Run the `basic_calculator_gui.py` file using Python 3.x.
3. Perform the following:
   - Enter the first number in the input box labeled "Enter first number."
   - Enter the second number in the input box labeled "Enter second number."
   - Click one of the operation buttons (`+`, `−`, `×`, or `÷`) to calculate the result.
   - View the result displayed in the "Result" section.

## Requirements
- Python 3.x
- Tkinter (included by default in most Python distributions)

## Example Usage
1. Enter `25` as the first number.
2. Enter `5` as the second number.
3. Click on the `÷` button.
4. The result `5.0` will be displayed in the "Result" area. If you try dividing by zero, an error message will pop up.

## Screenshots
Below are screenshots of the Basic Calculator's GUI in action:
- **The GUI's main interface and result display.**
![image](https://github.com/user-attachments/assets/22c4de46-902d-408d-a915-6e389cadd619)
![image](https://github.com/user-attachments/assets/398fedf8-86ac-4688-99ab-2677b1628165)

## Future Improvements
- Enhance the design with more themes and color schemes.

---
# Basic Calculator (Version 01)

**File:** `basic_calculator.ipynb`

This is a simple **Python-based calculator** that allows users to perform basic mathematical operations interactively through the terminal.

## Features
- Supports four operations:
  1. Addition
  2. Subtraction
  3. Multiplication
  4. Division
- Handles division by zero gracefully with a friendly message.
- Allows users to perform multiple calculations in a single session.
- Provides input validation to ensure smooth user interaction.

## How to Use
1. Clone or download this repository to your local system.
2. Run the Jupyter Notebook file (`basic_calculator.ipynb`) in any environment that supports Jupyter (e.g., Jupyter Notebook, JupyterLab, VS Code).
3. Follow the prompts to:
   - Select an operation (1 for addition, 2 for subtraction, etc.).
   - Enter the numbers you’d like to calculate.
   - Perform as many calculations as you'd like in the same session.

## Example Usage
Here’s an example interaction:

Select the operation you'd like to perform (choose number, e.g.: 1): 1. add 2. subtract 3. multiply 4. divide
Enter an operation (1, 2, 3, or 4): 4 Enter the first number (a): 4 Enter the second number (b): 0 Result of Division: Division by zero is not possible. Please try again.
Do you want to perform another calculation? (yes/no): yes

## Requirements
- Python 3.x
- Jupyter Notebook

## Future Improvements
- Add more advanced operations (e.g., exponentiation, square roots).
- Create a graphical user interface (GUI) for improved usability.~~ **(Done in Version 02!)**
- Integrate with external libraries like NumPy for extended functionality.

## License
This project is licensed under the [MIT License](LICENSE).
