# Secure it!

Fork this repository and solve the following problem.
---

You are tasked with implementing a function that continuously calls an asynchronous operation until it encounters a rejection.

Your tasks:

You are given an in-built function asyncOperation that returns a Promise that resolves with a success message or rejects with an error message.  
You need to repeatedly call this function until it rejects the returned promise.  
Make sure to print the resolved or rejected messages on the console.

## Input
The first line of input contains a positive number specifying the number of maximum retries, for which the given function asyncOperation will keep resolving the returned promise.

Example Input:
2

## Output
The message fetched from the API

Example Output:
You can use this API 1 more time(s).  
You can use this API 0 more time(s).  
You can no longer use this API.
```
