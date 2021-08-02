# leanneh11.github.io

Name:  
MIT xPro Course

Description:  
This project contains my library of JavaScript code for a course I'm taking at MIT xPro called Web Development with JavaScript.

Installation:  
No installation is required. You can download the repository and drag the index.html file onto your browser. 

Support:   
You can reach me @leannehardesty on Twitter or LinkedIn. 

License information:    
The project is released under the MIT license. The original project is part of an assignment for the MIT xPRO Web Development with JavaScript course.


Here are some early assignments from the course:

------------------------------------------------
Name: The name of the project. This name should be a descriptive, specific name for your project and what it does.  
Description: A description of the project to let people know what the project is for. A list of features could also be added here as a sub-section. 
Installation: If needed, you could include steps to help people get started with your project.
Usage: You can include examples of how to use your project in this section and highlight the expected outcomes. 
Support: You can tell people where to go for help regarding your project (example: email, Twitter, etc.). 
Roadmap: This section could include any future fixes or improvements you might be planning for your project. 
License information: For open source projects, you can describe how they’re licensed.  
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
