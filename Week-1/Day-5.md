Week-1, Day-5
===
   
Today, we studied about Flexbox project, Bootstrap Library   
   

   
   
* * *
   
   
   
Expamle of flexbox
---

```
<!-- vertical and horizontal alignment using flex -->
<!doctype html>
<html>
  <head>
    <style>
      #parent {
        align-items: center;
        display: flex;
        background-color: lightblue;
        height: 200px;
        justify-content: center;
        width: 400px;
      }

      .child {
        background-color: lightcoral;
        height: 100px;
        margin-right: 12px;
        width: 100px;
      }
    </style>
  </head>

  <body>
    <div id="parent">
      <div class="child"></div>
      <div class="child"></div>
    </div>
  </body>
</html>

```
```
<!-- Element height and centering -->

<!doctype html>
<html>
  <head>
    <style>
      html,
      body {
        background-color: #eee;
        margin: 0;
      }

      #parent {
       
        display: flex;
      /* How would you align The Child to the center of the screen? */


        /* this sets the min-height and width to 100% of the viewheight and width */
        min-height: 100vh;
        min-width: 100vw;
      }

      .child {
        background-color: rgb(50, 167, 89);
        border: 2px solid green;
        height: 100px;
        width: 100px;
      }
      .child img{
        height: 100%;
        width: 100%;

      }
    </style>
  </head>

  <body>
    <div id="parent">
      <div class="child"> 
          <img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/grogu-baby-yoda-the-child-1606497947.png?crop=0.585xw:0.927xh;0.245xw,0.0729xh&resize=768:*" alt="a picture of Grogu aka baby-yoda">
      </div>
    </div>
  </body>
</html>
```
   
   
  * * *
   
   
Media Queries
---   

Media Queries interact with the size of the viewport   
When you change the size of the window, different styles will take effect (depending on the media queries you created)   
*	Documentation   
	https://developer.mozilla.org/en-US/docs/Web/CSS/@media   
*	Syntax Example   
	https://www.freecodecamp.org/learn/responsive-web-design/basic-css/use-a-media-query-to-change-a-variable   
*	Project example   
	https://codepen.io/freeCodeCamp/pen/RKRbwL   




    * * *
   
   
Bootstrap
---
Bootstrap is a popular FREE Styles and Web Components library   
Bootstrap is sometimes called a CSS framework   
Intro to Bootstrap Video (Watch this later): https://www.youtube.com/watch?v=7g8Gg2QVdeU   
   
Bootstrap has 3 main parts   
1.	Default Styles package (Called Reboot)   
2.	A large number of predefined style classes   
3.	Bootstrap Grid System (Which is just utilizing flexbox and custom media queries)   
   
*	Install Bootstrap or Import Bootstrap   
*	Long way: Read the Installation Documentation   
*	Short and easy way: Use a CDN link!   
*	https://getbootstrap.com/docs/5.0/getting-started/introduction/   
   
Libraries are a great way to create beautiful features and components FAST!   
   
Here are some example templates   
https://getbootstrap.com/docs/5.0/examples/   

 

 * * *    
Team Assignment: Login Page 
---
