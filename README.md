# React useEffect with setInterval memory leak

This example demonstrates a common error in React where setInterval is used within a useEffect hook without proper cleanup.  This can lead to memory leaks and unexpected behavior. 

The `bug.js` file contains the problematic code, while `bugSolution.js` provides the corrected version using `useRef` to ensure the latest `setCount` function is used.