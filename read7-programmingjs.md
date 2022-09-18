# Control flow

- Order in which the computere executes statements in a script
- Trypical script in javascript and alikes include many control structures, including conditionals, loops, and functions
- [Javascript Control flow referece](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference#control_flow)
- [Statements reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)

# Javascript functions

- Function: block of code designed to perfor a particular task
- Function syntax: function keyword+name+parantheses
- Parnatheses may incldue parameter names  separated by commas
- function will execute when something invokes the function(button clicking, automatically etc.)

- Return statement: function will stop executing. OFten computes a return value
- Functions can be resued, even with different arugments
- Local variables: variable local to the function, can only be access from within the function, same name can be used in different functions

# Javascript operators

- = is an assignment operator
- == is an equal
- === equal value and equal tpe
- != not equal
- !== not equal value or not equal type
- ? ternary operator
- % modulus(division remainder)
- ++ increment
- -- decrement
- ** exponentiation
- \+ can also be used to concatenate strings
- && logical and, || logical or , | logical not

## Bitwise operators

- & and, | or, ~ not, ^ xor, \<< left shift, \>> right shift, >>> unsigned right shift

# Javascript Objects

- Objects are like variables, except it can contain many values
- Values are stored as name:value pairs
- It is a common practice to declare objects with the const keyword

## Accessing object properties

- objectName.propertyName or objectName\["propertyName"]
- Methods are actiosn that can be performed on objects and stored in properties as function definitions
- [Javascript Object Reference](https://www.w3schools.com/js/js_objects.asp)

# Javascript Events

- HTML event can be something the browser does, or something a user does
- Javascript lets you execute code when events are detected
- HTML allows event handler attributes, with javascript code, to be added to HTML elements
\<button onclick="document.getElementById('demo').innerHTML=Date()"> is an example

## Common HTML Events

- onchange, onclick, onmouseover, onmouseout, onkeydown, onload

# Strings

- string is zero or more characters written inside quotes
- .length will print the length of the string
- backslash is the escape character and turns special characters into string characters

# String Methods

- Extracting string parts: slice(start, end), substring, substr, end value is non-inclusive
-substr second parameter specifies the lenght of the extraacted part

# Replacing string content

- text.replace(somesentence with string1, string2) = sentence with string 2, replaces only the first match
- To replae case insensitivie, use a regular expression with an /i flag(eg. /MICROSOFT/i)

- toUpperCase(), toLowerCase()
- concat will join tow or more string(text1.concat(" ",text2)= text1 text2

- trim() removes whitespace from both sides of a string
- trimStart(), trimEnd removes whitespace only from the start and end of a string
- toString() will change int to string
- padStart() and padEnd() methods pad a string with another string (two parameters first one is how many and second paracter is string that willl be added)
- charArt(x) returns the character at x index position

- split(x) will convert a string to an array, if separator is ommited returned array will contain the whole string in index[0], if the separator is "" returned array will be an array of single characters

- indextOf() will return the inex of the first occurrence of a specified text in a string
- search() returns position of the match
- match() searches a string for a match against a regular expression and returns the matches as an array object
- includes() return true if a string contains a specified value
- startsWith() returns true if s string begins with a specified value (second parameter is option, it is the starting position of starting point)
- endsWith() returns true if string ends with specified value, second optional parameter is length to search

- Javascript numbers are always 64 bit floating point
- floating point arithmetic is not always 100% accurate, may need to multiply and divide by 10
- Javascript will try to convert string to numbers in all numeric operations(if one variable is numeric string)
- isNaN() is a method to findout if a value is a note a number

## Number methods

- toString()
- x.toExponential(a) returns a string with a humber rounded and written using exponential notation, parameter defines the number of characters behind the decimal point
- toFixed() returns a string with the number written with a specified number of decimals
- toPrecision() returns a string with a number written witha specified length
- valueOf() returns number object to primiteve values, there is NO reason to use it in your code
- MAX_VALUE, MIN_VALUE
