# HOW TO EASILY CREATE STUNNING ANIMATED CHARTS? 
Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
+ **Setting up**  
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script
+ **Drawing a line chart**  
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page
+ **Drawing a pie chart**  
Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element
+ **Drawing a bar chart**  
Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element  
# Installing Chart.js
You can get the latest version of Chart.js from npm , the GitHub releases , or use a Chart.js CDN . Detailed installation instructions can be found on the installation page.
# what is The \<canvas> element
+ At first sight a \<canvas> looks like the \<img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the \<canvas> element has only two attributes, width and height. 
+ hese are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high
+ The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
# How to Drawe shapes with canvas?
+ **Using The grid**  
Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. 
+ **Drawing rectangles**  
Unlike SVG, \<canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.
+ **Drawing paths**  
 To make shapes using paths, we take some extra steps:  

1. First, you create the path.
2. Then you use drawing commands to draw into the path.
3. Once the path has been created, you can stroke or fill the path to render it.
# How Add Colors to shapes
If we want to apply colors to a shape, there are two important properties we can use: **fillStyle** and **strokeStyle**.

+ fillStyle = color  
Sets the style used when filling shapes.
+ strokeStyle = color  
Sets the style for shapes' outlines.

