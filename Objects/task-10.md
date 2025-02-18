# Task #10 - Array of Objects
Create an array that contains at least 5 students (the algorithm should work for any number of students) and their grades (at least 4 grades per student).
```javascript
const students = [
  {
    name: "Alice",
    marks: [8, 10, 7, 5, 4]
  },
  {
    name: "Bob",
    marks: [3, 4, 2, 5, 6]
  },
  {
    name: "Charlie",
    marks: [9, 10, 8, 9, 7]
  },
  {
    name: "David",
    marks: [6, 5, 4, 7, 5]
  },
  {
    name: "Emma",
    marks: [10, 9, 10, 10, 9]
  }
];

```
Write the following functions:

- Calculate the average grade for each student and display their name with the average.
Example Output:
```
Alice: 6.8
Bob: 4.0
Charlie: 8.6
David: 5.4
Emma: 9.6
```
- Find and display students with an average grade < 5.
Example Output:
```
Students with an average grade < 5: Bob (4.0)
```

- Find the students with the highest and lowest average grades.
Example Output:
```
Highest Average: Emma (9.6)
Lowest Average: Bob (4.0)
```

- Sort students by their average grade in descending order.
Example Output:
```
Sorted List (by average grade):
Emma: 9.6
Charlie: 8.6
Alice: 6.8
David: 5.4
Bob: 4.0
```

- Display students whose average grade is higher than the class average.
Example Output:
```
Class Average: 6.88
Students above class average: Emma (9.6), Charlie (8.6)
```
