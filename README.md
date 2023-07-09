# py-galp
import turtle
import time

turtle.bgcolor("pink")
turtle.pensize(2)

def curve():
    for i in range(200):
        turtle.right(1)
        turtle.forward(1)

turtle.speed(0)
turtle.color("red", "red")

turtle.begin_fill()
turtle.left(140)
turtle.forward(111.65)
curve()

turtle.left(120)
curve()
turtle.forward(111.65)
turtle.end_fill()


turtle.penup()
turtle.goto(0, 200)
turtle.color("white")
turtle.write("SENİ SEVİYORUM", align="center", font=("Arial", 20, "bold"))
turtle.hideturtle()
turtle.exitonclick()  # Kullanıcının tıklamasını bekleyerek pencereyi kapat

turtle.bye()
