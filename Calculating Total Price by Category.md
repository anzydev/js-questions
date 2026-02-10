# Calculating Total Price by Category

Fork this repository and solve the following problem.
---

Imagine you are working on a shopping cart project your task is to implement the totalByCategory function, responsible for determining the total cost of products in a specific category.

Functionality:  
Calculate Total Price: The function should take an array of product objects and a category string as arguments. Each product object has properties namely name, price, and category. The function should return the total price of all products in the specified category.

Implementation Details:  
Use JavaScript only to create the totalByCategory function.  
Ensure that the function accurately calculates the total price based on the given category.

## Constraints
Make sure NOT to use for, while, do while, for in, and for of loop to solve this question. Using any of these above loops throws an error and test cases don't pass. Instead use array methods like map, filter, reduce, forEach.

## Input
User input  
The first line of input is going to be an array of object representing products, where each object must at least have price(key) and category(key).

Description of Object:

Value of type String against name, Value of type Number against price, and value of type String against category.

The second line is going to be a String representing category.

## Output
Return number representing the total price of all products in the given category string.
