# Javascript Object Basics

How would you describe an object to a non-technical friend you grew up with?
- Object is like preparing a meal kit for end user. Meal kit is comprised of recipes, raw ingredients, packaging, spices, sauce and etc. When these elements are all combined together in their own purposeful manner end product is a delicious meal and convenience for the end user.

What are some advantages to creating object literals?
- Shorter syntax and easier to understand, easier to transfer a seris of structured, related data items.
How do objects differ from arrays?
- "Objects are mutalbe data structure in javascript which is used to represent a 'thing'. It stores the data in key value pair and they key can be anythingn except for undefined. Arrays are objects only in javascript. The major difference is that they store the data in an ordered collection in which the data can be acessed using a numerical index. They are also mutable and data can be modified at any index."

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
- If an object property name is held in a variable, dot notation can't access the value, only bracket notation can accesss the values. 

Evaluate the code below. What does the term 'this' refer to and what is the advantage to using 'this'?
- 'this' refers to the current object the code is being written inside. In an object method, this refer to the object. When used alone, it refers to the global object. In a function, it refers to the global object. In a function, in strict mode, this is undefined. In an event, this refer to the element that received the event. Methods like call(), apply(), and bind() can refer 'this' to any object. For the following example, 'this' is referring to object dog. Advantage of 'this' keywod is reusability in different contexts.It means, a function once defined can be invoked for different objects using this keyword. Identifying the object in the current execution context when we invoke a method.

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

# Introduction To The DOM

What is the DOM?
- Document object model is a programming interface for web documents. It represents the page so that programs can change th edocument structure, style, and content. The Dom represents the document as nodes and objects; that way, programming languages can interact with the page.

Briefly describe the relationship between the DOM and JavaScript.
- DOM is not part of the Javscript language, but rather it's a Web API used to build websites. Javascript uses the DOM to access the document and its elements. Without DOM, Javascript won't have any model or notion of web pages, HTML documents, SVG documents, and their component parts.

# references
- [Javscript Object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [What is the difference between an array and an object in Javascript](https://learnersbucket.com/examples/array/what-is-the-difference-between-an-array-and-an-object-in-javascript/)
- [Dot notation vs. Bracket notation](https://codeburst.io/javascript-quickie-dot-notation-vs-bracket-notation-333641c0f781)
- [Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- [How to Solve programming problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
- [What's the difference between primitive values and object refereces in Javascript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
- [The JavaScript this keyword](https://www.w3schools.com/js/js_this.asp#:~:text=In%20JavaScript%2C%20the%20this%20keyword,this%20refers%20to%20the%20object.)
- [The Javascript 'this' keyword](https://www.freecodecamp.org/news/javascript-this-keyword-binding-rules/#:~:text=In%20JavaScript%2C%20the%20this%20keyword,when%20we%20invoke%20a%20method.)
