# teched-102
this repo contains 102 course material

102 
Lesson 1 | Class 1 16.01.23
Github
A platform where you can write code, an online space,  allows you to build code and practice
content management for versions  - make v1.0 but working on V5 can make that live and test it.  You can save different versions of your code so if your new version doesn’t work you can look back at your previous/earlier version and see why.
online repository  - project folders 
versioning  - v1.0, v1.1, v1.2 etc 
READ.ME file is very important 
Markdown .md is very specific for Github and Discord – computer doesn’t understand it.
Different way of formatting text so differet browsers understand the READ.ME file.  99% of the time a .md file will be a READ.ME file
Can use # or code e.g. <h1></h1> or # (heading 1 – the biggest, through 2,3,4,5,6
Combination of documentation, has own syntax and rules, combination of text and coding 
https://www.markdownguide.org/basic-syntax/
Request response lifecycle 
A question = a query 
Google requests information  - query – asks the database DB.  DB will respond and server sends info to Google
The DB is not a process – only stores and access rights needed
Lesson 1 | Class 2 17.01.23
Computer language is binary – 1 and 0 – ASCII, machine code, understood by the computer
Charles Babbage and Ada Lovelace then Alan Turing (film The Enigma Machine)
Tags
<oi>
<li>
<src>””</src>
<p>
<br>
<a href>
Structure of coding
Head (the brain)
Body (your appearance)

Semantic tags 
Commit to new file = save 
# in .md is <h1>
Hypen is bullet points
Pair programming  = geeky speak for collaboration 

Lesson 2 Lab 1b 
Class 3 18.01.23
Configuration and Terminal
Need tools to do web development front-end and back-end
Developer tools
Config – set up so everything works
Toolkit
Development
Testing
Production 
These are categories of toolkit
Repl.it is a code editor, a platform where you can write and run code
VSC is a platform
Terminal – not programming language, code editor to work with computer. Create a folder, move a folder – something you want to do in a computer
Terminal commands? 
Dir – directory
Cd – present working directory- where I am in the computer
Linux is the operating language of the computer
MERN is the library of js
80% of developers language – the concepts are the same
Different languages are better for different things 
js better for web, only language that works on a web browser.  General language used for anything
Pyhon – better for machine learning
Rust – cloud servers


Lesson 4 (? Check)
Class 4 19.01.23
VSC
View the terminal 
ls – lists – see how many files and folders you have as it lists the contents of the directory you are in 
pwd – present working directory
cd(space) – name of folder
cd(space).. – takes you back to parent folder
Task? 
Using the VSC terminal 
Create new file
Create new folder 
Git and Github
Git interacts with Github – twins, Git is a friend of Github.  Git is the dependency where you can work with Github
Together is a version control system
Repository – repo – project in a folder, other people can contribute to my repo = public
If private I have to give permission
Dependency
Code to facilitate working with website, app or whatever – VSC 
A super power, facilitates getting e.g. the weather 
Analogy, a mobile phone facilitates calling a friend, a toolkit that gets the tools for you
Node is a dependency
npm – node package manager – a registry of all the tools on the internet 
js world
other worlds e.g. python
node Is the toolkit that goes to the npm – node is the dependency
dependency goes to the npm to get the tools
Terminal on my computer is Command Prompt 

Lesson 5
Class ? 20.01.23
Node is a framework
Command on node system
Command prompt
Making a new folder
Making a new file
Moving from one to the another
npm 
dependency
extensions or add-ons – can download and they add extra functionality, add support for other tools.
Collaborating on Github
This was a task 
Used branching – main branch
Pull request
Bring changes/synch changes to my branch
When someone makes a change you can merge to your branch
Fork
Like branching but without editing access
A fork – a new repository without affecting the original.  The person who created the fork and made changes sends a message to the author/originator to ask if they want to merge.  Author can look at changes and make a decision as to whether to merge. Preview the merge before commit
Click on READ.ME and click on file changed and what has changed is in blue
You can do Open Source but not give write access and still Open Source so people can suggest changes that request via Pull Request to V

