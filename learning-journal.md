#Learning Journal 201

**Day 1**

  First day we learned about git and github. Commands like "git init", this
command actually starts git in the directory where we will create our
repository. Another very important command is "git add FILENAME". With this
command the files that we have in the repository can be tracked now by git.

  Another very important command is "commit -m "message"". With this command we
make sure we do not lose any of our work. It is recommended that we execute
this command every 15 minutes.

  We went over the main Unix commands. the CP command is used to copy a file
from one directory to another one. Other commands include rm, which is to erase
files and directories. To erase a directory using this command you have to add \
-rf to force the delete on the directory and all the files inside of it.

  We also learned hot to do branching in github.

**Day 2**
tags like <Header>, <footer>, <nav>, <aside>, <section>, <figure> and <div>. We
also learned about the structure of html.

  In the CSS part we learned hoe to link the CSS file to our HTML file. It is
much better to do it that way than to do a <style> tag. We also learned how to
style web pages using CSS.

**Day 3**

  In this day we covered the box model in CSS. The web page is actually
mad out of elements all made out of boxes. Even if we see an element as a
circle, this element is actually a box. How to manipulate the hight and
width. We also covered the border, margin and padding.

  In the javascript part we covered decision making. This can be done by
 conditionals. One of this conditionals is the If...else statements. Here is an
  example of the if, else statement.

if (x = 0) {
  y = 3 * 9
}
else [
  y = 5 * 20
]

  We also covered loops. Loops keep repeating the same instructions until a
certain condition is met. For the loop we use the for command. Here is an
example of a loop.

for (i = 0; i < x; i++) {
  x = x + 1
}


  In another loop we have instruction performing until a condition changes. In
this loop instead of using the keyword for we use the keyword while. Here is an
example of this loop.

while (i = 0; i < x; i++) {
  x = x + 1
}

**Day 4**

During this day we learned about functions is javascript and and introduction
to the CSS layout. We learned about parameters. Parameters are values that the
function needs to execute the instructions. SOme other functions need arguments.
Here is an example of a function.

function function1() {
X = 3 * s
}

  When you call this function so that the instructions inside of it will execute
you use the folloeing code.

function1 ();

  Inside the parenthesis we can add parameters so this values would be used buy
the instructions in the function.

**Day 5**

  Day 5 was spent covering CSS. We learned about how to use commands to position
the boxes in the web page. We covered relative positioning. An example of the
code used for relative positioning follows:

p.example {
    position: relative;
    top: 10px;
    left 100px;
}

  We also covered absolute positioning. In absolute positioning the box is
taken out of normal flow and no longer affects the position of other elements
on the page. Here is an example:

h1 {
  position: absolute;
  top: 0px;
  left: 500px;
  width: 250px;
}
p {
  width: 450px;
}

**Journal day 6**

We learned about objects, functions and methods.

Object group together s set of variables. Here is an example of how you add
variables (properties) to an object:

var = restaurant {
name: "El Res",
dishes: 3,
tables: 20,
dishType = ['tacos','hamburgers','hotdogs']
}

We also learned about built in objects. This built in objects contain
functionalities used by commonly by scripts.
Also we covered the methods. When a function is part of an object is called a
method.


Also DOM was covered. "Document Object Model"
When the browser loads a web page, it creates a model of that page, that is
the DOM. That summarizes day6.


**Journal day 7**
On day 7 we learned about box width, height, overflowBorder, margin, & padding.
Border width, style, & color. Centering content. Changing inline/block.
Visibility and additional border topics. All this is in CSS.

Following is an example of how to change the with.

.box {
    width: 100%;
}

this changes all that are in the class box to 100% with.

function myFunction() {
    var x = document.createElement("TABLE");
    x.setAttribute("id", "myTable");
    document.body.appendChild(x);

    var y = document.createElement("TR");
    y.setAttribute("id", "myTr");
    document.getElementById("myTable").appendChild(y);

    var z = document.createElement("TD");
    var t = document.createTextNode("cell");
    z.appendChild(t);
    document.getElementById("myTr").appendChild(z);
}
code source www.w3schools.com

