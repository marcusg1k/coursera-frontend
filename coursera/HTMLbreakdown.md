<!DOCTYPE html>
This notifies the web browser that it is an html document

<html>
this is known as the html root element
inside these html tags we have 
<head>
nothing inside the head tags is going to be displayed in the web browser
in the head tag you always create the title element
<title> Marcus Webpage </title>
can also link to css files and to find meta tags in the head section
meta tags can specify the description of the webpage, key for search engines
</head>
<body>
content of webpage goes here in the body tag 
<h1>
Marcus Menu
</h1> 
<h2>
Food option 1
</h2>
<h2>
Foot option 2
</h2>
</body>

</html> 

HEADINGS:
<body>
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
</body>
headings will allow you to display titles and subtitles on your webpage

PARAGRAPHS:
paragraphs contain text content. 
<p>
This paragraph 
contains a lot of lines
but they are ignore
because we have no breakpoints or linebreaks. 
when we add <br> to the end of a line
then we can see the line finally <br>
break.
</p> 

Strong: 
strong tags can be used to indicate that a range of text has importance. 
<p> 
No matter how much the dog barks: <strong> dont feed him chocolate </strong>
</p>
it pretty much bolds whatever is in the strong tags

Bold tags can be used also to draw attention
<p>
The primary colors are <b> red </b>, <b> yellow</b> and <b> blue </b>. 
</p>
this is going to bold red, yellow, and blue

Emphasis tags exist also 
<p>
Wake up <em> now </em>!
</p>

Italic tags also
<p>
The term <i> HTML </i> stands for HyperText Markup Language. 
</p>

we can also use lists: 
<ul>
<li> eggs </li>
<li> milk </li>
<li> bacon </li>
</ul>

list can be ordered 1. 2. 3. by using the <ol> tag
<ol>
<li> Rocky </li>
<li> Rocky II </li>
<li> Rocky III </li>
</ol>

websites are built using multiple webpages linked together, for this we use Anchor tags
<a href= "index.html"> </a>

image tags are used in html to reference images
<img src="kobe.jpeg" width="240" height="125"> 

we are adding tables to our html page
<table> 
<tr>
<td> something </td>
<td> something 2 </td>
</tr>
</table>
<style>
    table, th, td {
        border: 1px solid black; 
        border-collapse: collapse;
    }
    </style>
    this is how you input a border for style purposes

what are forms? 
Forms are used in websites to input information like login info, credit card information, and you can assign them actions. 
When you enter data in a form, and HTML form then sends an HTTP request that contains the data to the server. 

you define form using 
<form>
you can also do 
<form action = "registration" method="POST">
add a label above it so the user on the site knows what it needs to input in the text box below
<label for="username">Username:</label><br> br is our line break
<input type="text" name = "username" > does not need a closing tag but you 
can add one thatll look like username />
<label for="password> Password:</label><br>
<input type = "password" />
<input type ="submit" /> // we add this button so the user can submit the form
</form>
this would be like if you wanted someone to enter registration information for your site
</form>
there are 2 http methods to submit form data GET & POST
GET = retrives information from the server
POST = sends data to the server
when a user submits a form one of these methods is used
You are building an e-commerce site for a client. What kind of input types could you use? 
Answers: Number, Text, Radio, Password, Email, Checkbox, Textarea 
Wrong :Username bc it is not an input type


Introduction to DOM
HTML page -> DOM -> HTML page
this if for javascript interactivity
DOM = Document Object Model

The DOM allows you to update all HTML elements on a web page. (TRUE)


When you create a CSS rule, the part inside the curly brackets is called the: Declaration block (correct)

When designing a webpage you are presented an image with content width of 100px, 10px padding on both left and right sides, a 10px border on both left and right sides and a 10px margin on both left and right side. What is the border box width? 
answer: 140px

when coding in HTML you need to learn to utilize block level elements
these include 
<div> </div>
<form> </form>
<h1> </h1>
<h2> </h2>
<h3> </h3>

block vs inline
<div> is used to divide elements into sections </div> 

do inline elements appear on a new line? (false)

As a developer, deploying your application to a web server, you will use a bundling tool to:
Combine all your dependencies into a single file. (correct)
There are media queries that are a part of the CSS version 3 specification. What do they allow developers to query in order to conditionally apply CSS rules? Choose all that apply.  
Display Brightness (WRONG)

Aspect Ratio
Correct
That’s correct! The media queries that are a part of the CSS version 3 specification that allows developers to query display size, orientation and aspect ratio.  

Display Size
Correct
That’s correct! The media queries that are a part of the CSS version 3 specification that allows developers to query display size, orientation and aspect ratio.  

Orientation
Correct
That’s correct! The media queries that are a part of the CSS version 3 specification that allows developers to query display size, orientation and aspect ratio.  

Fixed grid as preset fixed margins
Fluid grid has a flexible content pick, where columns grow or shrink to adapt to available space
Hybrid grid that have fluid or fixed grid

when creating a bootstrap site we need a container element
it looks like 
<div class="container"> and it goes in the body tags <body>

bootstrap screen css rules
breakpoint          class infix         dimensions
extra small                                 <576px>
small                   sm                  >576px
medium                  md                  >768px
large                   lg                  >992px
extra large             xl                  >1200pxl
extra extra large       xxl                 >1400pxl

modifiers in bootstrap: 
primary, secondary, success, info, warning, danger, light, dark

As a web developer, you will use a modifier to indicate the breakpoint in Bootstrap CSS rules?
"No"
Correct!
That's right! Bootstrap modifiers add a CSS class to change the visual style of components. You will use an infix to indicate the breakpoint in Bootstrap CSS rules.  

Bootstrap's Grid System is structured with 3 types of elements. Select the correct types from the following options:

Containers
Correct
That’s correct! The Bootstrap's Grid system always contains container rows and columns.  

Rows
Correct
Correct! The Bootstrap's Grid system always contains container rows and columns.  

Columns
Correct
Correct! The Bootstrap's Grid system always contains container rows and columns.  

If I want to notify clients that Little Lemon has added a new burger to their menu. To do this I will use a Bootstrap Component. Which CSS classes can I use?
alert-info
alert
Correct
That is correct!  The alert CSS class will style an element as an alert component.


In website design, dynamic content is usually generated from where?
The application server

Cache: a saved copy of dynamic content, readily available on request
cache works in connection with the web server

