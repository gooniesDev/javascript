# Arrays

Arrays are a fundamental part of programming. An array is a list of data. We can store a lot of data in one variable, which makes our code more readable and easier to understand. It also makes it much easier to perform functions on related data.

The data in arrays are called **elements**.

Here is a simple array:

```javascript
// 1, 1, 2, 3, 5, and 8 are the elements in this array
var numbers = [1, 1, 2, 3, 5, 8];
```
It should be noted that using this data structure (ordering the data in an organized and easy-to-access way) we can create a two-dimensional array or matrix, which allows us to work with more complicated problems.

```javascript
//           	 name       age	 username   state 
let users = [['Alex Murphy', 22, 'Goonies', true], ['Emma', 31, 'EmmaDev', false]];

//Accessing element 0 (first array) and inside it I want to visualize the second element ('Goonies')
console.log(users[0][2]);
```

We can also exchange different types of data within an array or matrix.


