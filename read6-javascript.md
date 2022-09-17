
# Introduction to Javascript
- Traditionally Javascript was used inside web browsers.
- Node js: Server environment that can run Javascript
- 3 major parts of Javascript
    - Programming language itself
    - DOM API: how the lnaguage can interact with the various parts of a web page while in the browser
    - Server API: provided by Node.js or one of the other server side systems

-Javascript can be either coded directly inside the HTML file, or embed via external Javascript file. Latter is recommended in most cases. \<script></script> tag is used for javascript

- The most simple way for Javascript to display text for use is alert function< alert() >
- document.write: document.write(" ");
- console.log(" ");
- prompt: it will show a pop-up window wit the text provided as the first parameter and with a textbox the user can fill in.< prompt(" ","" ) >
- confirm() will show a pop-up window with the provided texts and with two buttons. If the user presses OK this function will return true, and vice verso for cancel
- fuction nameoffunction(){expression;}
- Function with parameters
    - inside the function the  parameter inside the parantheses holds the current value
    - function name(x){} > function name('Bob') > Bob gets processed through the expression between curly braces
- localStorage is a term used for a flat key value databases inside the browser that cana be access using Javascript.
- DOM(document object model): representation of the HTML page by javascript objects, heart of the interaction between plain javascript and the html in the browser.
- document.getElementById('btn').addEventListener('click', clicked); : this code means that when the browser detects a click on the html element with the id btn, then it will execute the function called clicked. Clicked function will change the DOM by running function clicked
- ajax_get: this function expects two parameters. The first one is the URL we request, second parameter is expected to be a function which will be called when the response arrives from the server
- [Javascript Basics](https://code-maven.com/javascript)
- [Mozilla Javbscript Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Javascript variables](https://www.w3schools.com/js/js_variables.asp)
- 