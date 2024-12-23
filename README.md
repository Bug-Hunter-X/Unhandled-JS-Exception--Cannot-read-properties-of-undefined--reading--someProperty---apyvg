# React Native: Accessing State Before Assignment

This repository demonstrates a common React Native error: attempting to access a state variable or prop before it has been assigned a value.  This often happens with asynchronous operations (e.g., fetching data from an API).  The error usually manifests as `Unhandled JS Exception: Cannot read properties of undefined (reading 'someProperty')`.

The `bug.js` file shows the erroneous code, while `bugSolution.js` provides the corrected version, illustrating how to handle asynchronous data fetching correctly and prevent this type of error.