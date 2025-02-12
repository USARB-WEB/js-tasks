## Description  
Write a function `convert(fn, array)` that takes a function and an array as input. It processes each element of the array using the provided function and returns a new array with the transformed values.  

The original array **must not be modified**.  

## Example Usage  

```javascript
function square(x) { 
    return x * x; 
} // Squares the number

console.log(convert(square, [1, 2, 3, 4])); // Output: [1, 4, 9, 16]
console.log(convert(square, [])); // Output: []

// Ensuring the original array remains unchanged
let arr = [1, 2, 3];
console.log(convert(square, arr)); // Output: [1, 4, 9]
console.log(arr); // Output: [1, 2, 3]
```
The function applies the given transformation function fn to every element in array.
It must return a new array instead of modifying the original one.
Do not use .map() method for this task.
