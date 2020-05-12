# Docs for the HTML `<canvas> `Element & Chart.js

## Creating Stunning Animated Charts with Chart.js

* Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw a graph onto the page. It makes using all kinds of bar charts, line charts, pie charts, and more, super easy.

### Setting Up

1. Download Chart.js
1. Copy the Chart.min.js out of the unzipped folder and into the directory you'll be working in.
 1. Then create a new HTML page and import the script.

 ### Drawing a Line Chart

1. Create a canvas elelment in our HTML in which Chart.js can draw our chart:
` <canvas id="buyers" width="600" height="400"></canvas>`

1. Write a script that will retrieve the context of the canvas. Add this to the foot of your body element.
```
<script> 
var buyers = document.getElementById('buyers').getContext('2d');
new Chart(buyers).Line(buyerData);
</script>
```
 1. Inside the same script tags we need to create our data, in this instance it's an object that contains labels for the base of our chart and datasets to describe the values on the chart. This is the buyerData and it goes immediatley above var buyers.
 ``` 
 var buyerData = {
   labels : ["January", "February", "March"],
   datasets: [
     {
       fillColor : rgb(),
       strokeColor: #,
       pointColor: #,
       pointStrokeColor: #,
       data : [203,156,99,251,305,246]
     }
   ]
 }
 ```

 ### Drawing a Pie Chart

1. Add canvas element like above.
1. Add context to instantiate the chart: use `Pie(pieData, pieOptions)` where you sued line.
1. add data
```
var pieData = [
  {
    value: 20,
    color:"#",
  },
  {
    value: 40,
    color "#",
  },
  {
    value: 10,
    color:"#"
  },
  {
    value : 30,
    color : "#"
  }
];
```
1. Immediatley after pieData add options:
```
var pieOptions = {
  segmentShowStorke :false,
  animateScale: true
}
```
## The `<canvas>` Element

* Canvas element has only two attrivutes, width and height.
* creates a fixed-size drawing surface that exposes one or more **rendering contexts**, which are used to create and manipulate the content shown. 

* Drawing Rectangles
  * `fillRect(x, y, width, height)`
    Draws a filled rectangle.
  * `strokeRect(x, y, width, height)`
    Draws a rectangular outline.
  * `clearRect(x, y, width, height)`
    Clears the specified rectangular area, making it fully transparent.

* Drawing paths (a list of points, connected by segments of lines that can be different shapes, curved or not, of different width and of a different color.)
  * `beginPath()`
    Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
  * `Path methods`
    Methods to set different paths for objects.
  * `closePath()`
    Adds a straight line to the path, going to the start of the current sub-path.
  * `stroke()`
    Draws the shape by stroking its outline.
  *  `fill()`
    Draws a solid shape by filling the path's content area.

* To draw straight lines use the `lineTo()` method. 
* To move the pen use the `moveTo(x,y)` function.

### Colors

* Two important properties to be used to add colors:
  1. `fillStyle = color`: sets the style used when filling shapes.
  1. `strokeStyle = color`: Sets the style for shapes' outlines
* To draw semi-transparent shapes use `globalAlpha = transparency Value`
* Line Styles:
  * `lineWidth = value`
    Sets the width of lines drawn in the future.
  * `lineCap = type`
    Sets the appearance of the ends of lines.
  * `lineJoin = type`
    Sets the appearance of the "corners" where lines meet.
  * `miterLimit = value`
    Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
  * `getLineDash()`
    Returns the current line dash pattern array containing an even number of non-negative numbers.
  * `setLineDash(segments)`
    Sets the current line dash pattern.
  * `lineDashOffset = value`
    Specifies where to start a dash array on a line.

### Drawing text

* Two methods to draw text with canvas:
  1. `fillText(text, x, y [, maxWidth])`
  Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
  1. `strokeText(text, x, y [, maxWidth])`
  Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
