# React Native Null Pointer Exception

This repository demonstrates a common error in React Native applications: attempting to access properties of an object before verifying its existence. This often happens when dealing with asynchronous data fetching or user input, where the object might be null or undefined. The example shows the incorrect code and the solution.

## Bug
The provided `bug.js` file contains code that attempts to access the `name` property of a `userProfile` object without checking if the `userProfile` object itself is defined.

## Solution
The `bugSolution.js` file demonstrates the corrected code, incorporating null and undefined checks to prevent runtime errors.  This safeguards against unexpected null values and ensures the app remains stable.  Best practices involve using optional chaining (?.) or the logical AND operator (&&) for concise error handling.