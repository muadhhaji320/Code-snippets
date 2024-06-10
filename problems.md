## There is no such thing as a good programmer, only <mark style="background-color: blue;">**a good problem solver**</mark>.
<u>**Greater number:**</u> find greater number between two numbers
```javascript
// Prompt the user for input
let first_number = parseInt(prompt("Enter the first number: "));
let second_number = parseInt(prompt("Enter the second number: "));

// Compare the numbers and display the appropriate message
if (first_number > second_number) {
    console.log(`${first_number} is greater than ${second_number}`);
} else if (first_number < second_number) {
    console.log(`${first_number} is smaller than ${second_number}`);
} else {
    console.log("Both numbers are equal");
}
```

<u>**Logging:**</u> Logging a message to the console
```javascript
// Logging a message to the console
console.log("Hello, world!");
```

<u>**arithmetic operations:**</u> Performing basic arithmetic operations
```javascript
// Performing basic arithmetic operations
console.log(2 + 2); // Addition: 4
console.log(5 - 3); // Subtraction: 2
console.log(4 * 3); // Multiplication: 12
console.log(10 / 2); // Division: 5
```
<u>**Variables and data types:**</u> Variables and data types
```javascript
// Variables and data types
let name = "John";
const age = 25;
console.log("Name:", name);
console.log("Age:", age);
```

<u>**Conditional statements:**</u> Conditional statements
```javascript
// Conditional statements
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
} else {
  console.log("x is less than or equal to 5");
}
```
// Loops
for (let i = 0; i < 5; i++) {
  console.log("Iteration:", i);
}

// Functions
function greet(name) {
  console.log("Hello, " + name + "!");
}
greet("Alice");

// Arrays
let fruits = ["apple", "banana", "orange"];
console.log(fruits[0]); // Accessing array element

// Objects
let person = {
  name: "John",
  age: 30,
  profession: "Developer"
};
console.log(person.name); // Accessing object property