We also learned about creating tables and structure. Here is a code example of
how to create a table.

**Journal day 8**

On this day we learned about forms, tables, lists and events.
Forms is a way the user inputs values. There are different types of forms. The
input types are text, password, submit, reset, radio, check box and button.
Here is an example of what the code would look when asking for a radio input
type:

<form>
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
</form>

Another important subject we covered are the events. An event is something the
user does or the browser does. Common events are:
onchange, onclick, onmouseover, onmouseout,onkeydown and onload.

**Journal day 9**

Today we learned about key positioning. CSS treats each HTML element as if it
is in its own box. The box can be in a block level or and inline box. Block
line elements start on a new line. Inline elements flow in between surrounding
text. CSS has the following ositioning schemes:

  Normal flow
  Relative positioning
  Absolute positioning
  Fixed positioning
  Floating elements

We also control screen sizes and resolutions.
We also learned about CSS frameworks. With CSS frameworks we can create common
tasks like the following:

  Layout grids
  styling forms
  crating printer friendly versions of pages.

**Journal day 10**

In day 10 we covered error handling and debugging.
Order of execution: The order in which statements are executed cannot complete
until until another statement or function as completed.

Functions in Javascript are said to have lexical scope, they are linked to the
object they were defined within. There are object objects like the following:

  Syntax error
  Reference error
  EvalError
  URIError
  TypeError
  RangeError
  Error
  NaN

There are two ways to threat errors:

1. Debug the script to fix errors.
2. Handle errors gracefully.

  The debugger keyword creates a breakpoint in the code. The common errors
we can find are missed extra characters and data type issues.

**Learning journal day 11**

Today we learned how to add video to our pages. We also commented that flash
is not used that much. Apple stopped using it. The best way to add video
into our web pages is by using the <video> tag. Here is a code example of how
to do this:

<video src = "video/jumping.mp4" poster = "images/jumping.jpg" width = "400"
height = "300" loop>
<p>Video of someone jumping</p>
</video>
d
In the css part we learned how to align the images, how and how to center them,
 here is an example of how to center an image in css:

  img.allign-center {
    display: block;
    margin: 0px auto:
  }
  img.medium {
    width: 250px;
    height 250px;
  }
We also covered about back-ground images. This way you can place an image
behind any html element.

**Journal Day 12**

  During day 12 we learned how to put the data we have into a chart. We learned
that these charts can be styled in many different ways. To create a canvas we
need to put information in the HTML and the js. We use a tag called <canvas> in
the HTML side, here is an example of this tag.

<canvas id="canvas" width="500" height="300"></canvas>

  We also learned where to find libraries to use with canvas, if we want to
use a library, we have to do the following tad, and put it in the head of our
HTML document.

 <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.5.0/Chart.min.js" charset="utf-8"></script>

**Journal day 13**

  Today we learned about storing data in the browser. Where we stored it is
called local storage.we do it with the following js.

  localStorage['ingredients'] = JSON.stringify(ingredientsArray);

  What this does is it stores an Array called ingredients in the local storage
by turning the data of this array into a string.

  Then when we want to retrieve the data from the local storage we use the
following js:

var existingData = JSON.parse(localStorage['ingredients']);

  This makes the string we had stored into a number or set of numbers.

**Journal day 14 **

  Today we learned about CSS transforms, transitions and animations. For the
transform property we 2 different settings: a 2-dimensional and a 3-dimensional.
Transform is a way that we can alter elements, here is an example of code that
we would use in css to use transform:

.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}

  With transitions and animations we can alter the appearance and behavior of
elements. Here is an example of this. During this example the box would change
the color it has in one second. It does it in one second over a linear fashion.

.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}

  Not all properties can be transitioned.

**Journal day 15**

  Today we had an introduction to jQuery. jQuery is basically a javascript
library that simplifies event handling, document traversing, etc. Here is the
basic syntax:

Basic syntax is: $(selector).action()

  A $ sign is to define or access jQuery.
