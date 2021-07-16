Week-2, Day-8
===
   
Today, we studied javascript.   
honestly, I already know the basic syntax about it   
because I already learn about it personally with Nico's class   
And I know how to programming in C# because I was gamedeveloper   
So JaveScript is also easy to understand   
I think JavaScript will be my main language, because It can make web, app, Backend, Frontend... evrything!   
Identity of developer is that they can make anything when they have some idea.   
From that point of view, JavaScript is best language.    

* * *
   
   
   
   
JavaScript Syntax
---
* Variables (var, let, const)   
```var``` is function scoped when it is declared within a function.   
This means that it is available and can be accessed only within that function.   
var variables can be re-declared and updated   

   ```let``` is now preferred for variable declaration.   
   It's no surprise as it comes as an improvement to var declarations.   
   It also solves the problem with var that we just covered.   
   Let's consider why this is so.   
   
   Variables declared with the ```const``` maintain constant values.   
   ```const``` declarations share some similarities with let declarations.   
   
* Math/Operators   
Math is a built-in object that has properties and methods for mathematical constants and functions.   
It’s not a function object.   
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math   
   
* Conditionals   
Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value.   
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#logical_operators   



   
   
  * * *
   
   
Code example
---
   
```
// Objects can be declared using let or const, just like any other data type
 
const myObject = {
  propertyOne: 'value one',
  propertyTwo: 'value two',
  propertyThree: 'value three'
}
 
// You can access and modify properties on objects using either dot syntax or bracket syntax
 
// Dot syntax
 
myObject.propertyOne = 'a new value for property one';
console.log(myObject.propertyOne);
 
// Bracket syntax
 
myObject['propertyTwo'] = 'a new value for property two';
console.log(myObject['propertyTwo']);
 
// Object methods: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object
 
 
// Arrays in JavaScript are just an ordered list of values. Arrays can contain any number of primitive types or objects and arrays
 
const myArray = [1, '2', { prop: 1234 }, true, [1, 2, 3]];
 
// Arrays are indexed starting at 0, you can access an element in an array using bracket syntax and a number representing the index you're trying to access
 
console.log(myArray[0]);
 
// You can iterate over arrays several different ways
// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration

```

   
* Arrays and Objects Practice assignment For extra practice   
```
/**
 * A SUV can hold 40 gallons of gasoline.
 * A sedan can hold 15 gallons of gasoline.
 * 
 * Assignment
 *  - Add a "range" property to each of the vehicles in the array. 
 *  - Assigning the "range" property must be done using a function.
 *    - This property will be calculated using the vehicle's MPG and the 
 *      gallon size (listed above).
 *  - Print the vehicles array with the new "range" property to the console.
 * 
 * Brownie points:
 *  - Find the average "range" of all the vehicles and print that to the 
 *    console
 */
 
 
// Note, this is an Immediately Invoked Function Expression or IIFE will call the function automatically when the code is run on node
//https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/object-oriented-programming/understand-the-immediately-invoked-function-expression-iife
 
(function() {
  const vehicles = [
    {
      year: 2017,
      make: 'Chevrolet',
      model: 'Tahoe',
      type: 'suv',
      mpg: 23,
      // range: mpg * fuel capacity
    },
    {
      year: 2019,
      make: 'Subaru',
      model: 'Outback',
      type: 'sedan',
      mpg: 33,
      // range: mpg * fuel capacity
    },
    {
      year: 2015,
      make: 'Toyota',
      model: 'Avalon',
      type: 'sedan',
      mpg: 30,
      // range: mpg * fuel capacity
    },
    {
      year: 2020,
      make: 'Mercedes',
      model: 'GLA 250',
      type: 'suv',
      mpg: 34,
      // range: mpg * fuel capacity
    },
    {
      year: 2018,
      make: 'Mercedes',
      model: 'C 300',
      type: 'sedan',
      mpg: 25,
      // range: mpg * fuel capacity
    }
  ]; //This is the end of the vehicles array
 
  // Write your code here
  // you can use console.log(); if you need to log text to the console
  
  
})
();
