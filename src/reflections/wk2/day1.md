Day 1 Intro to JS > Var
 
Daily Challenge
 
 
## What is Scope ? 
> where the variables are available for use; locally or globally.
 
 
    var greeter = "hey hi";   <<<<this is globally scoped because it exists outside of a function /////
 
    function newFunction() {      

         var hello = "hello";    
    } 
      <<<<<This is locally scoped because it exists within a function and cannot be accessed outside of that function. This means the variable hello cannot be accessed outside of this function.


 
## What is Hoisting ?
> Hoisting is part of a multi step process that occurs when creating an element with var,let, or const that tells the code to “hoist” the element to be read first before the value is applied.
 
 
## In what cases might you use let vs const vs var?
> let and const are block scoped and can be used instead of var. let can be redeclared 
 
>Const cannot be redeclared but the content within its [] can be added to. Const is great for creating content that will remain consistent like const people:[kate, Mack, jimmy] you can add to the list of names but you cannot change the declaration of people.
