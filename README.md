# React 19 useEffect Infinite Loop Bug

This repository demonstrates a common error in React 19's `useEffect` hook that can lead to an infinite loop. The bug arises from an incorrect dependency array, causing the effect to re-run continuously. The solution shows how to correctly specify the dependency array to resolve the issue.

## Bug
The `bug.js` file contains the buggy code. The `useEffect` hook lacks proper dependency management, leading to unintended re-renders and an infinite loop.

## Solution
The `bugSolution.js` file provides the corrected code. The dependency array is now correctly specified, fixing the infinite loop.

## How to Reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Observe the console logs and the component's behavior.