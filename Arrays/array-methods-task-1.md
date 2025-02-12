# Description  
Given an array `[1, 2, 3, 4, 5, 6, 7, 8, 9]`, use a **single array processing function** to transform it into `[1, 2, 3, 4, 0, 0, 0, 6, 7, 8, 9]`.  

## Solution Example  

```javascript
const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];

const modifiedArray = numbers.map((num, index) => 
    index === 4 || index === 5 || index === 6 ? 0 : num
);

console.log(modifiedArray); 
// Output: [1, 2, 3, 4, 0, 0, 0, 6, 7, 8, 9]
```
> Do not use map from previous example
