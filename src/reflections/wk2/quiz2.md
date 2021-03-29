# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
Var - Declares a variable with a global scope.

Let - Declares a variable with a local scope.

Const - Declares a variable with a local scope, however it's value cannot be changed after declaration.

```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A function is a reusable set of statements to preform a task or calculate a value.

```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```

S - Single Responsibility a class should be having one and only one responsibility
O - Open / Closed classes should be open for extension but closed for modification
L - Liskov Substitution parent classes should be easily substituted with their child classes without blowing up the application
I - Interface Segregation many client specific interfaces are better than one general interface
D - Dependency Inversion classes should depend on abstraction but not concretion.


```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple is in index 2 because apple is in index 0 and banana is in index 1. This is an array and every array starts at 0.

```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```js
 // >>>><<<<IM NOT SURE QUITE HERE><<<>>>  
 you.push(them)    
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```js
function example (hi)
 if(i=0; i == hi ; i++){
   return true
 }
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```

 That space is called final-expression. To increase i by one on every iteration you apply i++ to the final-expression space.

```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```

DOM stands for Document Object Model


```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
6 PRIMITIVE DATA TYPES: (these are defined by typeof)
undefined : typeof instance === "undefined"
Boolean : typeof instance === "boolean"
Number : typeof instance === "number"
String : typeof instance === "string"
BigInt : typeof instance === "bigint"
Symbol : typeof instance === "symbol"

2 STRUCTURAL TYPES
Object : typeof instance === "object". Special non-data but Structural type for any constructed object instance also used as data structures: new Object, new Array, new Map, new Set, new WeakMap, new WeakSet, new Date and almost everything made with new keyword;
Function : a non-data structure, though it also answers for typeof operator: typeof instance === "function". This is merely a special shorthand for Functions, though every Function constructor is derived from Object constructor.

1 STRUCTURAL ROOT (primitive)
null : typeof instance === "object". Special primitive type having additional usage for its value: if object is not inherited, then null is shown;


 
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
A parameter is basically a place holder in a function that can pass other values into that function. This keeps the function versatile and not bound by a certain list of values.

An argument are those values we want to pass through the parameter

```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```

Primitive values are data that are stored on the stack. A primitive value is stored directly in the location that the variable accesses.

Reference values are objects stored in a heap. A reference value stored in the variable location is a pointer to a location in memory where the object is stored.

```