Week-1, Day-2
===
   
Today, we studied about HTML and mainly how to using Git and Github   
And also having ice break time too
   

Announcements and Attendance (9:30AM - 9:40AM)
---
   

* Who was here yesterday who is here today   
* Which students need to catch up?   
   
   
* * *
   
Icebreaker Questions (In Small Groups) (9:40 AM - 10:00 AM)
---

We made team for team project   
and we made first meet in discord voice chat room   
our teams include four person, two people are korean and other two are states   
   
   * * *
   
   
Course Overview & Web Development Overview (10:00 AM - 10:30 AM)
---

*	Light the spark of interest for Web Development!
*	Introduce Web Development Basics
*	Introduce Angular Framework
*	Give Students a Chance to work on projects together and provide feedback about workflow 
*	Provide feedback, support, and encouragement
*	Provide links and resources for further learning and projects in the future!
*	To get to know you students!
*	For the Korean Students (a chance to challenge yourself to practice communicating in English)
*	For the US students a chance to practice communicating with International Speakers of English
*	Practicing the process of using documentation effectively while building projects
     
     
  * * *
   
   
Break (10:35 AM - 10:50 AM)
---


  
 * * *    
Git and Github Setup and Basics (10:50 AM - 12:30 AM)
---

* What is the Git and how to use them?   
  Git and Github is Coffie and Coffie Shop   
  Git is watching your code every time and record it   
  Include What code is changed, who changed, Why changed (Commit)   
  
* Git Command   
Configure your username and email   
(you only need to do this once PER COMPUTER EVER EVER EVER not once per project, since you are configuring this globally on your computer)
Set your global username/email configuration:   
(I recommend using the username and email of your github.com)   
Open the command line.   
Set your username:
```
git config --global user.name "Username"
Set your email address:
git config --global user.email "MY_NAME@example.com"
```

Initialize git in your project directory with the command   
```
git init 
```
Add all of the relevant files to be staged for a commit with the command:   
```
git add
```
Commit all of your staged files with the command below 
```
git commit -m “your commit message”
```

Follow the instructions listed to push an existing repository to your online repository
(Last command links your upstream repo online to your local repo)
(This makes your life easy)   
```
git branch -M master

git remote add origin https://github.com/githubusername/repository-name.git

git push -u origin master
```

For Updating your files after the initial setup:   
After making changes to your project, if you want to update your github.com repository you need to make a new commit, and then push the changes online.   
(you can check the status of your repository with git status)   
```
Step 1: type  git add .
Step 2: Type  git commit -m “commit message”
Step 3: Type  git push
```

If you were working together with other students on a project,   
You would need to do git pull before adding committing and pushing.   
```
Step 1: git pull
Step 2: type  git add .
Step 3: Type  git commit -m “commit message”
Step 4: Type  git push
```
 

 * * *    
Assignment: Create some simple web pages for practice
---
Make a page talking about a favorite book, manga, movie, or TV show   

```
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>Favorite Manga</title>
</head>
<body>
    <h1>進撃の巨人</h1>

    <h2>進撃の巨人</h2>
    <p>This mangga is started when I was studied in elementary school</p>
    <p>And this ended this year</p>
    <p>My half of life is with this mangga </p>

    <h2>What is fun point?</h2>
    <p>Action of this manga is really cool</p>
    <p>We can saw the scene that killing huge peoples</p>
    <p>and process of that is really dinamic</p>

    <img src="https://images-na.ssl-images-amazon.com/images/I/71GNi4Qnf1S.jpg" alt="image">
</body>
</html>
```
