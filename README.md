# Pythonrobot

from ast import walk
import math
from os import write
from pkgutil import walk_packages
from shutil import move
import turtle 
from turtle import * 

wallie = turtle.Turtle()  
                          
wallie.pencolor('red')  
turtle.bgcolor('pink')   
turtle.speed(900) 


wallie.pensize(10)
wallie.pendown()
wallie.fd(100)  
wallie.lt(90)             
wallie.fd(50)
wallie.lt(90)
wallie.fd(40)


wallie.begin_fill()
wallie.circle(20) 
wallie.circle(15)
wallie.fd(60)
wallie.end_fill()



wallie.begin_fill()
wallie.circle(20)
wallie.circle(15)
wallie.end_fill()

wallie.pensize(10)
wallie.fd(30)
wallie.lt(90)
wallie.fd(50)
wallie.lt(90)
wallie.fd(60)




wallie.rt(90)  
               
          
wallie.fd(60)
wallie.lt(90)
wallie.fd(10)
wallie.lt(90)
wallie.fd(60)
wallie.backward(60) 



wallie.pensize(10)
wallie.rt(90) 
wallie.fd(30) 



wallie.rt(45)  
wallie.fd(40)
wallie.lt(90)
wallie.fd(5)
wallie.rt(90)
wallie.fd(20)
wallie.rt(90)
wallie.fd(20)
wallie.rt(90)
wallie.fd(20)
wallie.rt(90)
wallie.fd(5)
wallie.lt(90)
wallie.fd(30)



wallie.lt(135)  
wallie.fd(60)
wallie.rt(90)
wallie.fd(80)
wallie.rt(90)
wallie.fd(60)



wallie.lt(135)
wallie.fd(30)
wallie.lt(90)
wallie.fd(5)
wallie.rt(90)
wallie.fd(20)
wallie.rt(90)
wallie.fd(20)
wallie.rt(90)
wallie.fd(20)
wallie.rt(90)
wallie.fd(5)
wallie.lt(90)
wallie.fd(40)

wallie.rt(45)
wallie.fd(80)
wallie.rt(90)


wallie.up()  
wallie.fd(50)
wallie.down()  


wallie.fd(100)
wallie.lt(90)
wallie.fd(10)
wallie.rt(90)
wallie.fd(10)
wallie.rt(90)
wallie.fd(30)
wallie.rt(90)
wallie.fd(10)
wallie.rt(90)
wallie.fd(10)
wallie.lt(90)
wallie.fd(60)


wallie.lt(90)
wallie.fd(60)


wallie.lt(90)
wallie.fd(60)
wallie.lt(90)
wallie.fd(10)
wallie.rt(90)
wallie.fd(10)
wallie.rt(90)
wallie.fd(30)
wallie.rt(90)
wallie.fd(10)
wallie.rt(90)
wallie.fd(10)
wallie.lt(90)
wallie.fd(75)


wallie.up()
wallie.fd(200)
wallie.rt(90)
wallie.fd(40)
wallie.rt(90)


y = 9

while y < 50:
    wallie.rt(10)
    y += 4


wallie.fd(100)
wallie.write("Python robot", font=("italic", 90,))




wallie.penup()
wallie.lt(30)
goto(-200, 2)
pendown()

for i in range (3):
    for colours in ["pink","red"]:
        color(colours)
        pensize(6)
        circle(150)
        fd(560)


turtle.mainloop()  
