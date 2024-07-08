## Turtle Lab:
## Objective: 
In this lab, you will learn how to use **turtle** and explore its built-in **SUPERPOWERS!**

> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab!


### 1) Shape of the Turtle: 
1. Turtle has a `shape()` function that allows us to change the **shape** of the turtle from an *arrow* to something else. 
1. Type this code (you don’t need to include the comments):
```python
import turtle # python needs this to use all of the turtle functions
turtle.shape('square') # changes the shape to a square
turtle.mainloop() # make this the last line of your turtle code.
    
```
**What do you see?**

3. Now, change `'square'` to `'turtle'` in your code. Did anything change?
<!--
You can do this by typing `turtle.shape('turtle')`.
-->
4. Now, type the following lines into your code. It should look like this:
   - remember to put the lines between `import turtle` and `turtle.mainloop()`

<!--
import turtle # python needs this to use all of the turtle functions
turtle.shape('turtle') # changes the shape to a turtle
-->
```python
greeny = turtle.Turtle() # creates a new turtle and saves it in greeny variable.
greeny.shape('square') # changes the shape of the 2nd turtle to a square
greeny.goto(100,100) # moves square to x=100 and y=100
```
- What happened?  Python made a copy of **turtle** and put it into the variable `greeny`.

5. Can you use the same turtle **functions** with the *new turtle*, `greeny`, as before? Draw a box with `greeny`.  
    - Remember: use `penup()`, `pendown()`, `and goto(x,y)`


- These are the **shapes** you can use:
    - Note: if you have a black background color in this page, you may not be able to see the shapes. Please ask for help from a TA or Instructor.
      
![Image of Turtle Shapes](https://github.com/meet-projects/Y1-Summer-Labs/blob/master/TurtleShapes.png)
---
### 2) Copy Cat: 
1. Comment out your code for Part 1 so that Part 2 can run uninterrupted! To comment out code, you can place a hashtag symbol `#` in front of every line of code, or add ''' before and after your code: ''' YOUR CODE '''.

2. Our goal is to make the picture below, using **two turtles**.
![Image of Copy Cat outcome](https://lh4.googleusercontent.com/ykhbjCdVwh8eHFxlphI9prJbFpNiLn9luPZicTQwI7NBs9b7baNsj9sPBFdihEFmyZPqpqS6RDS7a84yrISyCCSNcnWA7_j_OtO26bLVqBhg7qnGCYOeJCdY19CAFIGhNcYt1E8)

3. Note that the **short lines** are `75 pixels` long, and the **long lines** are `150 pixels`. You can name your turtles however you'd like!

> Hint: What do color(), pensize(), tilt(), and shape() do?

4. Call an Instructor/TA to check your completed task before moving on to the next part!

---

## Great job on completing your Turtle Lab!

### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, click on the submission link: https://forms.gle/dsCehzjbqPteTTAj6
- Copy your replit lab url, and paste it in the right place in the survey.
- Submit the survey!
  
<!-- 

## Wrapping up:

- Get a TA/Instructor to check your lab. 

-->

---

### Bonus:
> Note: You don't have to start the bonuses by order.
### Part 1
### Spell MEET with Turtle: 
1. Our goal is to make the picture below by the end of this part.  <br>
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

### Part 2
Roni, Ayoub, and Uri have won a competition of Kahoot! To honour that, let's draw them a *Crown* in turtle and go present it to them.
![Image of Turtle Crown](https://us.123rf.com/450wm/aditii16/aditii162106/aditii16210600011/170518370-cute-king-turtle-mascot-character-holding-staff-cartoon-vector-icon-illustration-design-isolated-on-.jpg?ver=6)

### Part 3 
Add a gif picture as a shape to your turtle.
   > Hint: Use addshape()
 
