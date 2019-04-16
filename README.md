# Color-Detection-Rpi-
The aim of the project was to use a Rpi and a camera module to detect particularly blue color in the environment. 


Colors on a computer are represented in what is called a color-space.
Color-space is also known as color models, which describes the range of colors as tuples of numbers. 
We won’t go over every color-space but we will focus on two main ones, BGR (Blue, Green, Red) and HSV (Hue, Saturation, Value).
In a BGR color-space, there are three parameters Blue, Green and Red. 
Each of these values typically goes from 0-255. For example, if we were to show a pure green pixel on-screen, then the B value would be 0, the G value would be 255, and the R value would be 0. 
This makes sense as there are no blue or red in a pure green pixel. Also the order you put these number in makes a difference. 
B is always first, then G, then R.
However, in HSV color space, the three parameters are Hue, Saturation, and Value. 
In simplest term Hue is the color, Saturation is how intense the color is and Value is the brightness of the color.

