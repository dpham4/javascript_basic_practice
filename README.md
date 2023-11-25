# JavaScript Basic Cheatsheet

## 1. Variables Declaration

**Syntax:**
```javascript
let variableName = value;
const constantName = value;
```

**Example:**
```javascript
let age = 25;
const pi = 3.14159;
```

**Practice Assignments:**

- Declare a variable `myNumber` and assign it a numeric value.
- Create a constant `PI` and assign it the value of `pi`.
- Declare two variables `num1` and `num2` and assign them numeric values. Add them together and store the result in a new variable called `sum`.
- Declare a variable `isTrue` and assign it a boolean value.
- Create a variable `fullName` and concatenate your first and last name into it.
- Declare a variable `price` and assign it a decimal value.
- Create a variable `message` and assign it a string. Append another string to it.
- Declare a variable `isNull` and assign it a null value.
- Create a variable `isArray` and assign it an array containing three elements.
- Declare a variable `isUndefined` without assigning any value to it.
- Declare a variable `temperature` and assign it a value.
- Create a constant `HOURS_IN_A_DAY` and assign it the value 24.
- Declare a variable `isWeekend` and assign it a boolean value.
- Create a variable `username` and assign it your name.
- Declare a variable `isValid` and assign it a boolean value.

<br/><br/>

## 2. If-Else Statements:**

**Syntax:**
```javascript
if (condition) {
  // code to be executed if the condition is true
} else if (anotherCondition) {
  // code to be executed if the first condition is false and this condition is true
} else {
  // code to be executed if all conditions are false
}
```

**Example:**
```javascript
let temperature = 25;

if (temperature > 30) {
  console.log('It\'s a hot day!');
} else if (temperature <= 30 && temperature > 20) {
  console.log('The weather is pleasant.');
} else {
  console.log('It\'s cold today.');
}
```


