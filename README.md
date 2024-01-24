## 1. What is JavaScript?
Explanation: JavaScript is a high-level, interpreted programming language primarily used for creating dynamic content on websites. It enables interactivity on the client side and is widely supported by web browsers.

###Example: 

alert('Hello, World!');

## 2. Separation of Concerns
Explanation: Separation of Concerns (SoC) is a design principle that suggests dividing a software system into distinct sections, each addressing a specific concern. This makes the code more modular, maintainable, and easier to understand.

### Example: In a web application, separate HTML for structure, CSS for styling, and JavaScript for behavior.

## 3. JavaScript in Node
Explanation: Node.js is a runtime environment that allows the execution of JavaScript code outside a web browser. It is commonly used for server-side development.

### Example: Creating a simple Node.js server:

const http = require('http');

const server = http.createServer((req, res) => {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello, Node!');
});

server.listen(3000, 'localhost', () => {
  console.log('Server running at http://localhost:3000/');
});
## 4. Variables
Explanation: Variables are containers for storing data values. They provide a way to label and reference data in a program.

### Example: Declaring and initializing a variable in JavaScript:

let age = 25;
console.log(age);  // Output: 25
## 5. Constants
Explanation: Constants are variables whose values should not be changed once they are assigned.

### Example: Declaring a constant in JavaScript:

const PI = 3.14;
console.log(PI);  // Output: 3.14
## 6. Primitive Types
Explanation: Primitive types are the most basic data types in a programming language. In JavaScript, they include numbers, strings, booleans, null, and undefined.

### Example: Using primitive types in JavaScript:

j
let num = 42;          // Number
let str = 'Hello';     // String
let isTrue = true;     // Boolean
let nothing = null;    // Null
let notDefined;        // Undefined
7. Dynamic Typing
## Explanation: Dynamic typing allows variables to hold values of any type, and the type can change during runtime.

### Example: Dynamic typing in JavaScript:

let variable = 42;    // variable is a number
variable = 'Hello';   // variable is now a string
## 8. Objects
Explanation: Objects are complex data types that can store key-value pairs. They are used to represent real-world entities and their properties.

### Example: Creating and accessing an object in JavaScript:

let person = {
  name: 'John',
  age: 30,
  isStudent: false
};

console.log(person.name);  // Output: John
## 9. Arrays
Explanation: Arrays are ordered lists of values. They allow storing and manipulating multiple values under a single variable.

### Example: Creating and accessing an array in JavaScript:

let fruits = ['apple', 'orange', 'banana'];
console.log(fruits[0]);  // Output: apple
## 10. Functions
Explanation: Functions are blocks of reusable code designed to perform a specific task. They promote code reuse and modularity.

### Example: Defining and calling a function in JavaScript:

function greet(name) {
  console.log('Hello, ' + name + '!');
}

greet('Alice');  // Output: Hello, Alice!
## 11. Types of Functions
Explanation: There are various types of functions, including regular functions, arrow functions, anonymous functions, and callback functions.

### Example: Using an arrow function in JavaScript:


const add = (a, b) => a + b;
console.log(add(3, 5));  // Output: 8
