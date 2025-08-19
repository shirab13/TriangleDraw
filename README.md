First thing I did was create a Form that accepts the user input,
in pure HTML, then I created the second page that will display the
user input.
I directed the form to send the parameters as query parameters to the
view page.
Then using JavaScript I read the query parameters and did some
basic math to scale the input values into the required 800x800px canvas.
Then I used the canvas API to draw the shapes on the canvas, first the
lines were drawn using the `moveTo` and `lineTo` methods,
then I used the `arc` method to draw the circles that are the edges of the triangle.
Finally, I used the `fill` method to fill the shapes with the specified
colors.
The arcs of each degree were drawn in the same way, using the arc method,
after performing some necessary calculations to determine the angle in degrees
and the radius of the arc, and its placement on the canvas.

1. "באיזו שיטה השתמשתם לציור המשולש? למה בחרתם בה?"
I used HTML canvas to draw the shapes, and I used JavaScript to handle the
user input and the drawing logic.
I went with basic HTML and JavaScript to keep it simple and working
on any device without the need for any additional libraries or frameworks.

2. "כיצד חישבתם את ערך הזווית?"
To calculate the angle value, I used the formula for the angles of a triangle,
we calculated the vectors of the triangle sides and used the dot product to find the angle,
then I converted the angle from radians to degrees.
and finally I used the `arc` method to draw the arcs on the canvas, and its labels

3. "מה היה מאתגר בתרגיל?"
Scaling the triangle was the most challenging part. the rest is mostly basic
math, on top of knowing the canvas element in HTML will provide the capabilities
to draw anything, and easily show it to anyone

4. "האם יש משהו שלא הצלחתם לפתור? איזה פערים היו לכם?"
I managed to complete the task, mostly I needed some math refreshments, and checking
some of the canvas documentation and examples to actually draw correctly on the HTML element.

5. "האם השתמשתם בעזרים חיצוניים? כולל בינה מלאכותית? אם כן במה הוא עזר?"
I used AI to help me think of how to scale user input to the canvas size
