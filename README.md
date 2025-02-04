# JavaScript Null Handling Bug

This repository demonstrates a common JavaScript bug related to null value handling and provides a solution.

## Bug Description
The `foo` function is intended to add two numbers.  However, it exhibits unexpected behavior when one or both inputs are null because of loose comparison (==).  Strict equality (===) provides the correct results. 

## Solution
The solution replaces loose equality (==) with strict equality (===) to accurately handle null inputs.

## How to Run
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` to see the buggy and fixed code respectively.
3. Run the JavaScript files in your preferred environment (e.g., Node.js, browser's console).