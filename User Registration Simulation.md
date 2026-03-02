# User Registration Simulation

Fork this repository and solve the following problem.
---

Write an asynchronous function register that takes a single parameter user:

user: an object with two properties:  
     username: a string representing the user's name.  
     password: a string representing the user's password.

The function must do the following:

Call a provided asynchronous function registerUser(user) which returns a Promise  

Use async/await along with a try/catch block to handle the promise returned by registerUser.  

In the try block, wait for the response and log it using console.log().  

In the catch block, catch any error thrown and log the error using console.log().

Note: You do not need to implement registerUser — it will be provided in the test environment.

## Input
A user object having username and password.

Example Input:
{ "username": "anonymous", "password": "123456" }

## Output
Respective message

Example Output:
User registered successfully
