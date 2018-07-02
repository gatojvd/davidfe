# davidfe
import turtle
import random
a=turtle.Turtle()
b=turtle.Turtle()
c=turtle.Turtle()
colors = ["red","green","blue","orange","purple","pink","yellow"]
for i in range(100):
a.color(random.choice(colors))
b.color(random.choice(colors))
c.color(random.choice(colors))
a.forward(random.randint(1,100))
a.right(random.randint(1,100))
b.forward(random.randint(1,100))
b.left(random.randint(1,100))
c.forward(random.randint(1,100))
c.right(random.randint(1,100))
