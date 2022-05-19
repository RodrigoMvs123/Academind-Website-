
https://github.com/RodrigoMvs123/Academind-Website-/blame/main/README.md

https://raw.githubusercontent.com/RodrigoMvs123/Academind-Website-/main/README.md

https://www.youtube.com/watch?v=i9uAgkKEuNU

# Academind-Website-



What is web development ? 
What do web developers do ?
What exactly happens behind the scene ?
To learn how to build simple and complex websites.
How to write code that is invisible to most users.  
To write code that affects what users see.
To learn how to build web services and to learn what web services do.



   Websites are built from multiple pieces. 
   To observe website pisces and its complexity.

To Enter a WebSite Address ( How it Works ? ) 
   Ex: A Phone Conversation.

Standardize 
HTTPS
HyperText Transfer Protocol Secure 
A Browser WebSite Address. 
To Send a Request to a Remote Computer that Owns a WebSite Address ( CopyRight ) that Will Be Visited. 

Website Code ( Browser Instructions ) 
It sends a response to the requested browser ) 
It is how to bring something on the screen using the internet. 

Client ( Front-end ) 

Server ( Back-end ) 



Which code do we have to write as web developers ?
Instructions that tell the browser what should be displayed on the screen. 
EX:
HTML 
The content and structure of the displayed page  

Hypertext Markup Language  
<section>
<h2>Recommended Product </h2>
<ul>
<li>Harry Potter 1 </li>
<li>Harry Potter 2 </li>
</ul>
</section>


CSS ( Optional  ) 
Cascading Style Sheets
h2{
font size: 20px;
color: purple;
border-bottom: 2px solid purple;
} 


JavaScript 
add interactivity that maybe be needed on the displayed page



https://academind.com/tutorials
      
