🖩 Simple Calculator

🖥️ display Element Access
The const display = document.getElementById("display"); line connects the JavaScript logic with the calculator's display field in the HTML. This ensures that any updates, inputs, or results are shown on the screen.

✏️ Append Input to Display
The appendToDisplay(input) function adds the user's input to the calculator's display. Every button press appends the corresponding value (like numbers or operators) to the current display content.

🪄 This function allows seamless entry of multi-digit numbers or complex expressions.
🧹 Clear Display
The clearDisplay() function wipes the display clean, resetting it to an empty state.

🗑️ A quick and easy way to start fresh with a single button press.
🤖 Perform Calculation
The calculate() function evaluates the mathematical expression entered by the user and updates the display with the result.

✅ Success: If the expression is valid, the result is displayed instantly.
⚠️ Error Handling: If the input is invalid (e.g., unmatched parentheses or unsupported syntax), the display shows "Error," ensuring clarity and user feedback. 
