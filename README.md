# Incorrect DOM Manipulation in HTML

This repository demonstrates a common mistake when working with the Document Object Model (DOM) in HTML. The bug involves incorrectly trying to access and modify the content of an HTML element using its ID directly without utilizing proper DOM methods.

## Bug Description
The bug arises from trying to directly change the text content of a div element by using the ID as a variable, which is not how DOM manipulation works in JavaScript. This usually results in a runtime error.

## How to reproduce the error
1. Clone the repository
2. Open `bug.html` in your browser.
3. Observe the console error message and the fact that the text of the div is not changed as expected.

## Solution
The provided `bugSolution.html` file shows the corrected method: using `document.getElementById()` to get a reference to the div element and then manipulating its `textContent` property.