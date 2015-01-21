#Front-end Job Interview Questions
  
#### General Questions:

1. Talk about your preferred development environment. (OS, Editor or IDE, Browsers, Tools, etc.)
1. Can you describe your workflow when you create a web page?
1. If you have 5 different stylesheets, how would you best integrate them into the site?
1. How would you optimize a website's assets/resources?
1. How many resources will a browser download from a given domain at a time?
  1. What are the exceptions?
1. Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
1. What is a recent technical challenge you experienced and how did you solve it?

#### HTML Questions:

1. What's a `doctype` do?
1. What's the difference between standards mode and quirks mode?
1. What kind of things must you be wary of when design or developing for multilingual sites?
1. What are `data-` attributes good for?
1. Can you explain the difference between `GET` and `POST`?

#### CSS Questions:

1. What is the difference between classes and ID's in CSS?
1. Describe what a "reset" CSS file does and how it's useful.
1. Describe Floats and how they work.
1. What are the various float clearing techniques and which is appropriate for what context?
1. Have you used or implemented media queries or mobile specific layouts/CSS?
1. What are the advantages/disadvantages of using CSS preprocessors? (Sass, Compass, Stylus, LESS)
1. What does ```* { box-sizing: border-box; }``` do? What are its advantages? 
1. What's the difference between inline and inline-block?
1. What's the difference between a relative, fixed, absolute and statically positioned element?
1. What existing CSS frameworks have you used locally, or in production? (Bootstrap, PureCSS, Foundation etc.)

#### JS Questions:

1. Explain how `this` works in JavaScript
1. Explain how prototypal inheritance works
1. What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  1. How would you go about checking for any of these states?
1. What is a closure, and how/why would you use one?
1. What's the difference between `.call` and `.apply`?
1. Explain AJAX in as much detail as possible.
1. Explain how JSONP works (and how it's not really AJAX).
1. Have you ever used JavaScript templating?
  1. If so, what libraries have you used? (Mustache.js, Handlebars etc.)
1. Describe event bubbling.
1. What is the difference between `==` and `===`?
1. Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

#### jQuery Questions:

1. Explain "chaining".
1. Explain "deferreds".
1. Name 4 different values you can pass to the jQuery method.
  1. Selector (string), HTML (string), Callback (function), HTML element, object, array, element array, jQuery Object, etc.

#### Fun Questions:

1. What's your favorite feature of Internet Explorer?


# Coding Questions:
1. Difference between: 
```javascript
function Person(){}
var person = Person()
var person = new Person()
```

1. Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```

1. Question: How would you make this work?
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

1. Question: What value is returned from the following statement?
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

1. Question: What is the value of `window.foo`?
```javascript
( window.foo || ( window.foo = "bar" ) );
```

1. Question: What is the outcome of the two alerts below?
```javascript
var foo = "Hello"; 
(function() { 
  var bar = " World"; 
  alert(foo + bar); 
})(); 
alert(foo + bar);
```

1. Question: What is the value of `foo.length`?
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```
