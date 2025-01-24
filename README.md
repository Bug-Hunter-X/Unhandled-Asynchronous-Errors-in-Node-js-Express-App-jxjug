# Unhandled Asynchronous Errors in Node.js

This repository demonstrates a common issue in Node.js applications: unhandled asynchronous errors.

The `bug.js` file contains an Express.js server that simulates an asynchronous operation.  Sometimes, this operation throws an error, which is not properly caught. 

The `bugSolution.js` file shows how to fix this by using appropriate error handling techniques (try...catch blocks within the asynchronous callback or promise error handling).