# Unexpected 'undefined' due to hoisting in JavaScript

This repository demonstrates a common JavaScript error related to hoisting.  The code in `bug.js` attempts to log the value of a variable before it's declared.  This results in `undefined` being logged to the console. The solution in `bugSolution.js` corrects this by declaring the variable before use.

## How to reproduce

1. Clone this repository.
2. Open `bug.js` and run it in a JavaScript environment (e.g., Node.js, browser's developer console).
3. Observe the output: `undefined`.
4. Open `bugSolution.js` to see the corrected code and run it. Observe the correct output.