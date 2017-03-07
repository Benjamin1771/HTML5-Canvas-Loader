# HTML5-Canvas-Loader

<h3> Creating loaders on the HTML Canvas without a framework: </h3>

<p>The purpose of this assignment was to understand working without a framework on the html canvas. Frameworks make coding faster and simpler, but undertanding just how much simpler the framework makes things is worth noting. There are many popular frameworks available, one of the most common being createJS which has extensive documentation and support, and is one of the most widely used frameworks available.</p>

<p>Below is a simple loader created on the canvas without the use of a framework. It is very basic, and the .html file can be found in this repository.</p>

<img width="419" alt="simpleloader" src="https://cloud.githubusercontent.com/assets/24251065/23678160/f5ccfe02-0350-11e7-8191-10dc90c50bdb.png">


<p>This loader animates accross the screen from left to right and repeats. To do this we need to introduce the canvas element in our code. The canvas element has an ID for css properties, and a height and width value determining its size.</p>  

<img width="652" alt="canvas" src="https://cloud.githubusercontent.com/assets/24251065/23676666/69289fec-034b-11e7-8094-5edf77553d20.png">


<p>Create a variable for the Canvas. Also create a variable to show the canvas in its 2d context. </p> 

<img width="571" alt="canvasvar" src="https://cloud.githubusercontent.com/assets/24251065/23676760/bdacc908-034b-11e7-9287-8d465d208629.png">


<p>Also define a couple of variables for X and Y positions we will call later: </p>

<img width="246" alt="vars" src="https://cloud.githubusercontent.com/assets/24251065/23677338/bd2f6cf4-034d-11e7-8870-e0f1423ddc14.png">


<p>Draw Circle, pass in perameters. Without a framework, we use the following to style the object drawn and position.</p>

<img width="562" alt="circle" src="https://cloud.githubusercontent.com/assets/24251065/23677530/80187e22-034e-11e7-9dd7-109fbf3a7daa.png">

<p>Create rectangle to cover the canvas with a low opacity.</p>

<img width="545" alt="rect" src="https://cloud.githubusercontent.com/assets/24251065/23677941/1d1a8b2e-0350-11e7-8c0a-4d71305b9525.png">

<p>Call setInterval function to loop through creating contents - this creates a tail for the circle, and a rectangle that appears over top the last created circle. </p>


<img width="324" alt="setinterval" src="https://cloud.githubusercontent.com/assets/24251065/23678077/9c9588d6-0350-11e7-9c71-afa8e0fec5f6.png">

<img width="144" alt="call30" src="https://cloud.githubusercontent.com/assets/24251065/23678080/9dea6efe-0350-11e7-9059-df6f26e532ee.png">


This is a very simple, working version of a basic loader done on the canvas without a framework. I've attached this file, along with two additional files in the repository. 

<h1>The HTML Files in This Repository</h1>
<h3>The 3 Attached HTML Files</h3>
<p>There are 3 files attached in this repository.</p>

<p>Two of them are done on the canvas without a framework: the one I just went over:</p>

<img width="419" alt="simpleloader" src="https://cloud.githubusercontent.com/assets/24251065/23678160/f5ccfe02-0350-11e7-8191-10dc90c50bdb.png">

<p>There is also a more challenging one that requires some more advanced familiarity with the canvas and javascript language: </p> 

<img width="431" alt="canvasinter" src="https://cloud.githubusercontent.com/assets/24251065/23680585/c28c5e44-0359-11e7-8566-866131ccc5fe.png">

<p>As previously mentioned, these two loaders are done without a framework, on the canvas.</p>
<p>The other file is CSS based loading animation.</p>
<p>The CSS file is to show how a lot can be done within a framework, with little coding. The loading animation this file creates is a fairly common one used - you will likely recodnize it:</p> 

<img width="278" alt="cssloader" src="https://cloud.githubusercontent.com/assets/24251065/23680539/96c56d64-0359-11e7-94a2-5ad447812f96.png">

<p>Other CSS based loaders:</p>
https://www.pexels.com/blog/css-only-loaders/
