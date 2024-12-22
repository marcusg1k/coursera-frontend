# Lab Instructions: Creating an HTML Document

In this exercise you will you will practice creating a simple HTML document.<br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
 <br><br> 
 
<br>

## Task 1: Create a valid HTML document that displays a piece of text.

Objectives
- Add the **DOCTYPE**.
- Add the HTML, head and body elements.
- Add the title element.
- Add the text to the body element.

Follow the Step by Step instructions below:

1. Open the `index.html` file.

2. Type `<!DOCTYPE html>` on the first line.

3. Create your `html` element on the next line. This will be the root element of the document.

4. Add the `head` element inside the `html` element. The head element contains data about the HTML document that does not display in the web browser.  

5. Add the `title` element inside the `head` element.

6. Add the text `My First HTML Document` inside the `title` element. The content of the `title` element is the text that will be displayed in the web browser tab.   

7. Close the `head` tag and add the `body` element. The ``body element contains all displayable content of the webpage.

8. Add the text `I successfully created my first document` inside the `body` element. This displays on the webpage. 


<br>



## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

### Tips

* Ensure that the **DOCTYPE** is declared at the beginning of the file.
* Remember that HTML documents have a specific structure.
* Review the lessons *What is HTML?* and *HTML Documents.*









ASSIGNMENT 2: 
# Lab Instructions: Create and style a webpage

In this exercise you will you will practice building your webpage using HTML and CSS.<br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
 <br><br> 
 
<br>

## Task 1: Create the HTML file. 

Objectives
- Add  photo.jpg to the webpage.
- Add your name as a heading to the webpage.
- Add an unordered list of your five favorite music artists.
- Add an ordered list of your top five favorite films.
- Add a hyperlink to your Facebook profile, or, meta.com.

Follow the Step by Step instructions below:

1. Open the `index.html` file and set up the following basic HTML document structure:
    ```HTML
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
    </body>
    </html>
    ```

2. Set the title of the HTML document to your name:
    ```HTML
    <!DOCTYPE html>
    <html>
    <head>
        <title>your name</title>
    </head>
    <body>
    </body>
    </html>
    ```

3. Link to `styles.css` in the `head` element.

4. Add five divider elements to the `body` element.

5. Add a heading 1 to the first divider element that displays your name.

6. Add `photo.jpg` using an image element in the second divider element..  

7. Add an ID attribute with the value `photo` on the image element.

8. Add a heading 2 for `Favorite Music Artists` in the third divider element. In the same divider add an unordered list with your top 5 favorite artists.

9. Add a heading 2 for `Favorite Films` in the fourth divider element. In the same divider add an ordered list with your top 5 favorite films.

10. Add a hyperlink to your Facebook profile page in the last divider element. Alternatively, add a hyperlink to `https://www.meta.com/`. As a last step, add `My Profile` to the descriptive text of the `<a>` tag. 


<br>

## Task 2: Style the webpage using CSS.

Objectives
- Style the webpage using CSS.

Follow the Step by Step instructions below:

1. Open the `styles.css ` file.

2. Add a CSS rule for your image that sets the `border` property to `2` pixels wide with a `solid blue` color.

3. Add a CSS rule for heading 1 containing your name and set its color to `blue`.

4. Add a CSS rule for all `<h2>` headings and set their color to `grey`.

5. Add a CSS rule that applies a `margin` of `4` pixels to the divider elements.


<br>



## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

### Tips

* Make sure that HTML tags are closed properly.
* Use a different heading type for your name.
* Remember the box model.
* Review the lessons *Creating a HTML document*, *Adding Images*, *Selecting and Styling*, and *Different types of selectors*.





Assignment: Styling a css page

# Lab Instructions: Styling a page

In this exercise you will you will practice applying CSS rules to HTML elements.<br><br>

> ### **Tips: Before you Begin**
> #### **To view your code and instructions side-by-side**, select the following in your VSCode toolbar:
> - View -> Editor Layout -> Two Columns
> - To view this file in Preview mode, right click on this README.md file and `Open Preview`
> - Select your code file in the code tree, which will open it up in a new VSCode tab.
> - Drag your assessment code files over to the second column. 
> - Great work! You can now see instructions and code at the same time. 
 <br><br> 
 
<br>

## Task 1: Style an HTML page using CSS..

Objectives
- Define a CSS rule using an element selector.
- Define a CSS rule using an id selector.
- Define a CSS rule using a class selector.
- Define a CSS rule using a descendant selector.

Follow the Step by Step instructions below:

1. Open the `styles.css` file.

2. Add a CSS rule for the `body` element that sets the background color to `#E0E0E2`.

3. Add a CSS rule for the `h1` element that sets the text color to: `#721817`.

4. Add a CSS rule for the `h2` element that sets the text color to: `#721817`.  

5. Add a CSS rule for the `center-text` CSS class that aligns the text to `center`.

6. Add a CSS rule for the HTML element with the id `logo`. Set its left and right margins to `auto` and changes its display to a `block` element.  

7. Add a CSS rule for all `span` elements that are children of `h2` elements that sets the text color to `#FA9F42` and its font size to `0.75em`.

8. Add a CSS rule for the HTML element with the id `copyright`. Set its top padding to `12` pixels and its font size to `0.75em`. 


<br>



## Final Step: Let's submit your code!
Nice work! To complete this assessment:
- Save your file through File -> Save 
- Select "Submit Assignment" in your Lab toolbar. 

Your code will be autograded and return feedback shortly on the "Grades" tab.  
You can also see your score in your Programming Assignment "My Submission" tab.
<br> <br> 

### Tips

* If you get stuck, apply the CSS rules one at a time and verify their behaviour is what you expect.
* Review the lessons *Selecting and Styling*, *Text and color in CSS*, *Different types of selectors*, and *Box Model Introducction*.