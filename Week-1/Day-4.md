Week-1, Day-4
===
   
Today, we studied about CSS flexbox   
This link helped me a lot   
https://flexboxfroggy.com/#ko   
   

Use LiveShare
---
   
We use the liveshare program on vs code today   
   
   
* * *
   
   
   
HTML
---



   
   
  * * *
   
   
CSS
---





  

 

 * * *    
Team Assignment: Design your webpage of past week with CSS learned today 
---
Make a page talking about a favorite book, manga, movie, or TV show  

![image](https://user-images.githubusercontent.com/57173871/124698815-949bfe80-df24-11eb-9ad8-b9e272b5c0a0.png)


Belew code is HTML code
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Practice Document</title>
    <link rel="stylesheet" href="styles/main.css">
</head>
<body>

<div class="container">

    <div>
    <h1>Fast and Furious 9</h1>
    <img src="images/Fast-Furious-9.jpg" alt="Vin Diesel and the cast of F&F9.">
    </div>

    <div class="content">
    <p>Vin Diesel is <strong>still</strong> making these?</p>
    <p>Only one of us has  actually seen this movie, but that's alright. Vin Diesel amazes me every day with his film choices.</p>
    <p><a href="https://www.imdb.com/title/tt5433138/">IMDB Page</a></p>
    </div>

    <div class="characters">
        <table>
            <thead>
                <tr>
                    <th colspan="2">Characters</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Vin Diesel</td>
                    <td>Dom</td>
                </tr>
                <tr>
                    <td>John Cena</td>
                    <td>Jakob</td>
                </tr>
                <tr>
                    <td>Michelle Rodriguez</td>
                    <td>Letty</td>
                </tr>
                <tr>
                    <td>Tyrese Gibson</td>
                    <td>Roman</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="question">
        <h3>Honestly, should Vin Diesel quit this franchise?</h3>
        <form>
            <input type="radio" id="yes" name="names" value="yes" checked>
            <label for="yes">Yes</label>
            
            <input type="radio" id="no" name="names" value="no">
            <label for="no">No</label>
            <button>Submit</button>
        </form>
    </div>
</div>
</body>
</html>
```

Belew code is CSS code   
```
body {
    background-color: rgb(48, 24, 24);
    color: white;
    font-family: Sans-serif;
    font-size: 20px;
}

.container {
    /* This is the main div. 
    I don't suggest using align-items just yet.*/

    display: flex;
    flex-flow: column nowrap;
    justify-content: center;
}

h1 {
    color: white;
    text-align: center;
    position: sticky;
    top: 10px;
}

/* Img element does not work with flexbox. */

img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 1000px;
    border: 5px solid white;
}

.content {
    background-color: rgb(221, 221, 221);
    color: black;
    border: 5px solid white;
    text-align: center;
    margin-top: 20px;
    align-self: center;
    font-size: 25px;
    width: 1500px;
}

.characters {

    /* This allows this element to work with flexbox parent. */
    align-self: center;
    text-align: center;
    color: black;
    background-color: rgb(200, 200, 200);
    border: 5px solid white;
    margin-top: 30px;
    /* This code makes Character explain on the center and flex vertical; */
    /* display: flex;
     flex-direction: row; 
    justify-content: center; */
}

.question {
    margin: 30px auto;
    text-align: center;
    align-self: center;
    width: 500px;
    height: 180px;
    padding: 5px;
    font-size: 22px;
    border: 5px solid white;
    background-color: rgb(200, 200, 200);
    color: black;
}
```
