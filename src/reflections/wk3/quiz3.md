# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
The four pillars of OOP:
  Encapsulation: accomplished when each object maintains a private state, inside a class.

  Abstraction: an extension of encapsulation. The process of fetching/removing/selecting the user information/data from a larger pool to show only the relevant details to the object. Finding things that are similar in your code and providing a generic function or object to serve multiple places/with multiple concerns.

  Inheritance: the ability of one object to acquire some/all properties of another object.

  Polymorphism: the condition of occurring in several different forms. That's exactly what the fourth and final pillar is concerned with – types in the same inheritance chains being able to do different things


```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
name.tim

```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is the process of storing like data in a constructor where it is kept private until it is called by a method within it.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The 'S' in SOLID stands for the single responsibility principle.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the blueprint, like the concept and idea.

An instance of a class is the physical object of a class. 
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
A Proxy object is a essentially photocopy of an object making it a duplicate but not the real thing.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
MVC's purpose is to seporate the display and the data which allows each to change without affecting the other. It also makes the processes more efficent so load time is better.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controllers job is to call functions based on what it recieves from the DOM(like the button the user clicked), interpret and clean up the data and then send it to service.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Services job is to change and minipulate the data.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
The Model is what hold the blueprint for the object data.
```

