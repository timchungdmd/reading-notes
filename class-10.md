# Debugging

Name some key differences between a Syntax Error and a Logic Error.
- Syntax Errors: these are spelling errors in youru code that actually cause the program not to run at all, or stop working part way through; you will usually provide with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the rror messages mean
- logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. Theses are often harder to fix than syntax errors, as there usually isnt' an error message to direct you to the source of the error.

List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
- Logic error due to functions not being able to access variables that are placed inside the wrong brackets, or variables with typos. Former error is more difficult than the typo error because it can take few tries to find the correct placement for the variable that won't break the entire logic. Syntax errors are faily straightforward to fix because IDE identifies the line of code where the error is detected.

How will this topic continue to influence your long term goals?
- Debuggin skill will reduce the time for fixing errors but also enable me to check other people contribution 

### The JavaScript Debugger.

How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
- Javascript debugger allows you to watch the value of variables and set breakpoint, places in your code that you wantn to pause execution and identify the problems that prevent your code from executing properly. Its a diagnostic tool, like the one you see at car repair shop that connects to the car and troubleshoots vehicles diagnostic stop points, to check and test if the machine, in our case javascript code, works properly

Define what a breakpoint is.
- A breakpoint is a point of code where the debugger will automatically pause the Javascript execution. While the code is paused, we can examine current variables, execute commands in the console etc.

What is the call stack?
- The call stack section shows you what code was executed to get to the current line. You can see that the code is in the function that handles a mouse clikc, and that the code is currently paused on the breakpoint.

# References
- [What went wrong?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong#types_of_error)
- [What are browser developer tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)
- [Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)
- [Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)
- [Debugging in the browser](https://javascript.info/debugging-chrome)
