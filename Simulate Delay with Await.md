# Simulate Delay with Await

Fork this repository and solve the following problem.
---

You are given a function solve(userName, ms) that takes two parameters:

userName: a string representing a name  
ms: an integer representing a delay in milliseconds  

Your task is to implement asynchronous logic inside the given solve function using only async / await.

## Requirements

Inside solve(userName, ms), you must:

Implement a function delay(ms) that:

Returns a Promise  
Resolves after ms milliseconds  
Resolves with the value userName  
Uses setTimeout internally  

Implement an async function getNameAfterDelay() that:

Does not take any parameters  
Calls await delay(ms)  
Stores the resolved value in a variable  
Returns that value  

Call getNameAfterDelay() using await inside solve  
Print the returned value using console.log  

Ensure solve is declared as async  

## Input
You will be given two lines of input:  
A name (string) on the first line  
A delay in milliseconds (integer) on the second line  

Example Input:
Carol  
2000  

## Output
The name must be printed exactly as received.

Example Output:
Carol  

## Constraints
getNameAfterDelay must not accept any parameters  
userName and ms must be accessed using closure  
You must not use .then() anywhere in the solution  
Only async / await is allowed for asynchronous handling  
Do not modify the function signature of solve(userName, ms)
