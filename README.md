# aid_tech_calculator
I have created a simple calculator project using HTML, CSS, and JavaScript. 
The project consists of three files: `index.html`, `index.css`, and `index.js`.

In the `index.html` file, I have defined the structure of the calculator using HTML elements such as `<div>`, `<button>`, and `<input>`. 
The `<link>` tag is used to import the CSS file, `index.css`, which contains the styling for the calculator. 
The `<script>` tag is used to import the JavaScript file, `index.js`, which contains the logic for the calculator.

The `index.css` file includes CSS styles for various elements of the calculator such as the body, calculator container, input box, buttons, and operators. 
It also imports the 'Poppins' font from Google Fonts.

The `index.js` file contains the JavaScript code that adds functionality to the calculator. 
It retrieves the input box element using `getElementById` and adds event listeners to all the buttons. 
When a button is clicked, it performs the corresponding operation based on the button's value. For example, if the button value is "=", it evaluates the string expression using `eval` and displays the result in the input box. 
If the button value is "AC", it clears the input box, and if the button value is "DEL", it deletes the last character from the input box. 
Otherwise, it appends the button value to the string expression.

Overall, your project creates a functional calculator with basic arithmetic operations using HTML, CSS, and JavaScript.
