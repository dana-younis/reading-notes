# Chart.js, Canvas

* * Charts are far better for displaying data visually than tables. Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw the graph onto the page. It's a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.
Drawing a line chart
* * To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.
* * So add this to the body of our HTML page:
Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element
Inside the same script tags we need to create our data, in this instance it's an object that contains labels for the base of our chart and datasets to describe the values on the chart.
 Chart.js is a free and open source chart-based programming language. It's very flexible and easy to use. There are tons of options listed in the documentation.


 * * Let's start this tutorial by looking at the canvas HTML element itself.
Indeed, the canvas element has only two attributes, width and height.
These are both optional and can also be set using DOM properties.
When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high.
* * The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.The id attribute isn't specific to the canvas element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance).
* * The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts. For 2D graphics, such as those covered by this tutorial, you specify "2d" to get a CanvasRendering Context.Checking for supportThe fallback content is displayed in browsers which do not support canvas.
Scripts can also check for support programmatically by testing for the presence of the getContext() method.
Our code snippet from above becomes something like this:





* * Now that we have set up our canvas environment, we can get into the details of how to draw on the canvas.By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes.Working with paths is essential when drawing objects onto the canvas and we will see how that can be done.Before we can start drawing, we need to talk about the canvas grid or coordinate space.Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high.Draws a filled rectangle with parameters x, y, width, height. Draws a rectangular outline with parameters X, Y, Height. ClearRectangle makes the specified rectangular area fully transparent. Each of these three functions takes the same parameters on the canvas. width and height provide the rectangle's size.

* * ClearRect() erases a 60x60 pixel square from the center, and then strokeRect() is called to create a rectangular outline 50x50 pixels within the cleared square. The clearRect() function draws a large black square 100 pixels on each side. In upcoming pages we'll see two alternative methods for clear Rect() and we'll also see how to build a path. The first step to creating a path is to call the beginPath() function. Once the path has been created, you can stroke or fill the path to render it. The path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be created by building a path up from the bottom up to the top.
* * The moveTo() function is used to move a pen or pencil from one spot to the next. It doesn't actually draw anything but becomes part of the path list described above. To try this for yourself, you can use the code snippet below. Just paste it into the draw() function we saw earlie use to draw a smiley face.
Arcs are drawn using the arc() or arcTo() methods. The method takes six parameters: x and y are the coordinates of the center of the circle on which the arc should be drawn. The startAngle and endAngle parameters define the start and end points of the arc in the given direction. The two for loops are for looping through the rows and columns of arcs. Angles in the arc function are measured in radians, not degrees. To convert degrees to radians you can use the following JavaScript expression: (Math.PI/180degrees. The following example is a little more complex than the ones we've seen above. It draws 12 different arcs all with different angles and fills. The top half of the canvas requires a slightly larger canvas than the others on this page: 150 x 200 pixels.
* * use the fillStyle property to change the fill color of Path2D objects. We also use a utility function in this case roundedRect Using utility functions for bits of drawing you do often can be very helpful and reduce the amount of code you need.
* * If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle. By default, the stroke and fill color are set to black. For every shape you want in a different color, you will need to reassign the fillStyle or strokeStyle property.
* * The blue channel has a fixed value.By modifying the channels, you can generate all kinds of palettes.
A strokeStyle example

* * We use the arc() method to draw circles instead of squares.
If you consider a path from (3,1) to (3,5) with a line thickness of 1.0, you end up with the situation in the second image.
* * The actual area to be filled (dark blue) only extends halfway into the pixels on either side of the path.An approximation of this has to be rendered, which means that those pixels being only partially shaded, and results in the entire area (the light blue and dark blue) being filled in with a color only half as dark as the actual stroke color.


* * The lineCap property determines how the end points of every line are drawn.
There are three possible values for this property and those are: butt, round and square.
The lineJoin property determines how two connecting segments (of lines, arcs or curves) with non-zero lengths in a shape are joined together. There are three possible values for this property: round, bevel and miter. The lineJoin setting has no effect if the two connected segments have the same direction, because no joining area will be added in this case. The example below draws three different paths, demonstrating each of these three line join properties.


* * MiterLimit property determines how far the outside connection point can be placed from the inside connection point. A miter limit equal to 1.0 will strip all miters for sharp angles below about 11 degrees. The default miterlimit of 10.0 is valid but will disable all miter limits below 1.4142136 rounded up It is then equal to the cosecant of half the minimum inner angle of connecting segments below. The maximum miter length is the product of the line width measured in the current coordinate system. If you specify a miterLimit value below 4.2 in this demo, none of the visible corners will join with a mitter extension. With an intermediate value above 10, most corners should join with miter far away from the blue lines.


* * Shadows are only drawn for source-over compositing operations. Use negative values to cause the shadow to extend up or to the left, and positive values to make the shadow extend down. The shadowBlur property indicates the size of the blurring effect; this value doesn't correspond to a number of pixels and is not affected by the current transformation matrix.
* * Styling text.css can make the font property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas. These properties might be familiar to you, if you have worked with CSS.