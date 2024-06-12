## There is no such thing as a good programmer, only <mark>**a good problem solver**</mark>.

```javascript
// Greater number: find greater number between two numbers
// Prompt:Prompt the user for input
let first_number = parseInt(prompt("Enter the first number: "));
let second_number = parseInt(prompt("Enter the second number: "));

// Compare: Compare the numbers and display the appropriate message
if (first_number > second_number) {
    console.log(`${first_number} is greater than ${second_number}`);
} else if (first_number < second_number) {
    console.log(`${first_number} is smaller than ${second_number}`);
} else {
    console.log("Both numbers are equal");
}
```
```html
<!DOCTYPE html>
<html>
<body>

<h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>


<!-- "finds" an HTML element (with id="demo"), and changes the element content (innerHTML) to "Hello JavaScript":-->
<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

</body>
</html>
```

```javascript
// alert: displays an alert dialog box with a message:
alert("Hello, World!");
```

```javascript
// Logging: Logging a message to the console
console.log("Hello, world!");
```

```javascript
// arithmetic operations: Performing basic arithmetic operations
console.log(2 + 2); // Addition: 4
console.log(5 - 3); // Subtraction: 2
console.log(4 * 3); // Multiplication: 12
console.log(10 / 2); // Division: 5
```

```javascript
// Variables and data types: Variables and data types
let name = "John";
const age = 25;
console.log("Name:", name);
console.log("Age:", age);
```

```javascript
// Conditional statements: Conditional statements
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
} else {
  console.log("x is less than or equal to 5");
}
```
```javascript
// Loops: Loops
for (let i = 0; i < 5; i++) {
  console.log("Iteration:", i);
}
```
```javascript
// Functions: Functions
function greet(name) {
  console.log("Hello, " + name + "!");
}
greet("Alice");
```
```javascript
// Arrays: Arrays
let fruits = ["apple", "banana", "orange"];
console.log(fruits[0]); // Accessing: Accessing array element
```
```javascript
// Objects: Objects
let person = {
  name: "John",
  age: 30,
  profession: "Developer"
};
console.log(person.name); // Accessing: Accessing object property
```
