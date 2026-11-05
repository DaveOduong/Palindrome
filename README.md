# PALINDROME CHECKER

## 1. Project Description
Palindrome Checker is a simple web application developed using HTML and JavaScript. It allows users to enter a word or text and determine whether it reads the same forward and backward.

## 2. Features
- Accepts user input through a text field.
- Reverses the entered text.
- Compares the original text with its reversed version.
- Displays an alert indicating whether the text is a palindrome.
- Clears the input field after checking.

## 3. Technologies Used
- **HTML:** Creates the webpage structure, input field, and button.
- **JavaScript:** Handles text reversal, comparison, and alert messages.

## 4. Project Files
- `index.html` – Contains the webpage structure and user input elements.
- `script.js` – Contains the functions used to reverse and check the entered text.

## 5. How to Run
1. Save the HTML code as `index.html`.
2. Save the JavaScript code as `script.js`.
3. Place both files in the same folder.
4. Open `index.html` in a web browser.
5. Enter a word or text and click **Check**.

## 6. JavaScript Functions

**reverseString(str)**

Uses `split()`, `reverse()`, and `join()` to reverse the characters in a string.

**check()**

- Retrieves the user's input.
- Calls `reverseString()` to reverse the text.
- Compares the original text with the reversed text.
- Displays an appropriate alert message.
- Clears the input field.

## 7. Concepts Demonstrated
- DOM manipulation using `getElementById()`.
- Functions and parameters.
- String manipulation.
- Conditional statements (`if/else`).
- Event handling using `onclick`.
- JavaScript alerts.

## 8. Conclusion
This project demonstrates basic JavaScript programming concepts, particularly string manipulation, functions, conditional statements, and interaction between HTML and JavaScript.
