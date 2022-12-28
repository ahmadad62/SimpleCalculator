
### 4: JAVASCRIPT CALCULATOR

![JavaScript calculator project for beginners](./image/JavaScript-calculator-project-for-beginners.png)

- This code defines a Calculator class with several methods for performing various operations on numbers, such as addition, subtraction, multiplication, and division. It also has methods for clearing and deleting the current operand, as well as updating the display of the calculator.

- The Calculator class takes two parameters in its constructor: previousOperandTextElement and currentOperandTextElement, which are elements in the HTML document that will be used to display the previous operand and the current operand, respectively.

- The clear method sets the currentOperand, previousOperand, and operation properties to an empty string and undefined, respectively.

- The delete method removes the last character from the currentOperand string.

- The appendNumber method appends a given number to the currentOperand string, but only if the number is not a decimal point or if the currentOperand does not already include a decimal point.

- The chooseOperation method sets the operation property to the given operation, and sets the previousOperand property to the currentOperand. If the previousOperand is not empty, it also calls the compute method.

- The compute method performs the operation specified by the operation property on the previousOperand and currentOperand, and stores the result in the currentOperand. It then sets the operation and previousOperand properties to undefined and an empty string, respectively.

- The getDisplayNumber method takes a number and returns a string representation of the number with commas as thousand separators and with a fixed number of decimal places.

- The updateDisplay method updates the text of the previousOperandTextElement and currentOperandTextElement elements to reflect the current state of the Calculator object.

- Finally, the code sets up event listeners for various buttons in the HTML document, such as number buttons, operation buttons, and a delete button. When these buttons are clicked, the corresponding methods of the Calculator object are called, and the display is updated.