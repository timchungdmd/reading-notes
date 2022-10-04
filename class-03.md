# Reading assignment 3
## HTML
When should you use an unordered list in your HTML document?
- Unordered list should be used when item order is irrelevant.

How do you change the bullet style of unordered list items?
- Add **type** attribute, which has 3 properties circle, disc and square.

When should you use an ordered list vs an unorder list in your HTML document?
- Contrary to unordered list, ordered list should be used when order of item is relevant.

Describe two ways you can change the numbers on list items provided by an ordered list?
- **Reversed** attribute and **start** attribute can alter  the numbers on list items. Reverse attribute will order list items from high to low. Start attribute will set the starting number of the list items. Start attribute takes arabic numeral between two quotations.

## CSS
Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
- Padding is the space between content and  the borders within an element, and margin is the space outside of the element. Padding is the equivalent of air pillow inside an amazon box, and margin is having the air pillow outside the box for protection.

List and describe the four parts of an HTML elements box as referred to by the box model.
- The box model is comprised of content box, padding box, border box, and margin box. Content box is where the content is displayed, padding box is space between the content and the borders of the box, border box wrap around the content and any padding box, and margin box is the space wrapping the 3 aformentioend boxes.

## Javscript
What data types can you store inside of an Array?
- strings, numbers, objects, and other arrays

Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
- It is a valid array. Items in an array can be accessd via using square brackeets and passing the index of the item of interest. If and item is an array itself, you can add additional index between tow square brackets. Bracket-index combination is then added at the end of the vriable that is storing the array. For example if I wanted to access 'pete' item I would type people[0][0] to access it. Two brackets are used because each item is an array. 

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

List five shorthand operators for assignment in javascript and describe what they do.
- x=f() and it means x is equal to f(). It's called assignment operator.
- x+=f() and it means x+f() value will be assigned to x variable. It's called addition assignment operator.
- x-=f() and it means x-f() value will be assigned to x variable. It's called subtraction assignment operator.
- x*=f() and it means x*f() value will be assigned to x variable. It's called multiplication assignment operator.
- x/=f() and it means x/f() value will be assigned to x variable. It's called division assignment operator.

Read the code below and evaluate the last expression and explain what the result would be and why.
- Result would be "10dog", a string type value. Javascript automatically converts numberic value to a string value when the a string is added to a number. 

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

Describe a real world example of when a conditional statement should be used in a JavaScript program.
- User login would be a good example of conditional statement. User can only login if all the conditions are met and true.

Give an example of when a Loop is useful in JavaScript.
- Loop would be useful in the example mentioned above in case password or username is not type correctly. In the case of misspelled username statement will loop through the same steps again until condition is true.

# Reference Links
- [HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals#lists)
- [Unordered list element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [Ordered list element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- [Padding](https://developer.mozilla.org/en-US/docs/Web/CSS/padding)
- [The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
- [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [Expressions and operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [Looping code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
