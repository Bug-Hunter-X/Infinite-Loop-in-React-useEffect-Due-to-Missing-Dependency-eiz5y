# React useEffect Infinite Loop Bug

This repository demonstrates a common React bug involving the `useEffect` hook.  Incorrectly specifying dependencies leads to an infinite render loop. The bug and its solution are shown in separate JavaScript files.

**Bug:** The original `MyComponent` has an incorrect dependency array for `useEffect`, causing it to run repeatedly and lead to an infinite loop.

**Solution:** The `bugSolution.js` file demonstrates how adding the `count` variable to the dependency array resolves the problem.

This example highlights the importance of correctly specifying dependencies in `useEffect` to avoid performance issues and unexpected behavior.