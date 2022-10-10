# Object-oriented programming, HTML tables

## Domain Modeling

Explain why we need domain modeling.
- Domain modeling is equivalent of rough draft in writing. When it's well articulated it can verify and validate the understanding of a specific problem aong various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

- Constructor exampel
var EpicaFailVideo=function(epicRating, hasAnimamls)
{
  this.epicRating = epicRating;
  this.hasAnimamls = hasAnimamls;
}
var parkourFail = new EpicFailVideo(7, false);
var corgFail=new EpicFailVideo(4,true);
  - Constructor function is defined using a function expression. 
  - When the function is called, the data inside these parameters are stroed inside the 'this.epicRating' and 'this.hasAnimamls' parameters. These properties ensure any newly created object can access that dat later.
  - 'new' keyword instantiates(creates) objects  and constructor function inisitalizes properties inside 'this.epicRating' and 'this.hasAnimals', (7,false) and (4,true) properties are initialized by calling the EpicFailVideo constructor function.
  - Objects are stores in keywords parkourFail and corgiFail.
- Methods can be added to a constructor functions prototype. ex) EpicaFailVideo.prototype.generateRandom=function(min,max){ return Math.Floor(Math.random() * (max-min+1)+min;)}
## HTML Table Basics

Why should tables not be used for page layouts?
- Layout tables reduce accessibility for visually impaired users because screen readers' output will be confusing to their users. Tables produce tag soup, which will be more difficult to write, maintain, and debug. Tables are not automatically responsive. 

List and describe 3 different semantic HTML elements used in an HTML <table>.
- <th> element that denotes a header, <table> tag, <td> element that denotes table data.

## Introducing Constructors

What is a constructor and what are some advantages to using it?
- Constructor is a function called using the new keyword.When a contructor is called it will create a new object, bind 'this' to the new object, run the code in the constructor, and return the new object. Contructors, by convention , stat with a capital letter and ar named for the type of object they create. 

How does the term 'this' differ when used in an object literal versus when used in a constructor?
- 'This' keyword refers to the object that will be created by constructor function. On the other hadn, 'this' refers to the object it is part of when used in an object literal.

## Object Prototypes Using A Constructor

Explain prototypes and inheritance via an analogy from your previous work experience.
-  Prototype is a property that every function in Javasscript has and it allows us to share methods across all instances of a function. All the functionality is still the same but now instead of having to manage a separate object for all the methods, another object that comes built into the function itself can be used.

NOTE: This is a very common front end developer interview question

# References
- [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- [HTML tables basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
- [Introducing constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
- [Beginners guide to Javascript prototype](https://ui.dev/beginners-guide-to-javascript-prototype)
