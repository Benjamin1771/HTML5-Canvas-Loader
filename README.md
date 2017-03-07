# HTML5-Canvas-Loader

<h3> Creating loaders on the HTML Canvas without a framework </h3>

<p>The purpose of this assignment was to understand working without a framework on the html canvas. Frameworks make coding faster and simpler, but undertanding how much simpler the framework makes things is worth noting. </p>

<p>Below is a simple loader created on the canvas without a framework. It is very basic, and the .html file can be found in this repository.</p>

<img width="419" alt="simpleloader" src="https://cloud.githubusercontent.com/assets/24251065/23678160/f5ccfe02-0350-11e7-8191-10dc90c50bdb.png">



This loader animated accross the screen from left to right and repeats. To do this we need to introduce the canvas element in our code. The canvas element has an ID for css properties, and a height and width value determining its size.  

<img width="652" alt="canvas" src="https://cloud.githubusercontent.com/assets/24251065/23676666/69289fec-034b-11e7-8094-5edf77553d20.png">


Var Canvas

<img width="571" alt="canvasvar" src="https://cloud.githubusercontent.com/assets/24251065/23676760/bdacc908-034b-11e7-9287-8d465d208629.png">


Along with a couple of variables we will call later: 

<img width="246" alt="vars" src="https://cloud.githubusercontent.com/assets/24251065/23677338/bd2f6cf4-034d-11e7-8870-e0f1423ddc14.png">


Draw Circle, pass in perameters: 

<img width="562" alt="circle" src="https://cloud.githubusercontent.com/assets/24251065/23677530/80187e22-034e-11e7-9dd7-109fbf3a7daa.png">

Create rectangle with low opacity

<img width="545" alt="rect" src="https://cloud.githubusercontent.com/assets/24251065/23677941/1d1a8b2e-0350-11e7-8c0a-4d71305b9525.png">

Call setInterval function to loop through creating contents - this creates a tail for the circle, and a rectangle that appears over top the last created circle. 


<img width="324" alt="setinterval" src="https://cloud.githubusercontent.com/assets/24251065/23678077/9c9588d6-0350-11e7-9c71-afa8e0fec5f6.png">

<img width="144" alt="call30" src="https://cloud.githubusercontent.com/assets/24251065/23678080/9dea6efe-0350-11e7-9059-df6f26e532ee.png">
