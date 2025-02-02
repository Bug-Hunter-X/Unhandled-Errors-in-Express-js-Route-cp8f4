# Unhandled Errors in Express.js Route

This repository demonstrates a common error in Express.js applications: unhandled errors during database operations. The `/users/:id` route retrieves user data from a database but lacks proper error handling.  This leads to server crashes when an invalid user ID is requested.

The `bug.js` file contains the faulty code, and `bugSolution.js` shows how to fix it using try-catch blocks and proper error handling.