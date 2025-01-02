# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common error in JavaScript: attempting to access the 'length' property of an undefined variable.  The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

The original code fails when an undefined value is passed to the function because it attempts to access the `length` property of undefined, resulting in a `TypeError`.

The solution handles the undefined case explicitly, preventing the error.