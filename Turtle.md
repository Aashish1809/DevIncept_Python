
<p align="center">
   <img src="https://miro.medium.com/max/1200/1*PPIp7twJJUknfohZqtL8pQ.png" alt="Python Programming"
        width="500" height="150">
   <br />
   <b> PYTHON - TURTLE LIBRARY </b>
   <br />
   <b> This mark down file helps understand Turtle library in Python. </b>
   <br />
</p>

---

### 📋 Turtle Library in Python

<p align="justify">
   Turtle is a pre-installed Python library that enables users to create pictures and shapes by providing them with a virtual canvas. The onscreen pen that you use for drawing is called the turtle and this is what gives the library its name. In short, the Python turtle library helps new programmers get a feel for what programming with Python is like in a fun and interactive way. Turtle is mainly used to introduce children to the world of computers. It’s a straightforward yet versatile way to understand the concepts of Python. This makes it a great avenue for kids to take their first steps in Python programming. That being said, the Python turtle library is not restricted to little ones alone! It’s also proved extremely useful for adults who are trying their hands at Python, which makes it great for Python beginners.
</p>
</ br>

<b> Python Compatible Environment and Version for Turtle </b>
<p align="justify">
   Python Environment can be any of the applications among IDLE, Jupyter Notebooks. Python version has to be version-3 as Turtle is within the version-3 of Python. The good thing about turtle is that it’s a built-in library, so ther's no need to install any new packages. The library can be put into use with just one line of code. Before beginning with libraries in  Python, understanding what a library is, is very important. In the non-computer world, a library is a place where different types of books are stored. These books can be accessed at any time, take whatever information you need from them, and return them to the same place.
In the computer world, a library works similarly. By definition, a library is a set of important functions and methods that you can access to make programming easier. The Python turtle library contains all the methods and functions that one need to create own set of images. To access a Python library, just import it into the Python environment, like this,
</p>

```
>>> import turtle
```
</br>

<b>Turtle Specific Methods</b>
<table class="table table-bordered">
<tr>
<th style="text-align:center;">Method</th>
<th style="text-align:center;">Parameters</th>
<th style="text-align:center;">Description</th>
</tr>
<tr>
<td>Turtle()</td>
<td>None</td>
<td>It creates and returns a new turtle object</td>
</tr>
<tr>
<td>forward()</td>
<td>amount</td>
<td>It moves the turtle forward by the specified amount</td>
</tr>
<tr>
<td>backward()</td>
<td>amount</td>
<td>It moves the turtle backward by the specified amount</td>
</tr>
<tr>
<td>right()</td>
<td>angle</td>
<td>It turns the turtle clockwise</td>
</tr>
<tr>
<td>left()</td>
<td>angle</td>
<td>It turns the turtle counter clockwise</td>
</tr>
<tr>
<td>penup()</td>
<td>None</td>
<td>It picks up the turtle’s Pen</td>
</tr>
<tr>
<td>pendown()</td>
<td>None</td>
<td>Puts down the turtle’s Pen</td>
</tr>
<tr>
<td>up()</td>
<td>None</td>
<td>Picks up the turtle’s Pen</td>
</tr>
<tr>
<td>down()</td>
<td>None</td>
<td>Puts down the turtle’s Pen</td>
</tr>
<tr>
<td>color()</td>
<td>Color name</td>
<td>Changes the color of the turtle’s pen</td>
</tr>
<tr>
<td>fillcolor()</td>
<td>Color name</td>
<td>Changes the color of the turtle will use to fill a polygon</td>
</tr>
<tr>
<td>heading()</td>
<td>None</td>
<td>It returns the current heading</td>
</tr>
<tr>
<td>position()</td>
<td>None</td>
<td>It returns the current position</td>
</tr>
<tr>
<td>goto()</td>
<td>x, y</td>
<td>It moves the turtle to position x,y</td>
</tr>
<tr>
<td>begin_fill()</td>
<td>None</td>
<td>Remember the starting point for a filled polygon</td>
</tr>
<tr>
<td>end_fill()</td>
<td>None</td>
<td>It closes the polygon and fills with the current fill color</td>
</tr>
<tr>
<td>dot()</td>
<td>None</td>
<td>Leaves the dot at the current position</td>
</tr>
<tr>
<td>stamp()</td>
<td>None</td>
<td>Leaves an impression of a turtle shape at the current location</td>
</tr>
<tr>
<td>shape()</td>
<td>shapename</td>
<td>Should be ‘arrow’, ‘classic’, ‘turtle’ or ‘circle’</td>
</tr>
</table>
</br>

<b> Steps for executing Turtle Program in Python </b>
<p align="justify">
   
   - Import the Turtle module
   - Creating a seperate window
   - Creating a Turtle to control the flow
   - Graphic creation using the Turtle methods listed prior
</p>
</br>

<b> Program to demonstrate the Turtle library </b>
</br>
<p align="justify">
   A turtle screen has to be opened first, and a variable has to be initialized for it in the following way. It makes up a window called the screen, where all of the ouptut for the code can be viewed. The litte black triangular shape in the middle of the screen as shown in the figure  is called the turtle. 
</p>

```
>>> dev = turtle.getscreen()
```

<p align="center">
   <img src="https://files.realpython.com/media/Screenshot_2019-12-10_at_7.40.34_AM.86e4071c3bb4.png" alt="Turtle Intro"
        width="400" height="300">
</p>
</br>

<p align="justify">
   Next, it is necessary to initialize the variable, which can then be used throughout the program to refer to the turtle. Just like for the screen, this also has to be given a name.
The screen acts as a canvas, while the turtle acts like a pen. The turtle can be programmed to move around the screen. The turtle has certain changeable characteristics, like size, color, and speed. It always points in a specific direction, and will move in that direction unless you tell it otherwise When it is up, it means that no line will be drawn when it moves, and  when it is down, it means that a line will be drawn when it moves. The initialization can be done as follows,
</p>

```
>>> t = turtle.Turtle()
```

<p align="justify">
   There are four directions that a turtle can move in, i.e., forward, backward, left and right. The turtle moves .forward() or .backward() in the direction that it is facing. The direction can be changed by turning it .left() or .right() by a certain degree. The code for movement and direction can be as simple as,
</p>

```
>>> t.right(90) //can also use .rt()
>>> t.forward(100) //can also use .fd()
>>> t.left(90) //can also use .lt()
>>> t.backward(100) //can also use.bk()
```
<p align="center">
   <img src="![](https://files.realpython.com/media/Update_-_Moving_Turtle_VIDEO_GIF.61623cf40fed.gif)" alt="Turtle Intro"
        width="400" height="300">
</p>



