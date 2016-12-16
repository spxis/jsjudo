

# Scalable Websites

- Architecture bottlenecks
- Scaling Database: vertical, horizontal
- CPU Bound Application
- IO Bound Application
- NoSQL vs RDBMS, sharding (horizontal) and partitioning (vertical) 
- Loose coupling of systems
- Asynchronous code
- Load Balancers
- CDNs, cache static content, reduce latency by geographic region

# Mathematical / Programming Sites

- LeetCode OJ Algorithms: https://leetcode.com/problemset/algorithms/
- Project Euler: https://projecteuler.net/archives
- Cracking the Coding Interview, 5th Edition Solutions: https://github.com/careercup/ctci/tree/master/javascript

# Answer Sites

- leetcode-javascript: https://github.com/chihungyu1116/leetcode-javascript

# Software Design

- Dependency Injection: https://en.wikipedia.org/wiki/Dependency_injection
- Design Patterns: https://en.wikipedia.org/wiki/Design_Patterns
- Describe Object Composition vs Class Inheritance!!! (Gang of Four 1995:20): Inheritance (white-box: internals are visible, "inheritance breaks encapsulation because it exposes a subclass to details of it's parent's implentation") vs object composition (black-box: no internal details are known)

# JavaScript and Object-Oriented Programming

- What is Inheritance? Inheritance refers to an object being able to inherit methods and properties from a parent object (Function).
- What is Encapsulation? Enclosing all the functionalities of an object within that object so that the object’s internal workings (its methods and properties) are hidden from the rest of the application. 
- What is Polymorphism? Objects can share the same interface (how they are accessed and used) while their underlying implementation of the interface may differ.
- What is the Object.prototype? The top of the prototype chain. The properties and methods that all objects inherit from. 
- What is a Constructor? A function for initializing new objects. You use the new keyword to call the constructor. 
- What is a Function property? A variable defined on a function.
- What is a Prototype? It defines the shape of an object. 
- What is a Prototype property? A property on an object that contains properties and methods, used with Inheritance. This property is available to all instances of that object [function].
- What is a Prototype attribute? The parent of an object, where its properties were inherited from.
- What is Object.create()? Introduced in ECMAScript 5, founded by Douglas Crockford. Helps achieve classical inheritance. This method creates a new object with the specified prototype object and properties.
- What is a Mixin? A function that copies functions from superclass prototypoe to the subclass prototype.
- What is the difference between Function Declarations and Function Expression? Function Declarations are hoisted while Function Expressions are not.
- What happens when a function is wrapped in parentheses? The result is evaluated as an expression, since the parentheses constitute a grouping operator and they can only contain an expression.
- What is a closure? An inner function that has access to the outer (enclosing) function's variables (scope). 
- What are the 3 scope chains for a closure? own scope, outer function variables, global variables.
- What does the hasOwnProperty() method do? Tells you if the object has it's own property with the specified name, not an inherited property.
- What are the methods used to Serialize and Deserialize Objects? JSON.stringify() and JSON.parse().
- How do you delete a project of an Object? Use the delete operator, delete someObject.propertyToDelete.

# Notes on Closures
- Closures have access to the outer function's variable, even after the outer function returns;
- Closures store references to outer function variables, not the actual value
- Closures require care when outer function variables change, since variables are by reference, if they change, the values will change as well.

# Angular Interview Questions

- Modern Angular 1.x essential interview questions: https://toddmotto.com/modern-angular-interview-questions
- 11 Essential AngularJS Interview Questions*: https://www.toptal.com/angular-js/interview-questions#note-1

# Front End Developer Interview Questions

- 4 JavaScript Design Patterns You Should Know (Module, Prototype, Observer, Singleton): https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know
- JavaScript Objects in Detail: http://javascriptissexy.com/javascript-objects-in-detail/
- JavaScript Prototype in Plain Language: http://javascriptissexy.com/javascript-prototype-in-plain-detailed-language/
- JavaScript Variable Scope and Hoisting Explained: http://javascriptissexy.com/javascript-variable-scope-and-hoisting-explained/
- Understand JavaScript Closures With Ease: http://javascriptissexy.com/understand-javascript-closures-with-ease/
- OOP In JavaScript: What You NEED to Know: http://javascriptissexy.com/oop-in-javascript-what-you-need-to-know/
- More on Hoisting: http://adripofjavascript.com/blog/drips/variable-and-function-hoisting
- More on Named Function Expressions: https://kangax.github.io/nfe/

# NodeJS Interview Questions

