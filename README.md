from turtle import *

tracer(0)
left(90)
k = 30
right(30)
for _ in range(30):
    right(30)
    forward(3 * k)
    right(30)
for x in range(-k, k):
    for y in range(-k, k):
        goto(x * k, y * k)
        dot(5)
done()

