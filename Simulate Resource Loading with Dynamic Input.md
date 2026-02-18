# Simulate Resource Loading with Dynamic Input

Fork this repository and solve the following problem.
---

You are tasked with creating a function loadResource(resourceId) that simulates loading a resource based on the provided resourceId. The function should return a Promise that resolves with a success message after a delay, or rejects with an error message if the provided resourceId is invalid.

The function should behave as follows:

If the resourceId is a positive number (valid ID), the function should resolve with the message "Resource loaded successfully" after a simulated delay of 2 seconds.  
If the resourceId is invalid (e.g., a non-positive integer or not a number), the function should reject the Promise with the error message "Invalid resource ID".

NOTE:- If the data is a positive real number convert it to an integer.

## Input
This is a functional problem hence you don't have to take any input.

The value of resourceId will follow the given format:

ResourceId will be provided as a number.  
1 <= resourceId <= 1000 for valid resource IDs.  
If resourceId is not a valid number, treat it as invalid.

## Output
A string which follows the above format.
