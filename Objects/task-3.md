# Task #3 - Object Methods
Create a function multiplyNumeric(obj) that multiplies all numeric properties of the object obj by 2.

For example:

Before calling the function:
```javascript
let menu = {
  width: 200,
  height: 300,
  title: "My menu"
};

multiplyNumeric(menu);

```
After calling the function:
```javascript
menu = {
  width: 400,
  height: 600,
  title: "My menu"
};
```
Note that multiplyNumeric should not return anything. It should modify the object directly.

P.S. Use typeof to check if the property value is numeric.
