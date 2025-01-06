# Uncommon HTML Error: Accessing Non-Existent Properties

This repository demonstrates an uncommon error in HTML: attempting to access a non-existent property of an element.  The bug showcases the importance of proper error handling and understanding the properties available on HTML elements.

## Bug Description

The `bug.html` file contains JavaScript code that attempts to access a non-existent property of a div element. This results in a JavaScript error. The other error is caused by accessing an element using the wrong tag name.  This is a common mistake that may easily go unnoticed during development.

## Solution

The `bugSolution.html` file provides a corrected version of the code. It includes error handling to gracefully manage cases where a property might not exist and corrects the wrong tag name usage.   It demonstrates best practices to prevent unexpected behavior during execution.