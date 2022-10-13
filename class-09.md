# Forms and JS events

### HTML Forms

Why are forms so important in web development?
- It is one of the main points of interactino between a user and a website or application. Forms allow useres to enter data, which is generally sent to a web server for processing and storage, or used on the client-side to immediately update the interface in some way .

When designing a form, what are some key things to keep in mind when it comes to user experience?
- Bigger forms can negatively imapct user experience, Define the right set of data I want to ask our user to enter, ask only for the data I absolutely need.

List 5 form elements and explain their importance.
- form element: This defines a form, container element like section or footer.
- label element: This represents a caption for an item in a user interface.
- input element: This is used to create interacitive controls for web-based forms in order to accept data from the user; a wide variety of types of input data and control widgets are available, depending on the device and user agent.
- textarea element: This element represents a multi-line-text editing control, useful when you want to allow users to enter a sizeablea mount of free-form text. 
- button element: this element is an interactive element activated by a user with an input devide. Once activated, it then performs a programmable action, such as submitting a form or opening a dialog.

Learn JS
Introduction To Events.

How would you describe events to a non-technical friend?
- Events are actions or occurrences that happen in the system you are programming, which the system tells you about so your code can react to them. Good example is password prompts. Everytime we type in our password to login, website tells us either we typed in the wrong password or log us into the website. These two responses from the website is an event. 

When using the addEventListener() method, what 2 arguments will you need to provide?
- the name of the event we want to register this handler for, and the code that comprises the handler function we want to run in response to it.

Describe the event object. Why is the target within the event object useful?
- Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. this is called the event object, and it is automatically passed to event handlers to provide extra features and information. Target property of the event object is always a reference to the element the event occurred upon. Some event objects add extra properties that are relevant to that particular type of event.

What is the difference between event bubbling and event capturing?
- Event bubbling: When an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestors.
- Event capturing: It's the opposite of bubbling. Event goes down to the element starting from the top parent element.

# References
- [Your first form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
- [Extensive guide to form usability](https://www.smashingmagazine.com/2011/11/extensive-guide-web-form-usability/)
- [7 Best practices for buttons](https://www.uxmatters.com/mt/archives/2012/05/7-basic-best-practices-for-buttons.php)
- [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events#using_addeventlistener)
- [Event bubbling and capturing](https://javascript.info/bubbling-and-capturing)
