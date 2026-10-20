
🟨 JAVASCRIPT FULL COURSE

«Goal: Become a strong JavaScript developer and use JavaScript to build real-world websites and applications.»

---

📚 TABLE OF CONTENTS

1. Introduction to JavaScript
2. JavaScript Syntax
3. Variables
4. Data Types
5. Operators
6. Strings
7. Numbers and Math
8. User Input
9. Type Conversion
10. Conditional Statements
11. Comparison and Logical Operators
12. Loops
13. Functions
14. Scope
15. Arrays
16. Array Methods
17. Objects
18. Object Methods
19. Destructuring
20. Spread and Rest Operators
21. Dates and Time
22. DOM Introduction
23. Selecting HTML Elements
24. Changing HTML and CSS with JavaScript
25. Events
26. Forms and Validation
27. Local Storage
28. JSON
29. Error Handling
30. Debugging
31. Modules
32. Asynchronous JavaScript
33. Promises
34. Async/Await
35. Fetch API
36. Working with APIs
37. ES6+ Features
38. JavaScript Classes
39. Object-Oriented Programming
40. Regular Expressions
41. Browser APIs
42. Node.js Introduction
43. npm
44. JavaScript Projects
45. Git and GitHub with JavaScript
46. React Preparation
47. Advanced JavaScript
48. Final Projects

---

🟦 PART 1 — JAVASCRIPT FUNDAMENTALS

LESSON 1 — INTRODUCTION TO JAVASCRIPT

What is JavaScript?

JavaScript (JS) is a programming language used to make websites and web applications interactive and dynamic.

JavaScript can be used to:

- Respond to button clicks
- Change webpage content
- Change CSS
- Validate forms
- Perform calculations
- Create animations
- Build games
- Work with APIs
- Store information in the browser
- Communicate with servers
- Build web applications
- Build backend applications using Node.js

HTML, CSS and JavaScript

HTML = Structure

HTML creates the content and structure of a webpage.

CSS = Appearance

CSS controls the appearance and layout of a webpage.

JavaScript = Behavior

JavaScript controls what the webpage does.

Simple example

HTML       → Structure
CSS        → Design
JavaScript → Behavior

---

LESSON 2 — JAVASCRIPT SYNTAX

JavaScript syntax refers to the rules used to write JavaScript code.

Example:

console.log("Hello World");

JavaScript instructions are called statements.

Example:

let name = "John";
console.log(name);

JavaScript is case-sensitive.

These are different:

name
Name
NAME

---

LESSON 3 — VARIABLES

A variable is a named container used to store data.

let

Use "let" when the value may change.

let age = 20;

age = 21;

const

Use "const" when the variable should not be reassigned.

const country = "Kenya";

Example

let name = "John";
let age = 20;
const country = "Kenya";

console.log(name);
console.log(age);
console.log(country);

---

LESSON 4 — DATA TYPES

JavaScript has different types of data.

String

Text:

let name = "John";

Number

Numbers:

let age = 20;
let price = 500;

Boolean

True or false:

let isStudent = true;

Undefined

A variable without a value:

let school;

Null

Represents an intentional empty value:

let result = null;

Object

Stores related information:

let student = {
    name: "John",
    age: 20
};

Array

Stores multiple values:

let languages = ["HTML", "CSS", "JavaScript"];

---

LESSON 5 — OPERATORS

Operators are symbols used to perform operations.

Arithmetic operators

+   // Addition
-   // Subtraction
*   // Multiplication
/   // Division
%   // Remainder
**  // Exponent

Example:

console.log(10 + 5);
console.log(10 - 5);
console.log(10 * 5);
console.log(10 / 5);
console.log(10 % 3);

---

LESSON 6 — STRINGS

A string represents text.

let name = "John";

String concatenation

let firstName = "John";
let lastName = "Kimani";

console.log(firstName + " " + lastName);

Template literals

Modern JavaScript commonly uses template literals:

let name = "John";
let age = 20;

console.log(My name is ${name} and I am ${age} years old.);

---

LESSON 7 — NUMBERS AND MATH

JavaScript can perform mathematical calculations.

let price = 500;
let quantity = 3;

