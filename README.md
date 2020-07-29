# Star_Red
illusions Star Pattern 



import turtle
window= turtle.Screen()
obj =turtle.Turtle()
obj.shape("triangle")
turtle.pencolor("RED")
def square ():
    turtle.forward (100)
    turtle.right(90)
for i in range (1,20):
    square()
    turtle.right(10)
    
window.exitonclick()