Gitinit
Git initialization – starting the process of starting git with github 
Creating a secure connection between git and github
Local machine with your github
VSC to github via git

Class 5 (3 on syllabus) 23.01.23
Repos – folder with files – github repos – a collection of files you’ve told git to pay attention to 
VSC is the Terminal 
Task (?)
Clone github into VSC
Go to folder class-102
Click code, under HTTPS
Copy code
Go to bottom right terminal – go to folder and click desktop then type git(space)clone(space) and paste link from git
Cd(space) click TAB button type cls (clear screen) gets a clear space in VCS
Type ls(TAB) then (TAB) again and lists my folders and o get to the one you want press ENTER or TAB
All this to open the folder in VSC 
VSC is the DEPENDENCY for github.
Can’t write code in github – just files and folders
VSC write the code
Github ACP
Git(space)add(space).(press enter)
TERMINAL is a space for configuring things 
Git(space)commit(space)-m
To push changes to github
Git push 
(I don’t understand this very well) 

Class 4 24.01.23
Submit a github repo in 101, 201 section of CANVAS
Wireframe
Rough sketch, hand drawn send to front end developer to do a mock-up, then send to someone who creates a prototype
3 stages  - 1 and 2 are hand-drawn 
Wireframe   
mockup  
prototype 
time consuming and difficult, legal reasons – copyright? 
Structuring a webpage
HTML
used Repl.it
Use VSC
<!DOCTYPE html> only use once, a document for html
<html>
<head>
Configuring for website
</head>
<body>
Where write something
</body>
Anchor tag takes to another page 
What is <h ref> relation to anchor tag? It’s an attribute, a feature
<a  - anchor
<h ref reference 
<a hrefwww.youtube.com/click here</a>
<img – image
<src – source
<img src=”image address here”</img>
Rendering means display – converting code to a webpage
Task – submit for LAB4, Class 8 (102 repo index.html)
Bullet list in html
<oi> is ordered  - numbered - list 
Table in html
<table>
<tr> is table row
<th> month</th> = table header
<th>savings</th> = table header
</tr>
<tr>
<td>January</td>
</tr>
</table>
DIV tag 
<div> in a div you can make anything, it’s a section
Can have other DIV tags, helps people who read the code 

Class 10 27.01.23
First stage html part, second part is css
DIV – divisiob between parts/areas of the page
CSS – styling
Attribute – use to style “ “ 
Div style=”border:1px solid black;”>
Style give to opening tags not the closing tags
; gives the next value and inside quotes e.g. background color
Nested – like a nesting or a Russian Doll, all exists inside 
Saturation or transparency – alpha channel (?)
For color can use rgb or Hex format
WEBSITE – ‘flat ui colors’ gives lovely colours and palettes

Class ?  Lesson ? 30.01.23
How do we put js in html? 
With <script></script>tag 
Use // inside the SCRIPT tag for commenting in js – for me to understand what I have done
Render  - how code is displayed on the front end 
Console (screwdriver icon)
Terminal area in the browser.  Space available allows you to check and run code for js
Console.log – use this write something you want e.g. explain
Another tool to check code is ‘alert’
ALERT
Check if the page has loaded or not 
VARIABLE
Like a box
Var firstName=prompt(‘enter your name’); console.log(firstName+’is cool’);
A space you can make in the computer
Can only use a particular variable once for a value in one website as computer commits it to memory 
//condition
If this then that 
TASK 
Age – hey welcome
Back 
Location – hey welcome
Back 
//put text in
Class 9? Day 12 12 31.01.23
Js
<head> for configuring of js
<H1>heading 
Console.log – log a form of writing 
Browser – console  - inspect code
Var – a variable is a memory name for computer
Debugging – removing errors
Var prompt(‘enter your name’)
Conditions - if and else 

