# Async Login Verification

Fork this repository and solve the following problem.
---

You are building an asynchronous login verification system.

The program receives two inputs:

username  
password  

Create a function called login that returns a Promise.

Using Promises, verify the login with the following rules:

## Verification Rules

### Validate Input
If either username or password is empty → reject with "Invalid input"

### Check Credentials
If username is "admin" and password is "1234" → resolve with "Login successful"  
Otherwise → reject with "Invalid credentials"

## Input
Two lines of input provided via standard input:

username  
password  

## Output

Successful Login  
Login successful  

Failed Login  
Invalid input  
or  
Invalid credentials  

## Constraints
Use Promises only  
new Promise()  
.then()  
.catch()  

Do not use async/await  
Do not hardcode input inside logic  
Use conditional checks inside Promises  
Output must be printed using console.log()  
Program must terminate after producing output
