#Front-end Job Interview Questions

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [jQuery Questions](#jquery-questions)
  1. [Coding Questions](#coding-questions)
  1. [Fun Questions](#fun-questions)
  

## Getting Involved

  1. [Original Contributors](#original-contributors)
  1. [Recent Contributors](https://github.com/h5bp/Front-end-Developer-Interview-Questions/graphs/contributors)
  1. [How to Contribute](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/CONTRIBUTING.md)
  1. [License](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/LICENSE.md)
  
#### General Questions:

* What did you learn yesterday/this week?
* What is a recent technical challenge you experienced and how did you solve it?
* Talk about your preferred development environment. (OS, Editor or IDE, Browsers, Tools, etc.)
* Can you describe your workflow when you create a web page?
* If you have 5 different stylesheets, how would you best integrate them into the site?
* How would you optimize a website's assets/resources?
* How many resources will a browser download from a given domain at a time?
  * What are the exceptions?
* What tools do you use to test your code's performance?
* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
* Explain some of the pros and cons for CSS animations versus JavaScript animations

#### HTML Questions:

* What's a `doctype` do?
* What's the difference between standards mode and quirks mode?
* What kind of things must you be wary of when design or developing for multilingual sites?
* What are `data-` attributes good for?
* Can you explain the difference between `GET` and `POST`?

#### CSS Questions:

* What is the difference between classes and ID's in CSS?
* Describe what a "reset" CSS file does and how it's useful.
* Describe Floats and how they work.
* What are the various float clearing techniques and which is appropriate for what context?
* Have you ever used a grid system, and if so, what do you prefer?
* Have you used or implemented media queries or mobile specific layouts/CSS?
* What are the advantages/disadvantages of using CSS preprocessors? (Sass, Compass, Stylus, LESS)
* What does ```* { box-sizing: border-box; }``` do? What are its advantages? 
* What's the difference between inline and inline-block?
* What's the difference between a relative, fixed, absolute and statically positioned element?
* What existing CSS frameworks have you used locally, or in production? (Bootstrap, PureCSS, Foundation etc.)

#### JS Questions:

* Explain how `this` works in JavaScript
* Explain how prototypal inheritance works
* AMD vs. CommonJS?
* What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  * How would you go about checking for any of these states?
* What is a closure, and how/why would you use one?
* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
* What's the difference between `.call` and `.apply`?
* When would you use `document.write()`?
* Explain AJAX in as much detail as possible.
* Explain how JSONP works (and how it's not really AJAX).
* Have you ever used JavaScript templating?
  * If so, what libraries have you used? (Mustache.js, Handlebars etc.)
* Describe event bubbling.
* What is the difference between `==` and `===`?
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

#### jQuery Questions:

* Explain "chaining".
* Explain "deferreds".
* Name 4 different values you can pass to the jQuery method.
  * Selector (string), HTML (string), Callback (function), HTML element, object, array, element array, jQuery Object, etc.

#### Coding Questions:

*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```

*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```

*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```

*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello"; 
(function() { 
  var bar = " World"; 
  alert(foo + bar); 
})(); 
alert(foo + bar);
```

*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```

#### Fun Questions:

* What's your favorite feature of Internet Explorer?

#### Original Contributors:

The majority of the questions were plucked from an [oksoclap](http://oksoclap.com/) thread created **originally** by [Paul Irish](http://paulirish.com) ([@paul_irish](http://twitter.com/paul_irish)) and collectively contributed to by the following: [@bentruyman](http://twitter.com/bentruyman) [@cowboy](http://twitter.com/cowboy) [@ajpiano](http://ajpiano)  [@SlexAxton](http://twitter.com/slexaxton) [@boazsender](http://twitter.com/boazsender) [@miketaylr](http://twitter.com/miketaylr) [@vladikoff](http://twitter.com/vladikoff) [@gf3](http://twitter.com/gf3) [@jon_neal](http://twitter.com/jon_neal) [@sambreed](http://twitter.com/sambreed) [@iansym](http://twitter.com/iansym)
