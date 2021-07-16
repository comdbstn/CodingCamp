Week-2, Day-9
===
   
   
Today, we studied about javascript classes   
   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes    
   
Object Oriented Programming   
---   
   
https://www.youtube.com/watch?v=pTB0EiLXUC8
* * *
   
ES6 Class Syntax
---   
https://www.youtube.com/watch?v=2ZphE5HcQPQ&feature=emb_title   
   
Assignment   
---
https://youtu.be/2ZphE5HcQPQ

Convert the following into ES6 class syntax.   
Then, make another class called Car that extends off of the ES6 Vehicle class you made   
The car class should have the make and model properties   

```
    for (let i = 0; i < vehicles.length; i++) {
        if (vehicles[i].type === 'suv') {
            vehicles[i].range = vehicles[i].mpg * 40;
        }
        else if (vehicles[i].type === 'sedan') {
            vehicles[i].range = vehicles[i].mpg * 15;
        }
    }

    let avgRange = 0;
    for (let i = 0; i < vehicles.length; i++) {
        avgRange += vehicles[i].range;
    }
    
    avgRange /= vehicles.length;

  console.log(vehicles);
  console.log(avgRange);
  ```
