# DrawingTest
#Description
A Simple console version of a drawing program. 
The functionality of the program is quite limited but this might change in the future. 
The program works as follows: 
1. create a new canvas. 
2. start drawing on the canvas by issuing various commands. 
3. quit. 

The program supports the following commands:

1. C w h - Create a new canvas of width w and height h.
2. L x1 y1 x2 y2 - Create a new line from (x1,y1) to (x2,y2). Currently only horizontal or vertical lines are supported.
Horizontal and vertical lines will be drawn using the 'x' character.
3. R x1 y1 x2 y2 - Create a new rectangle, whose upper left corner is (x1,y1) and lower right corner is (x2,y2).
Horizontal and vertical lines will be drawn using the 'x' character.
4.B x y c - Fill the entire area connected to (x,y) with colour 'c'. This behaviour is same as that of the "bucket fill" in paint programs.
5. Q - Quit the program.