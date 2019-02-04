# ChooseYourOwnCivilWar
A Civil War Time Travel/ Adventure Game
Python 2.7.12 (v2.7.12:d33e0cf91556, Jun 27 2016, 15:19:22) [MSC v.1500 32 bit (Intel)] on win32
Type "copyright", "credits" or "license()" for more information.
>>> 
>>> #Space Invaders-Part 1
>>> #Set Up the Screen
>>> #Python 2.7.12
>>> 
>>> #import turtle
>>> import turtle
>>> import os
>>> 
>>> #Set up the screen
>>> wn = turtle.Scree()

Traceback (most recent call last):
  File "<pyshell#10>", line 1, in <module>
    wn = turtle.Scree()
AttributeError: 'module' object has no attribute 'Scree'
>>> wn = turtle.Screen ()
>>> wn.bgcolor("black")
>>> win.title ("Space Invaders")

Traceback (most recent call last):
  File "<pyshell#13>", line 1, in <module>
    win.title ("Space Invaders")
NameError: name 'win' is not defined
>>> wn.title ("Space Invaders")
>>> 
>>> #Draw border
>>> 
>>> border_pen = turtle.Turtle()
>>> border_pen.speed(0)
>>> border_pen.color("white")
>>> border_pen.penup()
>>> border_pen.penup()
>>> border_pen.penup(-300, -300)

Traceback (most recent call last):
  File "<pyshell#23>", line 1, in <module>
    border_pen.penup(-300, -300)
TypeError: penup() takes exactly 1 argument (3 given)
>>> border_pen.setposition(-300,-300)
>>> border_pen.pensize(3)
>>> for side in range (4):
	border_pen.fd(600)
	border_pen.lt(90)
border_pen.hideturtle()
SyntaxError: invalid syntax
>>> border_pen.setposition(-300,-300)
>>> border_pen.hideturtle()
>>> 
=============================== RESTART: Shell ===============================
>>> 
