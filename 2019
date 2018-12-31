import turtle
from random import randint


def drawing_shapes():

	window = turtle.Screen()
	window.bgcolor("Black")

	christmas= turtle.Turtle()
	christmas2= turtle.Turtle()
	christmas.color("Green")
	christmas2.color("Green")
	christmas.shape("turtle")
	christmas2.shape("turtle")
	christmas.speed(4)
	christmas2.speed(4)
	counter1=80
	counter2=150
	y=-300
	christmas2.left(180)
	christmas.fillcolor("Green")
	christmas2.fillcolor("Green")

	#Tree Trunk
	trunk= turtle.Turtle()
	trunk.color("Brown")
	trunk.shape("turtle")
	trunk.up()
	trunk.setposition(-50,-300)
	trunk.down()
	trunk.right(90)
	trunk.fillcolor("Brown")		
	trunk.begin_fill()	
	for count in range(3):
			trunk.forward(100)
			trunk.left(90)	
	trunk.end_fill()	
	trunk.hideturtle()

	#209 ant the "1" is the tree trunk
	christmas2.pensize(10)
	christmas2.up()
	christmas2.setposition(-210,-310)
	christmas2.down()
	christmas2.left(180)
	for i in range(3):
		christmas2.forward(40)
		christmas2.right(90)
	christmas2.left(90)	
	for i in range(2):
		christmas2.left(90)
		christmas2.forward(40)

	christmas2.up()
	christmas2.setposition(-120,-310)
	christmas2.down()
	for i in range(4):
		christmas2.forward(40)
		if i%2==1:
			christmas2.forward(40)
		christmas2.right(90)

	christmas2.up()
	christmas2.setposition(80,-310)
	christmas2.down()	
	for i in range(4):
		christmas2.forward(40)
		christmas2.right(90)
	christmas2.forward(40)
	christmas2.right(90)
	christmas2.forward(80)
	christmas2.right(90)
	christmas2.forward(40)
	

	#Body of the tree
	for i in range(6):
		christmas.begin_fill()
		christmas.up()
		christmas.setposition(0,y)
		#christmas.down()
		if i==4:
			counter1=counter1
		christmas.forward(counter1)
		christmas.circle(190,40)


		christmas2.up()
		christmas2.setposition(0,y)
		#christmas2.down()
		christmas2.begin_fill()
		christmas2.forward(counter1)
		#a quarter circle:
		christmas2.circle(-190,40)

		christmas.left(90)
		christmas2.right(90)
		christmas.forward(80)
		christmas2.forward(80)
		christmas.left(50)
		christmas2.right(50)
		if i!=5:
			christmas.forward(counter2)
			christmas2.forward(counter2)
		christmas.right(180)
		christmas2.left(180)
		christmas.end_fill()
		christmas2.end_fill()

		#Tree Star
		if i==5:
				christmas.color("Yellow")
				christmas.fillcolor("Yellow")
				christmas.begin_fill()
				christmas.up()
				christmas.setposition(-35,y+130)
				christmas.down()
				for count in range(5):
					christmas.forward(70)
					christmas.right(144)
				christmas.end_fill()
				#christmas.up()
				#christmas.setposition(-2000,y)
				#christmas.down()
		y+=80
		counter1+=-30
		counter2+=-25	
	

	#Sana Saeeda 2019 in Arabic
	christmas.pensize(5)
	#Sana
	christmas.up()
	christmas.setposition(360,0)
	christmas.down()
	christmas.left(270)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(13)
	christmas.right(90)
	christmas.forward(20)
	christmas.left(180)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(13)
	christmas.right(90)
	christmas.forward(20)
	christmas.left(180)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(40)
	christmas.right(90)
	christmas.forward(20)
	christmas.backward(20)
	christmas.left(90)
	christmas.forward(40)
	christmas.right(90)
	christmas.forward(20)
	christmas.left(90)
	christmas.forward(16)
	christmas.left(90)
	christmas.forward(16)
	christmas.left(90)
	christmas.forward(16)

	christmas.up()
	christmas.setposition(286,20)
	christmas.down()
	for i in range(4):
		christmas.forward(4)
		christmas.left(90)

	christmas.up()
	christmas.setposition(250,20)
	christmas.down()	
	for i in range(4):
		christmas.forward(4)
		christmas.left(90)
	christmas.up()
	christmas.setposition(240,20)
	christmas.down()	
	for i in range(4):
		christmas.forward(4)
		christmas.left(90)

	#Saeeda
	christmas.up()
	christmas.setposition(-200,0)
	christmas.down()
	christmas.right(90)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(13)
	christmas.right(90)
	christmas.forward(20)
	christmas.left(180)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(13)
	christmas.right(90)
	christmas.forward(20)
	christmas.left(180)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(40)
	for _ in range(4):
		christmas.forward(20)
		christmas.right(90)
	christmas.forward(40)
	christmas.right(90)
	christmas.forward(20)
	christmas.left(180)
	christmas.forward(20)
	christmas.right(90)
	christmas.forward(40)
	christmas.right(80)
	christmas.forward(20)
	christmas.left(180)
	christmas.forward(20)
	christmas.right(100)
	christmas.forward(20)
	christmas.up()
	christmas.setposition(-390,0)
	christmas.down()
	christmas.circle(12)
	christmas.up()
	christmas.setposition(-305,-35)
	christmas.down()
	for _ in range(4):
		christmas.forward(4)
		christmas.right(90)

	christmas.up()
	christmas.setposition(-319,-35)
	christmas.down()
	for _ in range(4):
		christmas.forward(4)
		christmas.right(90)

	christmas.up()
	christmas.setposition(-380,10)
	christmas.down()
	for _ in range(4):
		christmas.forward(4)
		christmas.right(90)
	christmas.up()
	christmas.setposition(-394,10)
	christmas.down()
	for _ in range(4):
		christmas.forward(4)
		christmas.right(90)

	christmas.hideturtle()

	star= turtle.Turtle()
	star.color("Yellow")
	star.shape("arrow")
	star.speed(0)
	star.fillcolor("Yellow")

	#Sky Stars
	xCoordinate=0
	yCoordinate=0
	for i in range(200):
		xCoordinate=randint(-900,900)
		xCoordinate+=5
		yCoordinate=randint(240,380)
		yCoordinate+=5
		star.up()
		star.setposition(xCoordinate,yCoordinate)
		star.down()
		star.begin_fill()
		for count in range(5):
			star.forward(20)
			star.right(146)
		star.end_fill()
	

	window.exitonclick()
drawing_shapes()
