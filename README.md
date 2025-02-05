# Node.js Server Port Already in Use

This repository demonstrates a common error encountered when developing Node.js applications: the failure to start a server because the specified port is already in use.

The `bug.js` file contains the problematic code.  The `bugSolution.js` file provides a solution that handles this situation gracefully.

## How to Reproduce

1. Clone this repository.
2. Run `node bug.js`.  This will likely fail if port 8080 is already in use.
3. Run `node bugSolution.js`. This will handle the port already in use more gracefully.