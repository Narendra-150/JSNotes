<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#what-is-javascript">What is JavaScript</a>
      <ul>
        <li><a href="#ecmascript-editions">ECMAScript Editions</a></li>
      </ul>
    </li>
    <li>
      <a href="#intro-to-js-types">Intro to JS Types</a>
      </li>
      <li>
      <a href="#intro-to-conditionals">Intro to Conditionals</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- What is JavaScript -->
## What is JavaScript

### History of JavaScript
	• LiveScript -> JavaScript
	• ECMAScript (ES5, ES6)
		○ ECMAScript (ES) is a scripting-language specification standardized by ECMA International.
		○ It was created to standardize JavaScript.
		○ JavaScript has remained the best-known implementation of ECMAScript.
	• ECMAScript (ES2016, ES2017)


### HTML, CSS vs JavaScript
	• HTML and CSS
		○ Markup language used to describe and define elements within a document.
	• JavaScript
		○ Programming language used to communicate instructions to a machine.




<p align="right">(<a href="#top">back to top</a>)</p>



### ECMAScript Editions


|   Ver ------ |   Official Name --------- |   Description -----                                                                                                                                                                               |
|--------------|---------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ES1          | ECMAScript   1 (1997)     | First edition                                                                                                                                                                                     |
| ES2          | ECMAScript   2 (1998)     | Editorial changes                                                                                                                                                                                 |
| ES3          | ECMAScript   3 (1999)     | Added - regular expressions <br> Added - try/catch <br> Added - switch <br> Added - do-while <br>                                                                                             |
| ES4          | ECMAScript 4              | Never released                                                                                                                                                                                    |
| ES5          | ECMAScript   5 (2009)     | Added - "strict mode" <br> Added - JSON support <br> Added - String.trim() <br> Added - Array.isArray() <br> Added - Array iteration methods <br> Allows trailing commas for object literals |
| ES6          | ECMAScript 2015           | Added - let and const<br> Added - default parameter values<br> Added - Array.find()<br> Added - Array.findIndex()                                                                              |
|              | ECMAScript 2016           | Added   exponential operator (**)<br> Added   Array.includes()<br>                                                                                                                              |
|              | ECMAScript 2017           | Added - string padding<br> Added - Object.entries()<br> Added - Object.values()<br> Added - async functions<br> Added - shared memory<br>                                                    |
|              | ECMAScript 2018           | Added - rest / spread properties<br>  Added - asynchronous iteration<br> Added - Promise.finally()<br> Additions to RegExp<br>                                                                |


- The Original JavaScript ES1 ES2 ES3 (1997-1999)
- The First Main Revision ES5 (2009)
- The Second Revision ES6 (2015)
- Yearly Additions (2016, 2017, 2018)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Intro to JS Types -->
## Intro to JS Types

| Primitive types |                                                                                                                       |
|-----------------|-----------------------------------------------------------------------------------------------------------------------|
| undefined       | Data type <br>Absence of value, meaning nothing is assigned to a variable.                                            |
| null            | Data type<br>Value of nothing                                                                                         |
| String          |                                                                                                                       |
| Boolean         |                                                                                                                       |
| Number          | NaN<br>-> Number type<br>-> Not a Number<br>-> 'Hello' % 10 => NaN<br><br>Type coercion converts Hello to number, NaN |



• Implicit type coercion
	○ "3" can be converted by 3 implicitly
• Strict equality
	○ === and !==
	○ Check both type and value without type conversion


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- intro-to-conditionals -->
## Intro to Conditionals


### Truthy values 
	
		○ Everything else
		○ "null"

### Falsy values
		
		○ False
		○ ""
		○ null type
		○ undefined type
		○ 0
		○ NaN

### if statement
```js
if(x) {   
	If x is true
}
```

```js
### If-else statement
if(x) {   
	If x is true
}else{
	If x is false
}
```

### Nested If-else statement
```js
if(x) {   
	If x is true
}else if(y){
	If y is true
}...
else{
	All if are false
}
```

### Switch statement
```js
switch(x) {    // Each case statement is equivalent to ===
  case 'value1': 
	...
[break]
  case 'value2':      
	...
	[break]
  default:
         ...
         [break]
}
```


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- intro-to-loops -->
## Intro to Loops

