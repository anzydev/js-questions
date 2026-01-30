# Failed Orders

Fork this repository and solve the following problem.
---

Mr. Cashier at JSElectronics needs help counting failed orders for the day.

Implement the function:  
function failedOrders(orders)

Process:  
For each order:  
Check stock using checkQuantity(name).  
If the quantity is greater than 0:  
Reduce stock by 1 using updateQuantity(name).  
If out of stock, skip the order, and increase the count as a failed order.

Pre-defined Functions:  
checkQuantity(name): accepts order name as a parameter and returns the available stock quantity.  
updateQuantity(name): accepts order name as a parameter and reduces the available stock quantity by 1.

Function failedOrders Parameter:  
orders: Array of objects {name: string, price: number}

Function failedOrders return:  
Return the count of failed orders.

## Input
Input shall contain a single-line JSON string of an object with 2 keys ("orders", "stocks") with the value of an array of objects.  
i.e { "orders": [], "stocks": [] }

orders: an array of objects, where each object has 2 keys name (string) & price (number).  
For eg  
"orders": [{"name": "product1", "price": 2000}, {"name": "product2", "price": 3000}]

stocks: an array of objects, where each object has 2 keys name (string) & quantity (number).  
For eg  
"stocks": [{"name": "product1", "quantity": 2}, {"name": "product2", "quantity": 3}]

## Output
total number of orders that failed to be processed from all the transactions.
