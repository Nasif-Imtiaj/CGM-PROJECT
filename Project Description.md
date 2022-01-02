# CGM-PROJECT

A simple program to draw a solar system using computer graphics. In which the sun is at the center and other planets revolve around it.To draw the solar system, 
we start with a concentric ellipse because all the planet’s paths are elliptical.Then make a circle in the center of the ellipse and fill it with yellow paint to 
represent the sun.Then draw different circles, fill them with different colors and then choose the correct coordinate to place all of these in the ellipse’s path. 
After that change the positions of all the planets so that they appear to be moving on an ellipse.


Custom made functions used:
planetMotion(int xrad, int yrad,int midx, int midy,int x[70], int y[70]) : Function which is used to manipulates the position of planets on the orbit, it changes the planets in the
location in it's corresponding orbit.

Built in functions used:
setfillstyle(int pattern, int color) : Is used to set the current fill pattern and fill color.
floodfill(int x, int y, int border_color) : Is used to fill an enclosed area.
pieslice(int x, int y, int s_angle, int e_angle, int r) : pieslice() draws and fills a pie slice with center at (x, y) and given radius r. The slice travels from s_angle to e_angle which are starting and ending angles for the pie slice. The angles for pie-slice are given in degrees and are measured counterclockwise.
setcolor(int color) :  It is used to set the current drawing color to the new color.
outtextxy(int x, int y, char *string) : It is used to display the text or string at a specified point (x, y) on the screen.
rectangle(int left, int top, int right, int bottom) :  It is used to draw a rectangle.
getmaxx() : It returns the maximum X coordinate for current graphics mode and driver.
delay() :  Delay function is used to suspend execution of a program for a particular time.
closegraph() : The header file graphics.h contains closegraph() function which closes the graphics mode, deallocates all memory allocated by graphics system and restores the screen to the mode it was in before you called initgraph.
cleardevice(): The header file graphics.h contains cleardevice() function which clears the screen in graphics mode and sets the current position to (0,0). Clearing the screen consists of filling the screen with current background color.
initgraph(&gdriver, &gmode, "") : &gdriver is the address of gdriver variable, &gmode is the address of gmode and  "C:\\Turboc3\\BGI" is the directory path where BGI files are stored
Coordinates of left top and right bottom corner are required to draw the rectangle.
Left specifies the X-coordinate of top left corner, top specifies the Y-coordinate of top left corner, right specifies the X-coordinate of bottom right corner, bottom specifies the Y-coordinate of bottom right corner.
