# **Docs for the HTML canvas Element & Chart.js**

## **A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy .**
![](https://miro.medium.com/max/760/1*Vs0KD5q6PdT4_EaDK8b18A.jpeg)
## **At first sight a canvas looks like the img element, with the only clear difference being that it doesn’t have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn’t respect the ratio of the initial canvas, it will appear distorted.**


## **Drawing shapes with canvas :**
![](https://lenadesign.org/wp-content/uploads/2020/01/canvas.jpg)
## **through canvas you can:**

+ ## draw rectangles
+ ## draw paths
+ ## draw triangles
+ ## Move the pen
+ ## draw Lines
+ ## Arcs
+ ## draw Bezier and quadratic curves
+ ## Make combinations


## **Drawing text:**
![](https://i.ytimg.com/vi/4cFZ-CV88zM/maxresdefault.jpg)

## **To draw text on a canvas, the most important property and methods are:**
+ ## font - defines the font properties for the text.
+ ## fillText(text,x,y) - draws "filled" text on the canvas.
+ ## strokeText(text,x,y) - draws text on the canvas (no fill).

## **Canvas fill rules**

## When using fill (or clip and isPointInPath) you can optionally provide a fill rule algorithm by which to determine if a point is inside or outside a path and thus if it gets filled or not. This is useful when a path intersects itself or is nested.

## Two values are possible:

+ ## “nonzero”: The non-zero winding rule, which is the default rule.

+ ## “evenodd”: The even-odd winding rule.

## **The grid :** 
## Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high.
![](https://ae01.alicdn.com/kf/Hb6da072fb1a94d9587fd4787552ffb89r/5D-DIY-Blank-Grid-The-canvas-contains-Blank-canvas-glue-Cross-Stitch-Custom-Size-full-square.jpg_Q90.jpg_.webp)

## **The rendering context**
## The canvas element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, WebGL uses a 3D context based on OpenGL ES.The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The (canvas) element has a method called getContext(), used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context.The first line in the script retrieves the node in the DOM representing the (canvas) element by calling the document.getElementById() method. Once you have the element node, you can access the drawing context using its getContext() method.

## **Applying styles and colors :**
![](https://i1.wp.com/www.csscodelab.com/wp-content/uploads/2019/11/html-css-fatalistic-color-palette-ui-concept.png?fit=1024%2C715&ssl=1)
## we will explore the canvas options we have at our disposal to make our drawings a little more attractive. You will learn how to add different colors, line styles, gradients, patterns and shadows to your drawings.