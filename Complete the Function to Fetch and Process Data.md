# Complete the Function to Fetch and Process Data

Fork this repository and solve the following problem.
---

You are given an incomplete function fetchAndProcessData(id) that should:

1. Fetch user data for the given id using the provided fetchUser(id) function that returns a promise.  
2. Retrieve the first post from the array of postIds and fetch its details using fetchPosts(postId) that returns a promise.  
3. Return an object containing user: <users> & posts: <firstPost>.

Complete the function so that it works as expected using async and await.

## Input
Input id :
1

## Output
{  
 user: { id: 1, name: "Alice", postIds: [101,102] },  
 posts: { postId: 101, title: "Hello World" }  
}

## Constraints
only use id as integer from 1 to 3 only

## Example

Input:
1

Output:
{  
 user: { id: 1, name: "Alice", postIds: [101,102]},  
 posts: { postId: 101, title: "Hello World" }  
}