let total = price * quantity;

console.log(total);

JavaScript also provides the "Math" object.

Examples:

Math.round()
Math.floor()
Math.ceil()
Math.random()
Math.max()
Math.min()

---

LESSON 8 — USER INPUT

In browser JavaScript, we can use "prompt()" to receive input.

let name = prompt("What is your name?");

console.log(name);

Example:

let age = prompt("How old are you?");

console.log(age);

Remember that input from "prompt()" is returned as a string.

---

LESSON 9 — TYPE CONVERSION

Type conversion means changing data from one type to another.

String to Number

let age = Number("20");

console.log(age);

Number to String

let age = 20;

let text = String(age);

Other useful methods:

Number()
String()
Boolean()
parseInt()
parseFloat()

---

🟩 PART 2 — LOGIC AND CONTROL FLOW

LESSON 10 — CONDITIONAL STATEMENTS

Conditional statements allow JavaScript to make decisions.

if

let age = 20;

if (age >= 18) {
    console.log("You are an adult.");
}

if...else

let age = 16;

if (age >= 18) {
    console.log("Adult");
} else {
    console.log("Minor");
}

else if

let score = 75;

if (score >= 80) {
    console.log("A");
} else if (score >= 70) {
    console.log("B");
} else {
    console.log("C");
}

---

LESSON 11 — COMPARISON AND LOGICAL OPERATORS

Comparison operators

==    // Equal
===   // Strictly equal
!=    // Not equal
!==   // Strictly not equal
>     // Greater than
<     // Less than
>=    // Greater than or equal
<=    // Less than or equal

Logical operators

&&    // AND
||    // OR
!     // NOT

Example:

let age = 20;

if (age >= 18 && age <= 30) {
    console.log("Allowed");
}

---

LESSON 12 — LOOPS

Loops repeat code.

for loop

for (let i = 1; i <= 5; i++) {
    console.log(i);
}

while loop

let i = 1;

while (i <= 5) {
    console.log(i);
    i++;
}

for...of

Useful for arrays:

let languages = ["HTML", "CSS", "JavaScript"];

for (let language of languages) {
    console.log(language);
}

---

🟪 PART 3 — FUNCTIONS

LESSON 13 — FUNCTIONS

A function is a reusable block of code.

function greet() {
    console.log("Hello!");
}

greet();

Parameters

function greet(name) {
    console.log(Hello ${name});
}

greet("John");

Return

function add(a, b) {
    return a + b;
}

let result = add(10, 5);

console.log(result);

---

LESSON 14 — SCOPE

Scope determines where a variable can be accessed.

Local scope

function test() {
    let name = "John";

    console.log(name);
}

The variable belongs to the function.

Global scope

A variable declared outside functions can have broader access.

---

🟦 PART 4 — ARRAYS AND OBJECTS

LESSON 15 — ARRAYS

An array stores multiple values.

let fruits = ["Apple", "Banana", "Orange"];

Array indexes start at 0.

console.log(fruits[0]);

Output:

Apple

---

LESSON 16 — ARRAY METHODS

Important methods include:

push()
pop()
shift()
unshift()
slice()
splice()
includes()
indexOf()

Example:

let fruits = ["Apple", "Banana"];

fruits.push("Orange");

console.log(fruits);

Modern JavaScript also provides:

map()
filter()
find()
reduce()
forEach()
some()
every()

---

LESSON 17 — OBJECTS

Objects store related information using key-value pairs.

let student = {
    name: "John",
    age: 20,
    country: "Kenya"
};

Access a property:

console.log(student.name);

Or:

console.log(student["name"]);

---

LESSON 18 — OBJECT METHODS

Objects can contain functions.

let person = {
    name: "John",

    greet: function() {
        console.log("Hello!");
    }
};

person.greet();

---

LESSON 19 — DESTRUCTURING

Destructuring allows us to extract values easily.

let person = {
    name: "John",
    age: 20
};

let { name, age } = person;

console.log(name);
console.log(age);

---

LESSON 20 — SPREAD AND REST

Spread

The spread operator is:

...

Example:

let numbers1 = [1, 2, 3];
let numbers2 = [...numbers1, 4, 5];

