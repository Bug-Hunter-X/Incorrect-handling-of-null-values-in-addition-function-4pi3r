# Incorrect handling of null values in addition function
This repository contains a JavaScript function that incorrectly handles null values when adding two numbers. The function should return the sum of the two numbers, even if one or both are null. However, the current implementation returns 0 if either of the numbers is null.

## Bug
The bug is located in the `foo` function. This function takes two arguments, `a` and `b`, and returns their sum. However, if either `a` or `b` is null, the function returns 0 instead of adding the numbers together. This is incorrect behavior.

## Solution
The solution is to handle the null values appropriately. One way to do this is to treat null values as 0. Then, the function will return the sum of the two numbers, whether they are null or not.

## How to run the code
1. Clone this repository.
2. Open the `bug.js` and `bugSolution.js` files in a text editor.
3. Run the `bug.js` file to see the incorrect behavior. 
4. Run the `bugSolution.js` file to see the correct behavior.