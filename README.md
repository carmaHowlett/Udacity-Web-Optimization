## Project 4: Website Performance Optimization - Cameron's Pizzeria

### Part 1: index.html

#### Results

* Mobile : 93/100
* Desktop: 94/100

#### Changes Made

* Optimized Pizzeria Image (created smaller thumbnail)
* Minified JS and CSS
* Moved scripts to bottom of HTML document
* Inlined CSS in the <head>

### Part 2: pizza.html

#### Results

* Renders with a consistent frame-rate at 60fps when scrolling
* Time to resize pizzas is less than 5 ms using the pizza size slider

#### Changes Made

* In changePizzaSizes(): Removed unnecessary JS
* In updatePositions(): Reduced # of visible pizzas and utilized latestKnownScrollY

### Build Instructions

#### Python SimpleHTTPServer

>cd /path/to/your-project-folder
>python -m SimpleHTTPServer 8080

#### ngrok

>cd /path/to/your-project-folder
>./ngrok http 8080

#### Brunch Build

> brunch build --production  

### Resources Used

* <a href="https://www.html5rocks.com/en/tutorials/speed/animations/">Leaner, Meaner, Faster Animations with requestAnimationFrame</a>
* <a href="http://brunch.io/">Brunch Build</a>
* <a href="https://www.adobe.com/products/photoshop.html?sdid=KKQIN&mv=search&s_kwcid=AL!3085!3!155836184375!e!!g!!photo%20shop&ef_id=WF1nZAAABebVQG3H:20161229031240:s">Adobe Photoshop CC</a>
