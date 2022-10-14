# Event handling

Event is FIRED(or raised)
code is triggered(or invoked)

## events types
-click
-submit
-onchange
-hover
-on page load
-on mouse over
-on key release
-etc too many to list here

## Event listeners
code that is triggered when an event is fired

## bind
- bind or tether an event listerner to the event

## Event Handler
-code that runs in response to an event

## Old ways to do event handling (DO NOT DO This!)
- in the html: <article onClick='handleClickl">
-In the javascript 'element.onevenet= functioname;


## WE will use dom level 2 event handlers
'let element = docuement.getelementbyid('someid')
'element.addeventlistener

'use strict'

functin greeting(name){
  console.log(`Hello ${name}`);
}
 function processUserInput(callback){
  let name=prompt('Please enter your name'):
  callback(name) 
 }

proocessUserInput(greeting)
- it will first invoke the prompt line and any input from user will be passed through the greeting function as its argument


addEVentListener takes in 2 arguments
-event as a 
-a callback


## Asynchronous function call

//1grab container
let container=document.getElementById('container')
cosole.log(container)

// step 3declare a functino to be the event handler
function handClick(event){
  console.log('click happend')
  console.log(event);
  let thingthatgotclicked = event.target.id;
  console.log(thingthat gotclicked);

  let ptag=document.createElkemet('p');
  ptag.textContent=`You clicked on ${thingthatgotclicked};
  results.appendchild(ptag);
}

//step 2 add event listener
container.addEVentListener('click', handleClick);)
