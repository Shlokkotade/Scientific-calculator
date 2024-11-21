Scientific Calculator By Using Python Programming
Overview
This project involves the creation of a Scientific Calculator using Python's tkinter library for the graphical user interface (GUI) and math module for scientific functions. The calculator performs basic arithmetic operations as well as advanced scientific operations like trigonometric functions, square roots, logarithms, factorials, and more.

Features
Basic Arithmetic Operations: Addition, subtraction, multiplication, and division.
Scientific Operations: Includes operations such as square root, trigonometric functions (sin, cos, tan), logarithms, and more.
Advanced Functions: Functions like factorial, logarithms, square, cube, cube root, and degrees/radians conversion.
Dynamic Input & Output: Allows users to input expressions dynamically and displays results instantly.
Clear and Reset Functions: Provides options to clear the last entry or reset the entire input.
Dependencies
This project requires the following Python libraries:

tkinter (for creating the GUI)
math (for scientific calculations)
These libraries come pre-installed with Python, so no additional installation is necessary.

Installation
Make sure you have Python 3.x installed on your machine.

Copy the Python code into a .py file (e.g., scientific_calculator.py).

Run the script using the command:

bash
Copy code
python scientific_calculator.py
This will launch the scientific calculator GUI.

Code Explanation
1. Importing Libraries
python
Copy code
import tkinter
import math
tkinter: Used for the GUI.
math: Provides access to mathematical functions like sqrt, pi, sin, cos, etc.
2. Click Function
The click function handles the input and performs the necessary calculations when a button is clicked. It processes various operations based on the button clicked by the user.

3. Button Layout
The layout of buttons is created dynamically using a list of button labels (button_list). The buttons are arranged in a grid layout using the grid method.

4. GUI Setup
The GUI is initialized using tkinter.Tk(), and the window is customized with title, geometry, background color, and an entry widget to display input/output.

5. Event Handling
Each button is linked to the click function. When a user clicks a button, the corresponding value or operation is passed to the function.

6. Advanced Operations
The calculator supports operations such as:

Trigonometric Functions: cosθ, sinθ, tanθ, etc.
Logarithms: log10, ln, etc.
Factorial: x!
Exponentiation and Roots: Square, cube, x^y, cube root, etc.
Radians and Degrees Conversion: Functions to convert between radians and degrees.
Usage
Basic Calculation: Simply click the number buttons (0-9) and arithmetic operation buttons (+, -, *, /) to perform calculations.
Scientific Functions: Click on scientific function buttons like √, sinθ, cosθ, tanθ, π, and others to get advanced results.
Clear Input: Click C to delete the last character or CE to clear the entire input.
Final Result: Click = to get the result of the entered expression.
Sample Screenshots
(Include screenshots of the running calculator, if needed.)

Contributing
Feel free to fork the repository, submit issues, and open pull requests if you would like to contribute to the development or improve functionality.

License
This project is open source and available under the MIT License.
