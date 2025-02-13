# Unhandled Error in Express.js Route Handler

This repository demonstrates a common error in Express.js route handlers: the lack of proper error handling for invalid input.

The `bug.js` file contains code with a vulnerable route that fails to handle cases where the user ID is not a valid number.  This can result in unexpected application behavior or crashes.

The `bugSolution.js` file provides a corrected version with comprehensive error handling, demonstrating best practices for handling potential errors gracefully.