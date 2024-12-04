# happy-birthday-wish-
import turtle

# Create a turtle object
my_turtle = turtle.Turtle()

# Set the turtle's speed to fast
my_turtle.speed(10)

#set baground colour
turtle.Screen().bgcolor("yellow")

# Set the turtle's pen color to blue
my_turtle.pencolor("blue")

# Move the turtle to the starting position
my_turtle.penup()
my_turtle.goto(-150, 2)
my_turtle.pendown()


# Write the word "Happy"
my_turtle.write("Happy Birthday", font=("Itallic", 41, "bold"))


my_turtle.penup()
my_turtle.goto(+300, 0)
my_turtle.pendown()
my_turtle.pencolor("pink")


my_turtle.write("\n God bless you", font=("Arial", 36, "bold"))

# Hide the turtle when done
my_turtle.hideturtle()

# Keep the turtle window open
turtle.done()
