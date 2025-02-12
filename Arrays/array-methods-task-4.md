# JavaScript Task: Filter Numeric Values  

## Description  
Given the following array:  

```javascript
[1, "a", 2, null, 3, undefined, 4, {}, 5, 6, word, 7, 8, false, 9, 100]
```
Write a function filterNumbers() that removes all non-numeric values and returns a new array containing only numbers between 1 and 9, inclusive.

### Input and Output Examples
Input (Original Array)
```[1, "a", 2, null, 3, undefined, 4, {}, 5, 6, word, 7, 8, false, 9, 100]```

Output (Filtered Array)
```[1, 2, 3, 4, 5, 6, 7, 8, 9]```

Notes
- The function should filter out all elements that are not numbers.
- Only numbers between 1 and 9 should be included in the final array.
- The function should return a new array, leaving the original array unchanged.
