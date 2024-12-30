# React Native useRef Hook Error on Unmount

This repository demonstrates a common error encountered when using the `useRef` hook in React Native. The error, `Cannot read properties of undefined (reading 'current')`, arises when a component unmounts before a callback function referencing the ref is executed. This often happens due to quick navigation away from the screen or race conditions.

The `bug.js` file contains the buggy code that triggers the error.  The solution, which addresses the unmounting issue using cleanup functions, is present in `bugSolution.js`.