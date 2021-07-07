Week-1, Day-3
===
   
Today, we studied about HTML and CSS syntax   
This link helped me a lot   
https://developer.mozilla.org/en-US/docs/Web/HTML   
   

Install LiveShare
---
   

First at all, we download Liveshare for team assignment   
We didn't use this today, But we will
   
   
* * *
   
   
   
HTML
---

Basic Structure of your webpage   
We call this the “template”   

<h3> HTML Elements: h1 to h6, p, a, img, div, and span </h3>   

* ```h1``` to ```h6```   
those are make your words more bigger

* ```span```, ```div```
```Span``` and ```div``` are similar   
```Span```is a generic inline container for phrasing content   
They are used to the group of various tags of HTML so that sections can be created and style can be applied to them   

* ```p```   
The ```<p>``` tag defines a paragraph of text   

* ```a```   
The ```<a>``` tag defines a hyperlink, which is used to link from one page to another   

* ```img```   
```img``` tag define a image, you can add image to your website by using this tag   

     
     
  * * *
   
   
CSS
---

CSS is used to position HTML elements on the page and add styles to make them look beautiful and customized   
We refer to CSS files (or similar languages) as “style” files   
   
*	Change element and text colors
*	Give elements a certain height and/or width
*	Positions elements a certain way on the screen
*	Change the font that the text on the page is using
   
   I wrote about CSS already in below link   
https://github.com/comdbstn/Web.Development/blob/main/Day.3.md   



  

 

 * * *    
Team Assignment: Create some simple web pages about movie you like
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
    <h1>Fast and Furious 9</h1>
    <img src="https://images.chosun.com/resizer/IGbI41rAI0wGWxqOA9Xobj3Zo2k=/530x759/smart/cloudfront-ap-northeast-1.images.arcpublishing.com/chosun/G6AL4WMPVD7CXAOZE254R7LX3A.jpg" alt="Vin Diesel and the cast of F&F9.">
    <p>Vin Diesel is <strong>still</strong> making these?</p>
    <p>Only one of us has actually seen this movie, but that's alright. Vin Diesel amazes me every day with his film choices.</p>

    <div>
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

    <div class ="question">
        <h3>Honestly, should Vin Diesel quit this franchise?</h3>
        <form>
            <input type="radio" id="yes" name="names" value="yes" checked>
            <label for="yes">Yes</label>
            
            <input type="radio" id="no" name="names" value="no">
            <label for="no">No</label>
            <br>
            <button>Submit</button>
        </form>
    </div>
</body>
</html>
```

Belew code is CSS code   
```
img {
    display: block;
    margin-left: auto;
    margin-right: auto;
}

h1 {
    color: white;
    text-align: center;
    
}

body {
    background-color: black;
    color: white;
}

.question {
    margin-left: auto;
    margin-right: auto;
    text-align: center;
}
```
