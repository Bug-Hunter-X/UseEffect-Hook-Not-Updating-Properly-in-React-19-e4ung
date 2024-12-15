# React 19 useEffect Hook Bug

This repository demonstrates a common bug related to the `useEffect` hook in React 19 and its solution.

## Bug Description

The `useEffect` hook is not updating correctly when the dependency array is missing or incorrect. This leads to stale closures and unexpected behavior.

## Solution

Ensure that the `useEffect` hook has the correct dependency array. Include all variables used within the effect that are not declared within the effect itself.

## How to reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the console logs and the unexpected behavior.
5. Check the `bugSolution.js` file for the corrected code.