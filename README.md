
draw-canvas :-

The program works as follows:
 1. # write Steps


|Command 		|Description|
If any commands and its description
Sample given below
|----|----|
|C w h          | Create a new canvas of width w and height h.|
|L x1 y1 x2 y2  | Draw a new line from (x1,y1) to (x2,y2). Currently, only|
|               | horizontal or vertical lines are supported. Horizontal and vertical lines|
|               | will be drawn using the 'x' character.|
|R x1 y1 x2 y2  | Draw a rectangle whose upper left corner is (x1,y1) and|
|               | lower right corner is (x2,y2). Horizontal and vertical lines will be drawn|
|               | using the 'x' character.|
|B x y c        | Fill the entire area connected to (x,y) with "colour" c. The|
|               | behaviour of this is the same as that of the "bucket fill" tool in paint|
|               | programs.|
|Q              | Quit|

__Example Ref__

Below is an example how program runs with for different user input commands. 
User input is prefixed with `enter command: text `
`
_How to Build_
To build the executable jar, run the below maven command from project root directory:
$ mvn clean package

It will create a jar draw-canvas.jar in <project root>/target directory.

__How to run the program__
To run the program:
$ java -jar draw-canvas.jar
