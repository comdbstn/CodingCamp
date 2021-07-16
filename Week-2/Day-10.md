Week-2, Day-10
===
   
   
Today, we studied about javascript classes   
   https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes    
   
Intro to TypeScript and the Typescript Compiler     
---   
   
We downloaded it!   
![image](https://user-images.githubusercontent.com/57173871/125894955-082107a1-d406-490b-ae9b-8e0d27a6e8b8.png)
   
* * *
Assignment   
---

Play around with the lecture code example   
Add some additional properties to the Vehicle interface   
Create some additional instances of the Vehicle object   


Create some additional methods on the Vehicle class   

* I will upload whem it is made   
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
