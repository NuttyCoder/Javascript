### **Day 1: Basics of JavaScript**

1. **Introduction to JavaScript**  
   * History and Evolution  
   * Setting up your development environment  
2. **Variables and Data Types**  
   * `var`, `let`, `const`  
   * Primitive data types (Number, String, Boolean, Null, Undefined, Symbol)  
   * Non-primitive data types (Objects, Arrays)  
3. **Operators**  
   * Arithmetic operators  
   * Comparison operators  
   * Logical operators  
4. **Control Structures**  
   * `if`, `else if`, `else`  
   * `switch` statements

#### **1\. Introduction to JavaScript**

**History and Evolution**: Understand the context of why JavaScript was created, its evolution, and its importance in web development.

**Setting up your development environment**: Install Node.js, a code editor like Visual Studio Code, and configure the environment to run JavaScript code.

#### **2\. Variables and Data Types**

**Understanding Variables**: Learn the difference between `var`, `let`, and `const` and when to use each.

| Example: var name \= 'John'; let age \= 30; const isDeveloper \= true |
| :---- |

**Primitive Data Types**: Explore the basic data types such as Number, String, Boolean, Null, Undefined, and Symbol.

| let number \= 42;  let text \= "Hello, world\!"; let isHuman \= true;  let empty \= null;  let notDefined;  let symbol \= Symbol('symbol' |
| :---- |

#### **Non-primitive Data Types: Understand Objects and Arrays.**

| let person \= { name: 'Alice', age: 25 }; // Object let colors \= \['red', 'green', 'blue'\];   // Array |
| :---- |

### 

#### **3\. Operators**

### **Arithmetic Operators: Learn how to perform basic calculations: `+`, `-`, `*`, `/`, `%`.**

| let sum \= 5 \+ 3; // 8 let difference \= 10 \- 4; // 6 let product \= 2 \* 3; // 6 let quotient \= 8 / 2; // 4 let remainder \= 7 % 2; // 1 |
| :---- |

### **Comparison Operators: Understand how to compare values: `==`, `===`, `!=`, `!==`, `<`, `>`, `<=`, `>=`.**

| console.log(5 \== '5'); // true  console.log(5 \=== '5'); // false  console.log(5 \!= '5'); // false  console.log(5 \!== '5'); // true  console.log(5 \< 10); // true  console.log(5 \> 10); // false  console.log(5 \<= 5); // true  console.log(5 \>= 6); // false |
| :---- |

### **Logical Operators**: Work with logical operators: `&&`, `||`, `!` (AND, OR, NOT)

| let isAdult \= true;  let hasID \= false;  console.log(isAdult && hasID); // false  console.log(isAdult || hasID); // true  console.log(\!isAdult);       // false   |
| :---- |

    **Control Structures**

* `if`**,** `else if`**,** `else` **Statements**: Write conditional statements to control the flow of your program.

| let score \= 85; if (score \>= 90\) {  console.log('A');  } else if (score \>= 80\) {  console.log('B');  } else if (score \>= 70\) {  console.log('C');  } else {  console.log('F');  |
| :---- |

  `switch` **Statements**: Use `switch` to handle multiple conditions more concisely.

| let day \= 'Monday'; switch (day) {      case 'Monday':          console.log('Start of the week');          break;      case 'Wednesday':          console.log('Midweek');          break;      case 'Friday':          console.log('End of the week');          break;      default:          console.log('Another day'); } |
| :---- |

 **Practice:**

* Write simple programs to reinforce your understanding, like a basic calculator or a program that grades student scores.

### **Resources:**

* MDN Web Docs: JavaScript Basics  
* FreeCodeCamp: JavaScript Basics

Mastering these basics will set a strong foundation for your JavaScript journey.

       
**Day 2: Functions and Objects**

1. **Functions**  
   * Function declaration and expression  
   * Arrow functions  
   * Parameters and arguments  
   * Return values  
   * Recursion and higher-order functions  
2. **Objects and Arrays**  
   * Object literals  
   * Accessing and modifying properties  
   * Methods  
   * Array creation and manipulation  
   * Iterating over objects and arrays

### **Day 3: Advanced JavaScript Concepts**

1. **Closures and Scope**  
   * Global vs local scope  
   * Closures  
   * IIFE (Immediately Invoked Function Expression)  
2. **Asynchronous JavaScript**  
   * Callbacks  
   * Promises  
   * `async` / `await`  
3. **Error Handling**  
   * `try`, `catch`, `finally`  
   * Custom errors

### **Day 4: DOM Manipulation and Events**

1. **Document Object Model (DOM)**  
   * Selecting elements  
   * Modifying elements  
   * Creating and deleting elements  
2. **Events**  
   * Adding and removing event listeners  
   * Event propagation (bubbling and capturing)  
   * Event delegation

### **Day 5: Working with APIs and Advanced Topics**

1. **Web APIs**  
   * Fetch API  
   * Working with JSON data  
   * Making GET, POST, PUT, DELETE requests  
2. **Advanced Topics**  
   * Modules (ES6 Modules)  
   * Web Storage (LocalStorage, SessionStorage)  
   * Regular expressions  
   * Performance optimization tips  
3. **Project**  
   * Create a small project to apply everything you've learned, such as a to-do list app or a simple game.

### **Learning Resources**

* **Books**: *Eloquent JavaScript* by Marijn Haverbeke, *JavaScript: The Good Parts* by Douglas Crockford  
* **Online Courses**: FreeCodeCamp, Codecademy, and MDN tutorials  
* **Practice Platforms**: LeetCode, HackerRank, and Codewars