### for
```js
for (<start>; <stop>; <step>) {
                                <code-block>
                              }
```

### for...in statement
The for...in statement iterates a specified variable over all the enumerable properties of an object.

### for...of statement
The for...of statement creates a loop Iterating over inerrable objects (including Array, Map, Set, arguments object and so on)

### while
```js
while (<expression>) {
                         <code-block>
                     }
```

### do-while
```js
do {
            <code-block>
    }
while (<expression>);
```

### while
```js
while (<expression>) {
                       <code-block>
                     }
```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- intro-to-functions -->
## Intro to Functions


### Scope

+ Global scope : *Variables defined outside of an function*
+ Function scope

Shadowing => Global variable can be overridden inside a function.
*Preventable by re-declaring the same variable in the function.*

```js
// shadowing
var a = "a";
var b = "b";
function shadow() {
  a = "c";     // shadowing
  var b = "c"; // no shadowing
}
console.log(a); // a
console.log(b); // b
shadow();
console.log(a); // c, shadowed
console.log(b); // b
```



```js
function name(params) {
  // code block
}
```

### Parameter vs argument
		• Parameter: a variable name that appears in the function declaration.
		• Argument: a value that appears in the code when the function is invoked.
	*Parameters are always passed by value.*

### Return value
		• A function always returns some value back to the caller.
		• When return value is not specified, the function will return undefined.
	Eg. console.log

### Function as parameters
***A function passed into another function is called a callback.***


### Named function expressions
```js
var variable = function name() {
  console.log("function body"");
}
variable(); //log msg
name();    // call name() gives an error
```
*it's kind of anonymous function expression*


### Hoisting
		• Before any JavaScript is executed, all function declarations are "hoisted" to the top of their current scope.
		• Functions can be called before they are defined in a scope.
		• Only declaration is hoisted. Assignment is not. So hoisted variables can still be undefined.
		• The best practice is to define functions at the top of the scripts, and variables at the top of the functions.


```js
// only declaration is hoisted		
	
function sayGreeting() {
  console.log(greeting);
  var greeting = "hello";
}
sayGreeting(); // undefined	
```

```js
// equivalent function

function sayGreeting() {
  var greeting;
  console.log(greeting);
  greeting = "hello";
}
```


```js
// hoisting prevents access of global variable

var greeting = "hello";
function sayGreeting() {
  console.log(greeting); // undefined
  var greeting = "hello2";
}
sayGreeting(); // undefined

```

### Function expressions

	• A function stored in a variable.
	• Anonymous function.
```js
var variable = function(params) {
  // anonymous function body
}
variable();	

```	
	• Use the variable name to call the function.
	• Function expressions are not hoisted.
		
```js
sayGreeting(); // sayGreetings is not a function
var sayGreeting = function() {
  console.log("hello");
}

// equivalent code
var sayGreeting;
sayGreeting();
sayGreeting = function() {
  console.log("hello");
}
```


### Inline function expressions

	• Using function expressions that pass a function into another function inline, is really common in JavaScript.
	
```js
function movies(messageFunction, name) {
  messageFunction(name);
}
movies(function displayFavorite(movieName) {
  console.log("My favorite movie is " + movieName);
}, "Finding Nemo");

```	
	• Anonymous inline function expressions are often used for function callbacks that are not going to be reused elsewhere.
	
	

```js
function movies(messageFunction, name) {
  messageFunction(name);
}
movies(function(movieName) {
  console.log("My favorite movie is " + movieName);
}, "Finding Nemo");

```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- intro-to-objects -->
## Intro to Objects
* Objects are data structures that store data, and help track of that data by keys.
* Objects have properties and methods.
* typeof operator: return name of the data type

### Object-literal notation

```js
var umbrella = {
  color: 'red',
  isOpen: false,
  open: function() {
    umbrella.isOpen = true;
  }
}
```

### Data retrieval
* Bracket notation: umbrella['color']
* Dot notation: umbrella.color

### Naming conventions
* Don't wrap property names in quotes.
* Special property names can be put inside quotes. But they are not compatible with dot notations.
* Don't use numbers as first character as property names.
* Don't include space or - in property names.
* Use camel case for multi-word property names.



<p align="right">(<a href="#top">back to top</a>)</p>
