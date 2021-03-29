Day 2 Intro to JS > JavaScript Functions

Daily Challange https://github.com/Melia88/js-tests-loops-and-arrays

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
>Function Declaration defines a named function. Function definition is hoisted. To write; Function keyword followed by the name of the function 

```javascript
//SYNTAX// 
 function name(parameters){
    //statements
}
```
 
>Function Expressions defines a named or anonymous function. Function expressions are not hoisted because the function has no name and cannot be used before it is defined. 

```javascript
//SYNTAX//
 let name = function(parameters) {
    // statements
}
```

>Arrow Function Expression are shorter syntax for writing function expressions and do not create their own *this* value. //SYNTAX//
 let name = (parameters) => {
    // statements
}
 
 
## What is the difference between Parameters and Arguments?
>Parameters are the function definitions.
 
>Arguments are the value the function gets from each parameter.

```js 
const arg1 = true;
const arg2 = false;
 
function twoParams(param1, param2) {
 // function statements
}
twoParams(arg1, arg2)
``` 
 
## What are higher order functions? Can you provide an example?
>A higher order function is a function that accepts and/or returns another function. 


