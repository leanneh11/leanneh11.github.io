# leanneh11.github.io

This project contains my library of JavaScript code for a course I'm taking at MIT xPro called Web Development with JavaScript.

Here are some early assignments from the course:

------------------------------------------------

ball_2_OneDimensionalAnimation

I defined the ball in the div at the top

In my script I set up the code to move the ball across the page, using variables of time, velocity, and position.
A ball variable gets the ball attributes defined in the div.

I created the increasePosition function to advance the position of the ball across the page.
It increases the position of the ball by the velocity value and sets the ball in relation to the left axis.

I used the setInterval function to call the increasePosition function, which does so over based on the time variable which is set to 50 milliseconds. 

-----------------------------------
ball_4_TwoDimensionalAnimation

In this demonstration I've added another dimension to this animation, the Y axis

I've added velocity and position variables for the Y dimension as well as defined the edge
for the Y dimension which is the vertical axis

In this animation if the ball encounters the edge (min max) of either dimension (x or y) then
the ball reverses direction.

I've added a few balls to show some different features such as color, true velocity which is 
direction and speed along the different axes.
