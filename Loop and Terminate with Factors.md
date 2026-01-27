# Loop and Terminate with Factors

Fork this repository and solve the following problem.
---

Write a JavaScript program that iterates numbers starting from 1 up to a number given in input, which is stored as variable: N.  
You are also given two numbers A and B. For each number in the loop, print output based on the rules below:

If the number is divisible by neither A nor B, print the number itself.  
If the number is divisible by both A and B, print "BothFactor" and stop the loop immediately.  
If the number is divisible by A only (divisible by A but not by B), print "A_Factor".  
If the number is divisible by B only (divisible by B but not by A), print "B_Factor".

The program must stop printing values either:

When the BothFactor condition is met, or  
When the loop reaches N  

Ensure that the condition for divisibility by both A and B is checked before all other conditions.

## Input
Three space-separated integers:

N A B  

N — upper limit of the loop  
A — first divisor  
B — second divisor  

## Output
Print each result on a new line using console.log().

The output may contain:

Numbers  
A_Factor  
B_Factor  
BothFactor
