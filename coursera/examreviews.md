// When sending a message to another computer, the source and destination are specified using?
// answer: IP address

// Which of the following are valid IP addresses?
// answer: 192.0.2.235 & 4527:0db8:85a3:0000:0000:8a2e:0370:7334

// When using TCP, data can arrive out of order?
// answer: false!!

// Which of the following are valid HTTP methods? 
// answer: GET, POST, PUT, DELETE

// HTML describes the structure and content of a web page?
// answer: true

// When you type a website address in your web browser, which protocol is used to find the ip address of the website?
// answer: DNS 

// A web application  is more informative/interactice compared to a website?
// asnwer: interactive

// open dev tools on chrome using F12




// which of the following can be done using the developer tools in your browser? select all that apply
// 

// in software development, a library provdes _____
// a structure for developers to build an applcation with

// in software development, an API is 
// a set of functions that an application component or service can provide (WRONG)
// Reusable pieces of code that can be used by your application (RIGHT)

// which of the following are benefits of using an integrated development environment (IDE) such as Visual Studio Code? 
// syntax highlighting, error highlighting, auto complete, intellsense

/*
to reference a css file in an html document, you use the ____ tag
link

in the following css rule, the 'h1' part of the rule is called the ___
selector

what is the total horizontal margin of the following css rule?
div{ 
width: 10px; 
padding: 20px; 
margin: 40px; 
}
answer: 70px WRONG bc the padding box width is the sum of the content and the padding width
so it should be 30px bc we dont count the padding in the margin

which css property and value change the HTML element to a block-level element?
display: block

which css propert and value change the test to center alignment?
text-align: center

Additional resources
Learn more
Here is a list of resources that may be helpful as you continue your learning journey.

CSS Reference (Mozilla)

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

HTML and CSS: Design and build websites by Jon Duckett

https://www.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189/

CSS Definitive Guide  by Eric Meyer  

https://www.amazon.com/CSS-Definitive-Guide-Visual-Presentation/dp/1449393195/

*/

/*
Module quiz intro to html and css

Which two elements should be added to the html element to make the structure of an html document
body and head <body> and <head>


When using the anchor tag <a>, which attribute determines where the hyperlink links to?
href

When adding an image to a webpage, which of the following is the correct HTML tag?
<img>

How many columns exist in this HTML table?
<table>
<tr>
<td>1</td>
<td>2</td>
</tr>
<tr>
<td>3</td>
<td>4</td>
</tr>
<tr>
<td>5</td>
<td>6</td>
</tr>
</table>
answer: 2 columns

When an html form is submitted to a webserver, which HTTP methods can be used?
GET and POST
NOT PUT OR DELETE

for the following html code, which css selectors can be used to select the h1 element?
<h1 id="title">Hello World</h1>
element selector, id selector, class selector, descendant selector
answer: element selector and id selector

In the following css code, what is teh color: part known as?
h1{
color: purple;
}
css rule, property, attribute or selector
answer: property

based on the css values what will be the margin-box width for the div elements?
div{
width: 10px;
padding-left: 5px;
padding-right: 5px;
margin-left: 5px;
margin-right: 5px;
}
answer: i chose 20px bc width + margin left and margin right
it was wrong, answer was 30px bc margin-box width = 10px + 5px + 5px + 5px + 5px = 30px

true or false, in document flow. block-level elements always start on a new line
true

based on the following css code, how will the text be aligned for the p element?
p {
text-align: justify; 
}
the text will be centered, aligned to the left, aligned to the right, or spread out so that every line of the text has the same width within the p element?
answer: spread out so that every line of the text has the same width within the p element

*/

/*
To view the page in the web browser, the logo should be centered on the webpage?
true or yes

when viewing the page in the web browser on a desktpp, the four menu items display in one column?
no, the 2 div elements take up half the row each when viewed on a desktop broswer

*/

// BOOTSTRAP DOCUMENTATION: https://getbootstrap.com/docs/5.3/getting-started/introduction/
// BOOTSTRAP CHEATSHEET: https://getbootstrap.com/docs/5.0/examples/cheatsheet/

/*
To reference a js script or file in an html document you use the ____
tag
<script> 

if your application requires a library or frame to run, this is called a _____.
dependency

A point at which a websites content and design will adapt in order to prodive the best user experience is called a _____.
breakpoint

The bootstrap grid system always starts with which element?
container

The responsive breakpoint for bootstrap css rules is determined by the _____.
modifier or infix
answer: infix

modifiers are used for the components. Infixes are use for the responsive breakpoints
Additional Resources
Bootstrap Official Website

https://getbootstrap.com/

Bootstrap 5 Foundations by Daniel Foreman  

https://www.amazon.com/Bootstrap-Foundations-Mr-Daniel-Foreman/dp/B0948GRS8W/

Responsive Web Design with HTML5 and CSS  by Ben Frain  

https://www.amazon.com/Responsive-Web-Design-HTML5-CSS/dp/1839211563/

Bootstrap Themes  

https://themes.getbootstrap.com/


*/