console.log(numbers2);

Rest

Rest collects multiple values.

function add(...numbers) {
    console.log(numbers);
}

---

🟨 PART 5 — DOM AND WEB DEVELOPMENT

LESSON 21 — WHAT IS THE DOM?

DOM means:

Document Object Model

The DOM represents an HTML page as objects that JavaScript can access and modify.

JavaScript can:

- Change text
- Change HTML
- Change CSS
- Create elements
- Remove elements
- Respond to events

---

LESSON 22 — SELECTING HTML ELEMENTS

getElementById

let title = document.getElementById("title");

querySelector

let button = document.querySelector("button");

querySelectorAll

let paragraphs = document.querySelectorAll("p");

---

LESSON 23 — CHANGING HTML

HTML:

<h1 id="title">Hello</h1>

JavaScript:

let title = document.getElementById("title");

title.textContent = "Welcome!";

---

LESSON 24 — CHANGING CSS

let title = document.getElementById("title");

title.style.color = "blue";
title.style.fontSize = "40px";

---

LESSON 25 — EVENTS

Events allow JavaScript to respond to user actions.

Examples:

click
mouseover
keydown
submit
change
input

Example:

button.addEventListener("click", function() {
    console.log("Button clicked!");
});

---

LESSON 26 — FORMS AND VALIDATION

JavaScript can validate information entered into forms.

Example:

if (username === "") {
    console.log("Username is required.");
}

Forms are commonly used for:

- Registration
- Login
- Contact forms
- Search
- Payments

---

🟩 PART 6 — BROWSER STORAGE AND DATA

LESSON 27 — LOCAL STORAGE

Local Storage allows a website to store data in the browser.

localStorage.setItem("name", "John");

Retrieve it:

let name = localStorage.getItem("name");

Remove it:

localStorage.removeItem("name");

---

LESSON 28 — JSON

JSON stands for:

JavaScript Object Notation

It is commonly used to exchange data between applications.

Example:

{
    "name": "John",
    "age": 20
}

JavaScript can convert between objects and JSON.

JSON.stringify()
JSON.parse()

---

🟦 PART 7 — ASYNCHRONOUS JAVASCRIPT

LESSON 29 — ERROR HANDLING

JavaScript provides tools for handling errors.

try {
    // Code that might cause an error
} catch (error) {
    console.log(error);
}

---

LESSON 30 — DEBUGGING

Debugging means finding and fixing problems in code.

Useful tools:

console.log()
console.error()
console.warn()

The browser's Developer Tools are very import…

LESSON 31 — PROMISES

A Promise represents an operation that may finish in the future.

A Promise can be:

Pending
Fulfilled
Rejected

Example:

let promise = new Promise((resolve, reject) => {
    resolve("Success!");
});

---

LESSON 32 — ASYNC AND AWAIT

"async" and "await" make asynchronous code easier to read.

async function getData() {
    let response = await fetch("API_URL");
    let data = await response.json();

    console.log(data);
}

---

LESSON 33 — FETCH API

"fetch()" is used to request data from a server or API.

Example:

fetch("https://example.com/data")
    .then(response => response.json())
    .then(data => console.log(data));

Later we will use real APIs to build projects.

---

🟪 PART 8 — MODERN JAVASCRIPT

LESSON 34 — ES6+

Modern JavaScript introduced many useful features.

Important features include:

- "let"
- "const"
- Arrow functions
- Template literals
- Destructuring
- Spread operator
- Rest operator
- Classes
- Modules
- Promises
- Async/Await

---

LESSON 35 — ARROW FUNCTIONS

Traditional function:

function add(a, b) {
    return a + b;
}

Arrow function:

const add = (a, b) => {
    return a + b;
};

Short version:

const add = (a, b) => a + b;

---

LESSON 36 — MODULES

Modules allow JavaScript code to be separated into different files.

Export:

export function add(a, b) {
    return a + b;
}

Import:

import { add } from "./math.js";

---

🟥 PART 9 — ADVANCED JAVASCRIPT

LESSON 37 — CLASSES

Classes are used to create objects using a defined structure.

class Student {
    constructor(name, age) {
        this.name = name;
        this.age = age;
    }
}

