# Self-Portrait-Assignment-For-Artistry-Design
This project is a graphical application developed in Python using the Turtle graphics library. It demonstrates mastery of basic program structure, naming conventions, and styling, while incorporating fundamental graphical logic to render complex shapes through procedural commands.
# -*- coding: utf-8 -*-
"""
Spyder Editor
This is a temporary script file.
"""
import turtle
# Set up the screen
screen = turtle.Screen()
screen.setup(width=1000, height=600)
screen.bgcolor("saddlebrown")
screen.title("Stop Sign")
# Create the turtle for drawing
quan = turtle.Turtle()
quan.speed(0)
#Draw octagon
quan.penup()
quan.goto(-50, -80)
quan.pendown()
quan.color("red")
quan.begin_fill()
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.end_fill()
#Draw white border
quan.penup()
quan.goto(-50, -80)
quan.pendown()
quan.width(5)
quan.color("white")
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
quan.forward(100)
quan.left(45)
#Write "STOP"
quan.penup()
quan.goto(-105, -10) 
quan.pendown()
quan.color("white")
quan.write("STOP", font=("Clearview", 60, "bold"))
#sign post
quan.penup()
quan.goto(0, -83) 
quan.pendown()
quan.color("silver")
quan.width(10) 
quan.setheading(270)
quan.forward(1000)
# Hide the turtle

quan.hideturtle()
