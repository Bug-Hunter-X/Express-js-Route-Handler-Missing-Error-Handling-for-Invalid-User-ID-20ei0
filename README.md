# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  the lack of proper error handling for invalid or missing parameters.

The `bug.js` file shows a route that attempts to fetch a user by ID.  However, it doesn't handle cases where the ID is not a number or the user does not exist, leading to potential crashes or 500 errors.

The `bugSolution.js` file provides a corrected version with comprehensive error handling.