Event, Event listener, event handler
Event – on a website, when human interacts with computer <button onclick=”execute blah blah”{
Event listener – not a function, piece of code initiating when something happening – on click, on refresh, on mouseHover
Calling a function – talk to the function to do something, when event listeners is event handler calling a function – talking to function as event happened and event handler to do something
Eventhandler – a function, executes, a block of code that handle what happen when an event occurs, 
DON’T USE LOCALTION, just LOC as this means something different to the computer
Task
Create a button
Add an event listener to it 
Create an eventhandler with a proper name
Execute some piece of code when the event occurs in console.log
Update github READ.ME repo – v posted on Discord
My Discord post on 31.01.23 is wrong.  Repl.it 21.01.23 is correct

Body is front-end of website.  Html inside <body>
Configuration <head</head>, <script></script>, <style></style> and others
Class 8, part 2 Day 13 01.02.23
Code, READ.ME is github
CANVAS – paste links to github
Put links into CANVAS and github every 2 days
Js needs to be hosted by html as can’t exist outside browser
<!DOCTYE html>
CSS
Style attribute inside the <h1 style =”color red:”?
Learning about identities – ids </h1>
js in <script> tags
<style><h1{color:red;}</style>
Create a class (a group of the same things) to make changes to code where you have lots of it and more efficient than by hand. <style>.fizzwizz{color:green;font-family:claibri:
To create another variation can use another class
Create a class called ‘fruit’
.fruit{coloe:blue;font-family:cursive;border:1px dashed green;text-shadow:2px 10px red;}
Can check if repl.it gone wrong check if code is ok in VSC
<style> and CSS
Class posted on Discord 01.02.23 – pinned
Another way to create a unique is create and id, use individually, unique, one time
<h1 id=’my mind goes blank”{color:purple;font-family:fantasy:}
.document GetElementById (“My mind goes blank”)
Id used for styling CSS and js
js very powerful and can affect html

Day 14 Class 9 02.02.23 - revision
Markdown
READ.ME
Dependency 
Class 3
Git is dependency to connect to github, for versioning
Github – version control, branches, control management, system, push changes
Forks
Node is platform
Repl.it – code editor online – render
VSC – local machine editor:cd, pwd,ls,mkdr
Class 4
Wireframe, mock-up, prototype (structure, color, blueprint to client)
Html to make website
CSS to style
DIV put into different sections of website – divisions
CSS and color layout
Style attribute – in line styling or colors, HEX, name f color, RGB
js only used in web browser makes html manipulate tags on page
console.log 
variable – define and memory remembers the value
conditions – if, else
terminal – for file management commands
script tags in body tag
js at the bottom after the last one
#document
Element + tag mean the same objects in a document
CHECK DISCOD POST 02.02.23
Loops – for is a loop
Repeats
3 ways writing js
//function code here
(for (1;2;3){
//1)var i = 0;
//2) i is <60
//3) i++
For (var i-0:i<60;i++{
Code above, starts with 0 and adds 1 all the time repeating up to 59 in console log, will stop the loop at 59 as <60
If want to do 5 things use a loop rather than repeat the command yourself
Line 34-37 in { is the loop
19.52 Carla posted a working lop in Discord
All progamming language inbuilt method, has an array – a list of records
//write the logic
Console.log(i);
Array
Var name = [“George,””Jane,””Paisley,”£Carla,””V”]
Memory efficient drawio screenshot insert here 
S.no – serial number
0, 1,2,3,4…….same no.
Serial no (index)
Data (value)
0
George
1
Jane 
2
Paisley
3
Carla
4
V


Array is in square brackets [ ]
Name [index]
Name [1] is my name
What if 100 names?
Loop -basic building block for any application
After screenshot see discord 20.13
To make this more effiecit e.g. if have 97
Inbuilt mrthod – length
Array js – uses square brackets 
Use .length rather than no 5 or fowever many as array may continue to grow by automation and so doesn’t need amending 
Length is a property of an array – see screenshot in loop section
Loop could add to an array, delete data, replace dates
No of values in brackets 
See Discord post 20.28
For loop e.g. google search says how long it took to search 




































##### class 04 was about html.  

I learnt about *structuring a web page using html*.  This was done in Replt but in future it will be in VSC.

I learnt the following html tags

- Doctype html will only use once in a file
- html
- head is for the header
- body where write something for your page 
- h1 is the biggest heading and continues in ascending numbers but the size of the heading gets smaller
- 