/*
which of the following are SPA approaches to serving code?
json object, post request, bundling, lazy loading
answer: bundling, lazy loading


You are developing a SPA, or Single Page Application. Why is it beneficial to use React during your development? Choose all that apply from the list below.

Re-use components.
Correct
Correct! React allows developers to write less code to implement functionality in a web browser, it helps them maintain code in the long term and simplifies testing, and it also allows developers to re-use components when building their applications.

Write less code to implement functionality in a web browser.
Correct
Correct! React allows developers to write less code to implement functionality in a web browser, it helps them maintain code in the long term and simplifies testing, and it also allows developers to re-use components when building their applications.

Simplify testing.
Correct
Correct! React allows developers to write less code to implement functionality in a web browser, it helps them maintain code in the long term and simplifies testing, and it also allows developers to re-use components when building their applications.

Maintain code in the long term.
Correct
Correct! React allows developers to write less code to implement functionality in a web browser, it helps them maintain code in the long term and simplifies testing, and it also allows developers to re-use components when building their applications.


React updates the virtual DOM and compares it to the previous version of the virtual DOM. 
If a change has occurred, only that element is updated in the browser DOM. Changes on the browser DOM cause the displayed webpage to change.   

true or false: react components cannot be reused
false- the great benefit of developing your website with react is that components can be reused so that you
do not need to code every component from scratch.

*/


/*
Knowledge check: introduction to react
dynamic content is faster to generate than static content
false

single page applications allow users to interact with a website without redownloading the entire webpage
true

react applications are built using reusable pieces of code called____
components

to improve performance, react uses a _____ to reduce updates to the browser DOM
virtual DOM (document object model)


react applications have at least 1 component called the ____ component
root


*/

/*
If a library depends on another library, it forms _____
a dependency tree

How many columns does bootstraps responsive grid consist of?
12

To change the style of a bootstrap component, you use ____.
an infix or a modifier
answer: modifier

to improve performance, web servers can keep a copy of dynamic content in a _____
cache

what are the two main approaches for serving code and resources in a single page application called?
packets, bundling, code boxing, code splitting
answer: bundling, code splitting


react is a ______ that can be used to create single page applications
library or framework
answer: library

components allow developers to improve development efficiency by reusing code
true

a react application is built of a tree of components called the component
branch, root, hierachy, library
answer: hierachy

Additional Resources
Learn more
Here is a list of resources that may be helpful as you continue your learning journey.

React Official Website
https://reactjs.org/

Choosing between Traditional Web Apps and Single Page Apps (Microsoft)

https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/choose-between-traditional-web-and-single-page-apps

React Source Code (Github)

https://github.com/facebook/react

Introduction to React.js  

The original video recorded at Facebook in 2013.

https://youtu.be/XxVg_s8xAms

*/

/*
web developers
full stack = front end + back end

Course 1 assessment: Introduction to web development

true/false. In the request/response cycle, the web browser sends the request
true!!!

In the web browser, what is the role of JavaScript?
tp provide interactivity and data processing, to describe the visual look and layout, to describe the content of the webpage
answer: to provide interactivity and data processing

which protocol is used to transfer html documents to the web browser when browsing the world wide web?
HTTP

Which of the following issues does UDP solve? choose all that apply
out of order data, corrupted data, lost data
answer: lost data and out of order data

What will display in the web browser tab for the following HTML document?

answer: little lemon bc its asking about web browser tab and not the webpage tab


True or false, unordered lists are defined in HTML using the <ol> tag
false

in the following css rule, what is the width 50% part of the rule known as?
div{
width: 50%;
}
property, selector or attribute
answer: property

a responsive web page adapts its layout to provide the best user experience based on a users device. The point at which it adapts is known as the ____?
breakpoint 

In the following html, the btn-primary css class is applied to the button element. 
what is this css class known as in bootstrap?
infix, modifier, component
answer: modifier

What is the border-box width of the following css rule?
div{
width: 10ox;
padding-left: 5px;
padding-right: 5px;
border-width:5px;
margin-left: 10px;
margin-right: 10px;
}
answer: 30px

true or false. The libraries which our application depends on can be combined into a single file using code bundling
true

in the following html, bootstrap grid css class col-xl-6 is applied to the div element.
What is part of the class known as?
<div class="col-xl-6">
</div>

infix, modifier, component
answer: component

react stores a repsentation of the browser DOM in memory. What is the representation called?
virtual DOM

react applications are built using reusable pieces of code called?
components

in the web browser, what is the role of css?
to describe the visual look and layout

*/