# Readings: Problem Domain, Objects, and the DOM

## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
 - An object is a way to contain information about a bit of code in something that's like a physical object.
2. What are some advantages to creating object literals?
    - It makes code more readable, easier to manage and more flexible.
3. How do objects differ from arrays?
    - Objects can contain functionality.
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    - Bracket notation is used when you need to access the object's properties dynamicaly.
5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
    - The term refers to an object constructor called 'dog'; the advantage of using this is that you can call on the properities of this object.
``` javascript
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```
## Introduction To The DOM

1. What is the DOM?
    - The Document Object Model.
2. Briefly describe the relationship between the DOM and JavaScript.
    - The DOM is an API made for JavaScript.
