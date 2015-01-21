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

1. What did you learn yesterday/this week?
1. What is a recent technical challenge you experienced and how did you solve it?
1. Talk about your preferred development environment. (OS, Editor or IDE, Browsers, Tools, etc.)
1. Can you describe your workflow when you create a web page?
1. If you have 5 different stylesheets, how would you best integrate them into the site?
1. How would you optimize a website's assets/resources?
1. How many resources will a browser download from a given domain at a time?
  1. What are the exceptions?
1. What tools do you use to test your code's performance?
1. Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.
1. Explain some of the pros and cons for CSS animations versus JavaScript animations

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
1. Have you ever used a grid system, and if so, what do you prefer?
1. Have you used or implemented media queries or mobile specific layouts/CSS?
1. What are the advantages/disadvantages of using CSS preprocessors? (Sass, Compass, Stylus, LESS)
1. What does ```* { box-sizing: border-box; }``` do? What are its advantages? 
1. What's the difference between inline and inline-block?
1. What's the difference between a relative, fixed, absolute and statically positioned element?
1. What existing CSS frameworks have you used locally, or in production? (Bootstrap, PureCSS, Foundation etc.)

#### JS Questions:

1. Explain how `this` works in JavaScript
1. Explain how prototypal inheritance works
1. AMD vs. CommonJS?
1. What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  1. How would you go about checking for any of these states?
1. What is a closure, and how/why would you use one?
1. Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?
1. What's the difference between `.call` and `.apply`?
1. When would you use `document.write()`?
1. Explain AJAX in as much detail as possible.
1. Explain how JSONP works (and how it's not really AJAX).
1. Have you ever used JavaScript templating?
  1. If so, what libraries have you used? (Mustache.js, Handlebars etc.)
1. Describe event bubbling.
1. What is the difference between `==` and `===`?
1. Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
1. Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?

#### jQuery Questions:

1. Explain "chaining".
1. Explain "deferreds".
1. Name 4 different values you can pass to the jQuery method.
  1. Selector (string), HTML (string), Callback (function), HTML element, object, array, element array, jQuery Object, etc.

#### Fun Questions:

1. What's your favorite feature of Internet Explorer?

#### Coding Questions:

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


#### Original Contributors:

The majority of the questions were plucked from an [oksoclap](http://oksoclap.com/) thread created **originally*1. by [Paul Irish](http://paulirish.com) ([@paul_irish](http://twitter.com/paul_irish)) and collectively contributed to by the following: [@bentruyman](http://twitter.com/bentruyman) [@cowboy](http://twitter.com/cowboy) [@ajpiano](http://ajpiano)  [@SlexAxton](http://twitter.com/slexaxton) [@boazsender](http://twitter.com/boazsender) [@miketaylr](http://twitter.com/miketaylr) [@vladikoff](http://twitter.com/vladikoff) [@gf3](http://twitter.com/gf3) [@jon_neal](http://twitter.com/jon_neal) [@sambreed](http://twitter.com/sambreed) [@iansym](http://twitter.com/iansym)
