# React useEffect Hook with Incorrect Dependency Array

This repository demonstrates a common error in React's `useEffect` hook: using an incorrect dependency array.  The example shows a counter component where the `useEffect` hook is intended to log the count every time it changes. However, due to an empty dependency array (`[]`), it only runs once on mount and doesn't reflect subsequent count updates. This results in the log only showing the initial count.

The `bug.js` file shows the problematic code, and `bugSolution.js` provides the corrected version with the correct dependency array.