httpc:// : Hypertext transfer protocol ( secure ) 
academind.com : Domain  ( The human readable address (“identifier”) of a website 
/tutorials: Path A “pointer” ( on a given website ) to a specific resource 


 
Academind ( Website ) Domain 
-> ( IP Address ) 
Request 

<-
Server ( DNS Servers ) - Domain Name System “Map Tables”
Stores Domain < - - >  IP Translation Tables 
The Browser talks to a DNS Server to translate the Domain into IP Address so it can use the IP Address. ( DNS Response the IP Address ) 
->

Response
<-   
Academind ( Website Code Browser Instructions ) 

IP: Internet Protocol / IP Addresses 
A unique identifier (“Address”) of network devices  

Getting started with html & css
Displaying & Styling Website Content 
Module Content 
What is HTML ? Why we use HTML ? 
Understanding HTML Elements 
Styling HTML Content with CSS

How to create a website:
Your computer can act as a temporary development server 

A Browser 
Any browser works but Chrome and Firefox provide particularly good development support 

+ 

A Html File 
A regular text file that just happens to have “.html” as a file extension and contains Html code 

Empty folder
// https:// windows notepad  
<h1>Hello World!</h1>

100 Days of Code 
Day 2 HTML and CSS 


//
code.visualstudio.com 
https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/Heading_Elements
https://developer.mozilla.org/pt-BR/docs/Web/HTML

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
https://developer.mozilla.org/pt-BR/docs/Learn/CSS

Colour Picker 
https://g.co/kgs/J5Q6UP
Live Server ( Extension ) 
Prettier ( Extension ) 
//

// https:// windows bloco de notas 
<h1>Hello World!</h1>

Html is a “Markup Language”  
Instructs the browser about content, its instructs and its meaning 

<h1>Hello World!</h1>
html element: Elements tells the browser which kind of content is displayed ( headings, text, images, lists, buttons, … )  

Html Tags 
<h1>>: Opening tag
</h1>: Closing tag 
Hello World: Element name


Which html elements exist ? 

There are many available HTML elements: Because there are a lot of things you can describe. EX: https://academind.com/. 


You will learn a lot of html elements in this course 
You can then also use resources like MDN to look up all available elements ( e.g. for niche use case ) 

Why HTML Elements? 
Without extra annotation, content often has no clear meaning 
EX: Hello World ! ( Can you tell that this should be a title ? ),
with the <h1> tags, it is absolutely clear that this should be a title! 
It is like writing just plain, unformatted text in Word.
“Telling” the browser that something is a title / subtitle / image / … allows the browser to present that content correctly. 
To regular visitors of your website 
To search engine crawlers 
To visitor using assistive technologies (e.g. screen readers ) 

//
<!DOCTYPE html> 
<html>
 <head>
<style >
h1 {
font-family: sans-serif;  
text-align: center; 
color: rgb(39, 35, 35)
}


p {
font-family: sans-serif;
text-align: center;
color: rgb(39, 35, 35) 
}
</style>

</head>
 <body>
<h1>Max ' Challenge for Wednesday, August 4th</h1>

<p>
Learn about the basics of web development - specifically dive into HTML & CSS.
</p> 

<p> 
I´ll achieve this goal by diving into 
<a href="https://www.google.com">more learning resources.</a>
</p>
</body>
</html>

//

Working with Global CSS & CSS Selectors 

p -> A Css selector. In this case: A “type selector” Selects by element type. 
p {

color #534b4b // A CSS property + value. In this case: The color property and a hex color code. 

}
CSS Rules 

The Anatomy of a Valid HTML Document ( Page ) 


 Html Version 
<!DOCTYPE html>  
Page Metadata 
<html>
<head>
<title>My Page</title>
</head>

Page Content 
<body>
<h1><Welcome/h1>
</body>
</html>

1993: HTML1
1995: HTML 2 
1997: HTML 3
1997: HTML 4 
2014: HTML 5 

100 Days of Code 
Day 4 - CSS Deep Dive & Splitting Code


Css Sizes & Size Units 

Some Css properties expect numeric values( e. g. a size value for the front-size property ) 
For Css properties that expect a size ( dimension ), you got different options for defining that size

Absolute 
px ( a device independent pixel on the screen, low resolution device and high resolution device ) 
Relative rem, % 


https://fonts.google.com/
fira sans regular 400 
bold 700

100 Days of Code 
Day 5 - Working with Images 



Code
// 

<!DOCTYPE html> 
<html lang="en">
 <head>
<meta charset="UTF-8">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&display=swap" rel="stylesheet">

<link href="styles/shared.css" rel="stylesheet"/>
<link href="styles/daily-challenge.css" rel="stylesheet"> 
<title>My Daily Challenge</title>
</head>
 <body>

<img src=" images/https://img.freepik.com/vetores-gratis/trofeu-de-ouro-com-a-placa-de-identificacao-do-vencedor-da-competicao_68708-545.jpg?w=2000" alt="A trophy">


<h1>Max ' Challenge for Wednesday, August 4th</h1>
<p id="todays-challenge">
Learn about the basics of web development - specifically dive into HTML & CSS.
</p> 
<p> 
Explore the <a href="full-week.html">full week.</a>
</p>
</body>
</html>

//


//
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Upcoming Challenges</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&display=swap" rel="stylesheet">
<link href="styles/shared.css" rel="stylesheet"/>
<link href="styles/https://full-week.css" rel="stylesheet"/>
</head>
<body>

<h1> My Upcoming Challenges </h1>

 <a href="file:///C:/Users/Matheus/Desktop/Rodrigo/WebSite%20Academind/index.html">
<a> View Today´s challenge </a>

<p> Reapt what I learned about HTML & CSS </p>

<p> Do the exercises on HTML & CSS </p>

<p> Dive deeper into HTML and & CSS and build more complex websites </p>

p {
font-family: 'Fira Sans', sans-serif;
color: rgb(39, 35, 35) 
}

</body>
</html>

//

//
https://img.freepik.com/vetores-gratis/trofeu-de-ouro-com-a-placa-de-identificacao-do-vencedor-da-competicao_68708-545.jpg?w=2000
//

//
body {

    background-color: rgb(233, 215, 207);
    text-align:center
    color: rgb( 83, 75, 75 ); 
}

h1{
    font-family: 'Oswald'; sans-serif;

    p {
        font-family: 'Fira Sans', sans-serif; 
   
    }

a {
 font-family: 'Fira Sans', sans-serif;
 text-decoration: none;
color: rgb(167, 1, 78) 
}


a: hover {
text-decoration: underline;
}

//

//
body {

margin: 50px;

}


h1 {
font-family: 'Oswald', sans-serif;  

}


p {
font-family: 'Fira Sans', sans-serif;

}


img {
width: 200px;
height: 200px;
border-radius: 100px;
}


#todays-challenge {
color: rgb(170, 96,83);
font-weight:bold;
font-size:52px 
}

//

//
body {

    background-color: rgb(233, 215, 207);
    text-align:center
    color: rgb( 83, 75, 75 ); 
}

h1{
    font-family: 'Oswald'; sans-serif;

    p {
        font-family: 'Fira Sans', sans-serif; 
   
    }

a {
 font-family: 'Fira Sans', sans-serif;
 text-decoration: none;
color: rgb(167, 1, 78) 
}


a: hover {
text-decoration: underline;
}



//

   
   
100 Days of Code 
Day 06 
Beyond the CSS Basic 
100 Days of Code - Web Development  Bootcamp - Full Course: Day 1 - 8

Module Content 

Diving Deeper into HTML and CSS 

Lists & Website Structure with Semantic Elements
Containers, Cascading, Inheritance & Specificity 

The Box Model 

Live Server ( Extension ) 
live server started at port: 5500
http://127.0.0.1:5500/full-week.html


Parent and Children Relationship
Inspection 
Anchor Tag 
Colors 
Select or To not Select Color 
Inheritance 
( Select ) container rules apply to descendants  

Cascading Style Sheet 
Multiple rules can be applied to the same elements 

Specificity 
More specific´s rule wins over less specific selector 

100 Days of Code 
Day 7 
Box Model
Classes 
Elements Deep Dive 

The CSS Box Model 

Content 

Padding 
Border 
Margin 
HTML 
<p> The Box Model</p>

CSS
Top 
Right 
Bottom
Left

p{
padding: 2px 5px 2px 5px;
border: 2px dashed black;
margin: 8px 6px;
margin: 8px 
}


HTML
https://developer.mozilla.org/pt-BR/docs/Web/HTML 
https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Colors/Applying_color 

Adding Structure to a Webpage 
<body>
<h1></h1> [<header>]

[<main>]
<ol>
<li>...</li>
…
</ol>
[<main>]

<p>...</p> [<footer>]

</body>


Selectors and Combinators 

Selectors
Type
Elementname

ID
#id

Group 
Elementname
Elementname

Class 
.class


Combinators 

Descendent 
li p 
All p with li as ancestors 

Child 
h2 > p
Only p which are direct children of h2 


Block ( Level ) Elements vs Inline Elements 

<p>This is a block element</p>
<p>This <a>link is an inline element</a>nested into a block element</p>
new line
full width 
block yes 
inline no 

Common Inline Elements 
https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/code
https://developer.mozilla.org/pt-BR/docs/Web/HTML/Inline_elements

<a> Link to other website/page of a current website
<button> clickable button to submit forms 
<img> embed image into HTML page
<span> Non-semantic inline container to mark-up the text 

100 Days of Challenge 
Day 8 - Your Challenge 

// 
   
<!DOCTYPE html> 
<html lang="en">
 <head>
<meta charset="UTF-8">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&display=swap" rel="stylesheet">

<link href="styles/shared.css" rel="stylesheet"/>
<link href="styles/daily-challenge.css" rel="stylesheet"> 
<title>My Daily Challenge</title>
</head>
 <body>

<main>

<img src=" images/https://img.freepik.com/vetores-gratis/trofeu-de-ouro-com-a-placa-de-identificacao-do-vencedor-da-competicao_68708-545.jpg?w=2000" alt="A trophy">

<h1>Max ' Challenge for <span>Wednesday, August 4th</span></h1>
<p id="todays-challenge">
Learn about the basics of web development - specifically dive into HTML & CSS.
</p> 

</main>
<footer>
    Explore the <a href="full-week.html">full week.</a>   
</footer>
</body>
</html>

//
   
   
   //
   
   
   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Upcoming Challenges</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@700&display=swap" rel="stylesheet">
<link href="styles/shared.css" rel="stylesheet"/>
<link href="styles/https://full-week.css" rel="stylesheet"/>
</head>
<body>
<header>
    <h1> My Upcaming Challenges </h1>
    <p id="description">These are my gols for the next days</p>
    <a href="file:///C:/Users/Matheus/Desktop/Rodrigo/WebSite%20Academind/index.html">
        <a> View Today´s challenge </a>
</header>
<main>
<ol>
<li>
    <h2>Tuesday, April 2nd</h2>
    <p>Reapt what I learned about HTML & CSS</p> 
</li>
<li class="highlight-goal">
    <h2>Wednesday, April 3rd</h2>
    <p>Do the exercises on HTML & CSS</p>
</li>
<li> 
    <li class="highlight-goal">
    <h2>Thursday, April 4th</h2>
    <p>Dive deeper into HTML and & CSS and build more complex websites</p>
</li>
    <h2>Friday, April 5th</h2>
    <p>Practice advanced HTML & CSS concepts</p>
</li>

 </ol>
</main>
</body>
</html>

   
 //
   
   
   //
   body {

    background-color: rgb(233, 215, 207);
    text-align:center
    color: rgb( 83, 75, 75 ); 
}

h1{
    font-family: 'Oswald'; sans-serif;

    p {
        font-family: 'Fira Sans', sans-serif; 
   
    }

a {
 font-family: 'Fira Sans', sans-serif;
 text-decoration: none;
color: rgb(167, 1, 78) 
}


a: hover {
text-decoration: underline;
}
   
   //
   
   
   //
   
 header {
    margin-bottom: 64px;
}


body {

    background-color: rgb(233, 215, 207);
    text-align:center
    color: rgb( 83, 75, 75 ); 
}

h1{
    font-family: 'Oswald'; sans-serif;

    p {
        font-family: 'Fira Sans', sans-serif; 
        margin-bottom 36px;
    }


}

/* header p {
    margin-bottom: 36px;
} */

a {
 font-family: 'Fira Sans', sans-serif;
 text-decoration: none;
color: rgb(167, 1, 78) 
}


a: hover {
text-decoration: underline;
}

h1 {
   font-size: 48px;
   color:rgb(71, 62, 62);
   margin: 0;
}

#description {
    margin:12px;

a {
padding: 12px 48px;
background-color: rgb(167, 1, 78);  
border:1px solid rgb(167, 1, 78);
color:white;
border-radius: 4px;
font-size: 24px;
display: inline-block;
margin: 0;
}
}       

a:hover{
    background-color:rgb(180, 12, 90);
    text-decoration: none;
}
}


ol {
    list-style: none;
    width: 500px;
    margin: 36px auto 0 auto; 
    padding: 0;
    }
    


li{
   padding:16px;
   box-shadow: 1px 1px 4px rgba(0, 0, 0, 0.2);
   margin: 32px; 
   background-color: rgb(223, 136, 124);
   border-radius: 6px;
}

h2{
    color: rgb(78, 13, 5);
    font-family: 'Oswald'; sans-serif;
}

main p {
    margin: 12px;
    color: rgb(71, 29, 22);
}

.highlight-goal {
    background-color: rgb(226, 115, 101);
}
  //
   
   
   //
   
   
   https://img.freepik.com/vetores-gratis/trofeu-de-ouro-com-a-placa-de-identificacao-do-vencedor-da-competicao_68708-545.jpg?w=2000
   
   //
   
   

 
   

   
   
