# Task #9 - Working with Keys
Create two objects person1 and person2 with the following structure:
```javascript
{
  name: "Person",
  age: 123,
  salary: 1542.33,
  contacts: {
    phone: "112",
    email: "email@domain.com"
  },
  address: "Moldova"
}
```
Write a method Intersection that takes these two objects as input and returns a new object containing only the fields where the values are the same in both objects.
Example:
```javascript
const person1 = {
  name: "Person",
  age: 123,
  salary: 1542.33,
  contacts: {
    phone: "112",
    email: "email@domain.com"
  },
  address: "Moldova"
};

const person2 = {
  name: "Person",
  age: 123,
  salary: 2000.00, // Different value
  contacts: {
    phone: "112",
    email: "email@domain.com"
  },
  address: "Romania" // Different value
};

// Expected result
{
  name: "Person",
  age: 123,
  contacts: {
    phone: "112",
    email: "email@domain.com"
  }
}

```
The function should compare both primitive values and nested objects correctly.
