README.TXT

/* NetId(s): aam, jz674 Time spent: 6 hours, 30 minutes.
* Name(s):Anirudh Maddula, Jeffrey Zhang
*/

We added in 2 helper functions in DrawingCanvas.java to assist with our program.

Method drawLine will draw and repaint a line given 2 endpoints. This is called on in various places for both the Pencil and Line tool to draw a line using a Line2D.Double.

Method drawCircle will draw and repaint a line given 2 points, the centerpoint and the circumference. It uses these to calculate the radius. This is called on in various places for the Circle tool to draw a circle using an Ellipse2D.Double.

We have one issue with the Circle tool. When we draw a circle with the toolSize greater than the radius, it forms some odd shapes with dissproportionate strokes. However, it still follows the specifications so we left it as is.

Other than this, the rest of the code follows the given specs.