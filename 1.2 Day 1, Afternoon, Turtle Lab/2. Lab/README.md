## Lab Instructions:

### 1) Shape of the Turtle: 
1. Turtle has a `shape()` function that allows us to change the **shape** of the turtle from an *arrow* to something else. 
1. Type this code (you don’t need to include the comments):
```python
import turtle # python needs this to use all of the turtle functions
turtle.shape('square') # changes the shape to a square
turtle.mainloop() # make this the last line of your turtle code.
    
```
**What do you see?**

3. Now, change `'square'` to `'turtle'` in your code. You can do this by typing `turtle.shape('turtle')`.  Did anything change?

4. Now, type the following lines into your code. It should look like this:

```python
import turtle # python needs this to use all of the turtle functions
turtle.shape('turtle') # changes the shape to a turtle
greeny = turtle.Turtle() # creates a new turtle and saves it in greeny variable.
greeny.shape('square') # changes the shape of the 2nd turtle to a square
greeny.goto(100,100) # moves square to x=100 and y=100
```
- What happened?  Python made a copy of **turtle** and put it into the variable `greeny`.

5. Can you use the same turtle **functions** with the *new turtle*, `greeny`, as before? Draw a box with `greeny`.  
    - Remember: use `penup()`, `pendown()`, `and goto(x,y)`


- These are the **shapes** you can use:  
![Image of Turtle Shapes](https://github.com/meet-projects/Y1-Summer-Labs/blob/master/TurtleShapes.png)
---
### 2) Copy Cat: 
1. Our goal is to make the picture below, using **two turtles**.
![Image of Copy Cat outcome](https://lh4.googleusercontent.com/ykhbjCdVwh8eHFxlphI9prJbFpNiLn9luPZicTQwI7NBs9b7baNsj9sPBFdihEFmyZPqpqS6RDS7a84yrISyCCSNcnWA7_j_OtO26bLVqBhg7qnGCYOeJCdY19CAFIGhNcYt1E8)

2. Note that the **short lines** are `75 pixels` long, and the **long lines** are `150 pixels`. You can name your turtles however you'd like!

> Hint: What do color(), pensize(), and shape() do?

3. Call an Instructor/TA to check your completed task before moving on to the next part!

---

### 3) Spell MEET with Turtle: 
1. Our goal is to make the picture below by the end of this part.
![Image of MEET spelled with Turtle](https://lh6.googleusercontent.com/FNxs9tykGwRH9nRERleBnkIXmXCCdTGkNxju2yebYvrtArkfjmLCQaXsJ7bcj9z4bGSjmC_abCzcrSInYjrj3b8tVzZyuqk3ftgGpk8D1hc03ia7J16ojcxd1M2zcDyHa9yEGYE)

2. Copy the code below to **Repl.it**, if you feel like it's running too slow, feel free to use **idle3**, but make sure by the end of the lab to copy all of your code and save it into **Repl.it**!

```python
import turtle 

# Everything that comes after the # is a comment.
# It is a note to the person reading the code.
# The computer ignores it.
# Write your code below here...


# ...and end it before the next line.
turtle.mainloop() # tells the turtle to do all the turtle commands above it and paint it on the screen.
# It always has to be the last line of code!
```

3. We will need to tell the Turtle to move and draw lines to draw the word *MEET*. Commands we will need to use:
```python
turtle.penup() # Brings the pen up, so nothing will be drawn.
turtle.pendown() # The exact opposite of penup()
turtle.goto(x,y) # Go to the position x,y (but they should be in numbers instead)
```

4. Draw the M using the `pendown()`, `goto(x,y)`, and `penup()` commands, as shown below.  Every time you finish a line, press the **"Run"** on **Repl.it** or **"F5"** button in **idle3** to run the code you wrote so far!
```python
turtle.penup() #Pick up the pen so it doesn’t draw
turtle.goto(-200,-100) #Move the turtle to the position (-200, -100) on the screen
turtle.pendown() #Put the pen down to start drawing

#Draw the M:
turtle.goto(-200,100) 
turtle.goto(-150,-100) 
turtle.goto(-100,100)
turtle.goto(-100,-100) 
```
4. Get the idea? Great! Now complete the rest of the letters:
    - **E**
    - **E** (Feel free to do it normally, or in reverse, just like the original MEET logo!)
    - **T**


##### Great job on completing your first Turtle Lab!
##### Call an Instructor/TA to check your completed tasks
 

If you have extra time, continue to the **Bonus Problems** [here](https://github.com/meet-projects/Y1-Summer-Labs/tree/master/1.2%20Day%201%2C%20Afternoon%2C%20Turtle%20Lab/3.%20Bonus).  
If not, make sure your code is saved in **Repl.it**!


[![](https://www.vivaxsolutions.com/images/turtle-11.gif)]()



