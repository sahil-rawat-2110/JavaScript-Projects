Project Folder Structure:

Let us explore the project folder structure. The project folder consists of 3 files. The HTML file creates the elements required to build the structure and layout of our project. Next, the CSS file styles the elements that we have created with CSS and Finally, Javascript adds functionality to our project.



----------------HTML----------------

We begin with the HTML code.
Here, we create a div with the class ‘clock’ and inside this, we create divs for displaying hours, minutes, and seconds. Apart from this we also use span tags to display ‘:’ between the divs.


----------------CSS----------------

Next, we style our game using CSS. 
We provide a background color to the body, while the time is displayed on a white background. Each element is aligned correctly and given a bit of a curve to make it look good.




----------------Javascript----------------

Finally, we add functionality using Javascript.

We create a ‘clock’ variable in which we call the function ‘time’, this function updates the time every second by getting the current time using the JavaScript Date() object. The hours, minutes, and seconds are then extracted from the date and formatted with leading zeros using the padStart() function. Next, formatted time is then displayed on the webpage as “hour”, “minute”, and “seconds”.