- What is setImmediate()?
- Node.js Interview Questions and Answers: https://blog.risingstack.com/node-js-interview-questions/
- 7 Essential Node.js Interview Questions: https://www.toptal.com/nodejs/interview-questions
- Top 25 Node.js Interview Questions & Answers: http://career.guru99.com/top-25-interview-questions-on-node-js/

# Interview Preparation

- JavaScript test: http://www.w3schools.com/quiztest/quiztest.asp?qtest=JavaScript
- Interview Questions for front-end-Developer: http://www.thatjsdude.com/interview/
  - HTML related interview questions: http://www.thatjsdude.com/interview/html.html 
  - part -1: beginner: http://www.thatjsdude.com/interview/js1.html
  - JS: Interview Questions part -2: intermediate http://www.thatjsdude.com/interview/js2.html
  - JS: Interview Questions part -4: Stack, Queue, Linked List: http://www.thatjsdude.com/interview/linkedList.html
  - ALL Front End Interview Questions: https://github.com/khan4019/front-end-Interview-Questions
- 5 Typical JavaScript Interview Exercises - https://www.sitepoint.com/5-typical-javascript-interview-exercises/
- Front-end Job Interview Questions: https://github.com/h5bp/Front-end-Developer-Interview-Questions

# CSS Questions

Questions inspired and borrowed from resources I collected:

- What is a class selector is and how is it used?
- What is an ID selector and how is it used?
- How does a class selector differ from an ID selector?
- What is a child selector?
- How does a browser determine how CSS selectors are applied to an element? Describe CSS specificity.
- What are pseudo classes and how are they used? Name three.
- What are pseudo elements? How are they defined? Name one.
- How do you use the CSS content property? What pseudo-elements are used with this property?
- What is the difference between the nth-child and nth-of-type?
- What are 3 ways to apply CSS styles to a web page.
- What is CSS grouping and how is it used?
- How do floats work in CSS? How would you clear a float?
- What is Quirks Mode and how is it relevant?
- What is a CSS "reset" file? What is it used for?
- Describe the CSS Box Model. What are the 4 that can be controlled?
- Describe the CSS Flexbox layout.
- How would you visually hide HTML content to only be read by a screen reader?
- How would you check if a CSS feature or property was supported on a target browser?
- What are CSS sprites? What are their advantages and how are they used?
- What is the CSS Z-index property? How does it take effect?
- What are the pros and cons of External Style Sheets? Where should they be placed in HTML?
- What are the pros and cons of Embedded CSS Style Sheets? Where should they be placed in HTML?
- What is the HTML tag used to refer to an External Style Sheet?
- Describe and name the two CSS box-sizing properties. What is the default property?
- What are CSS Media Types? Name two.
- What are CSS Media Queries? How are they used?
- What techniques are used to optimize a page for printing?
- What CSS properties are used to change element dimensions? What values can they accept?
- What is the CSS property used for changing text color? What about text size?
- How can you restore the default CSS property of a DOM element?
- Name five major CSS properties for any given element.
- Are CSS properties case-sensitive?
- Name the four different unit types for the CSS font-size attribute.
- What is the correct order of the four CSS border properties?
- What is the default CSS position property value? Name two others.
- What is a CSS shorthand property? Give an example.
- What is the CSS property for manipulating a bulleted list?
- What are CSS Counters and how are they used?
- What are the differences between inline and block elements?
- How do you apply CSS3 transitions to any element property? Name one transition.
- How are the visibility and display CSS properties used to hide elements? Describe the differences. 
- Why are relative width fonts considered better than fixed width fonts?
- What fonts are supported by all computing platforms?
- Name a CSS Grid System and how it is used.
- Name a CSS preprocessor system and how it is used. What are the pros/cons?
- Name one feature that was introduced in CSS2 or CSS2.1.
- Name 3 features and properties of CSS3.
- Name one new feature or property of any proposed CSS4 specification.
- How do you apply rounder corners to a DIV element?
- Name several ways to modify CSS properties for an element in JavaScript?
- What is the syntax for accessing CSS properties with hyphens in JavaScript?
- How do you alter the class attribute of an HTML element in JavaScript?

## CSS References
- Test your CSS skills: http://www.w3schools.com/quiztest/quiztest.asp?qtest=CSS
- 25 Helpful CSS Interview Questions and Answers: http://www.skilledup.com/articles/25-css-interview-questions-answers
- CSS interview questions and answers: http://jgthms.com/css-interview-questions-and-answers.html
- CSS: interview questions, 21+ questions for intermediate JS developer: http://www.thatjsdude.com/interview/css.html
