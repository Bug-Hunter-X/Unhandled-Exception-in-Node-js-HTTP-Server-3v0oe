# Unhandled Exception in Node.js HTTP Server

This repository demonstrates a common error in Node.js applications: unhandled exceptions in HTTP servers.  The `bug.js` file shows a server that lacks proper error handling, which can lead to unexpected crashes. The `bugSolution.js` file provides a solution that gracefully handles errors and prevents crashes.

## Bug
The original code fails to catch and handle potential errors that might occur during request processing. This leads to the server crashing and becoming unavailable.

## Solution
The solution adds error handling using a `try...catch` block to gracefully manage exceptions.  This ensures that even if errors occur, the server remains operational and provides a more robust user experience.