let student = new Student("John", 20);

---

LESSON 38 — OBJECT-ORIENTED PROGRAMMING

Important OOP concepts include:

- Classes
- Objects
- Encapsulation
- Inheritance
- Polymorphism
- Abstraction

---

LESSON 39 — REGULAR EXPRESSIONS

Regular expressions are patterns used to search and validate text.

They can be used for things such as:

- Email validation
- Password validation
- Searching text
- Finding patterns

---

🟦 PART 10 — JAVASCRIPT OUTSIDE THE BROWSER

LESSON 40 — NODE.JS

Node.js allows JavaScript to run outside the browser.

With Node.js, JavaScript can be used for:

- Backend development
- APIs
- Servers
- Command-line programs
- Web applications

---

LESSON 41 — NPM

NPM is the Node Package Manager.

It allows developers to install and manage JavaScript packages.

Example:

npm init -y

Installing a package:

npm install package-name

---

🟩 PART 11 — REAL-WORLD JAVASCRIPT

APIs

An API allows different applications or services to communicate.

Example:

Your website
      ↓
    API
      ↓
Weather server
      ↓
Weather data

We will learn how to:

- Find APIs
- Read API documentation
- Send requests
- Receive data
- Display API data
- Handle API errors

---

💻 PROJECT ROADMAP

After learning the fundamentals, I will build projects such as:

Project 1

Personal Profile Website

Project 2

Calculator

Project 3

To-Do List

Project 4

Digital Clock

Project 5

Quiz Application

Project 6

Weather Application

Project 7

Movie Search Application

Project 8

Expense Tracker

Project 9

Notes Application

Project 10

Full-stack Web Application

---

🏆 FINAL JAVASCRIPT GOAL

By completing this course, I should be able to:

- Understand JavaScript fundamentals
- Write JavaScript without copying everything
- Manipulate HTML and CSS using JavaScript
- Build interactive websites
- Work with APIs
- Handle user input
- Store data
- Debug JavaScript
- Understand asynchronous programming
- Use modern JavaScript
- Use Node.js
- Work with npm
- Build real-world projects
- Understand the foundation needed for React
- Build a portfolio of JavaScript projects

---

📈 MY PROGRESS

- [ ] Lesson 1 — Introduction
- [ ] Lesson 2 — Syntax
- [ ] Lesson 3 — Variables
- [ ] Lesson 4 — Data Types
- [ ] Lesson 5 — Operators
- [ ] Lesson 6 — Strings
- [ ] Lesson 7 — Numbers & Math
- [ ] Lesson 8 — User Input
- [ ] Lesson 9 — Type Conversion
- [ ] Lesson 10 — Conditions
- [ ] Lesson 11 — Operators & Logic
- [ ] Lesson 12 — Loops
- [ ] Lesson 13 — Functions
- [ ] Lesson 14 — Scope
- [ ] Lesson 15 — Arrays
- [ ] Lesson 16 — Array Methods
- [ ] Lesson 17 — Objects
- [ ] Lesson 18 — Object Methods
- [ ] Lesson 19 — Destructuring
- [ ] Lesson 20 — Spread & Rest
- [ ] Lesson 21 — DOM
- [ ] Lesson 22 — Selecting Elements
- [ ] Lesson 23 — Changing HTML
- [ ] Lesson 24 — Changing CSS
- [ ] Lesson 25 — Events
- [ ] Lesson 26 — Forms
- [ ] Lesson 27 — Local Storage
- [ ] Lesson 28 — JSON
- [ ] Lesson 29 — Error Handling
- [ ] Lesson 30 — Debugging
- [ ] Lesson 31 — Promises
- [ ] Lesson 32 — Async/Await
- [ ] Lesson 33 — Fetch API
- [ ] Lesson 34 — ES6+
- [ ] Lesson 35 — Arrow Functions
- [ ] Lesson 36 — Modules
- [ ] Lesson 37 — Classes
- [ ] Lesson 38 — OOP
- [ ] Lesson 39 — Regular Expressions
- [ ] Lesson 40 — Node.js
- [ ] Lesson 41 — NPM
- [ ] Projects
- [ ] Final Project