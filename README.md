# Unhandled Promise Rejection and Uncaught Exception in Express.js

This repository demonstrates a common error in Node.js asynchronous programming within an Express.js application: unhandled promise rejections and uncaught exceptions.

The `bug.js` file showcases a scenario where an asynchronous operation might throw an error, leaving the application vulnerable to crashes if not handled properly.

The `bugSolution.js` file provides a solution illustrating how to gracefully handle such errors using try-catch blocks and proper promise handling. This ensures the application continues to function even during unexpected situations. 