# -
用python的turtle库画一个小猪佩奇

## [使用API](https://docs.python.org/2/library/turtle.html)
###	pu
penup,pu,up: 
Pull the pen up – no drawing when moving.

###	goto
goto,setpos:
Move turtle to an absolute position. If the pen is down, draw line. 
Do not change the turtle’s orientation.

###	pd
pendown,pu,down:
Pull the pen down – drawing when moving.

###	seth
setheading,seth(to_angle):
Set the orientation of the turtle to to_angle.

###	begin_fill
Call just before drawing a shape to be filled


###	lt
left(angle),lt(angle):
Turn turtle left by angle units. 

###	fd
forward(distance),fd(distance):
Move the turtle forward by the specified distance, 
in the direction the turtle is headed.

###	end_fill
Fill the shape drawn after the last call to begin_fill(). 
Equivalent to fill(False).

###	pencolor
pencolor(*args):
Return or set the pencolor.

###	circle
circle(radius, extent=None, steps=None)
Draw a circle with given radius. 

###	color
color(*args):
Return or set pencolor and fillcolor.

###	pensize
pensize(width=None):
Set the line thickness to width or return it.

###	hideturtle
hideturtle, ht:
Make the turtle invisible.

###	colormode
colormode(cmode=None):
Return the colormode or set it to 1.0 or 255.
Subsequently r, g, b values of color triples have to be in the range 0..cmode.

###	setup
setup(width=_CFG["width"], height=_CFG["height"], startx=_CFG["leftright"], starty=_CFG["topbottom"])
Set the size and position of the main window. 
Default values of arguments are stored in the configuration dictionary and can be changed via a turtle.cfg file.

###	speed
speed(speed=None):
Set the turtle’s speed to an integer value in the range 0..10. If no argument is given, 
return current speed.
