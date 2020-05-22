# Variables & Debugging Lab

### Objective: 
In this lab, you will learn how to assign *values* to **variables**, how to change the *values* of a **variable**, and how to *recognize* **errors** in code!




[![](https://gotvantage.com/wp-content/uploads/2017/09/abtest.gif)]()



> Before we start, make sure to create a new file (in **Repl.it**) and call it **"VariablesLab"**.  
> Make sure it's saved in the same folder you created earlier today - **"Day 2"**.

---

## Instructions:

### 1) Variables Switch: 
1. In the **python editor**, define **two variables** with the following code:  
```python
a = 5
b = 10
```

2. Type the following to try to switch `a` and `b` values:
```python
a = b
b = a
```
[![](https://lh3.googleusercontent.com/GPGDnk2B09wllDTMf5kxDmxqNaI-oyYYtVeCNRQI93bNaUXrkZYSJVlMN_gqKZgtfQy-9EGZ6Y4Nl_Z7Zb4TLsFnRi6Fkn82WIhQc_3HNV527AQ3o8-6sgQqJiGeDLFdIAbphqM)]()

3. What are the new values of `a` and `b`? 
    - Find out by printing the values!
    
4. What happened? why didn't it work?
    - When we set `a = b`, the value in `a` changed to `10`. So both variables `a` and `b` have the value of `10`. Then, when we set `b = a`, the value of `a` was `10` so the value `b` of **did not change**.

[![](https://lh6.googleusercontent.com/8_InDsh4L5c_np1x4e7zq5lA7YAzzQaV8AMrOL_aYsuKGssuODuCCur2KUHcgpA7AOIu7kaGl1pLN0p34KCqUi9mV5fPLYoBv9HYPhyrvsQKo3cm-pCHrs0yxC3_XaQPRSej0K0)]()

5. Come up with a solution that fixes this issue, and switches the `a` and `b` values correctly!


### 2) Strings : 
1. In the **python editor**, define **a variable** with the following code:  
```python
four = '4'
```

2. What happens when you type:
```python
print(four*3)
```
3. Why did this happen?
    - Discuss this with your partner!

4. Now, set a new variable called `five` and make it equal to the integer `4`, and copy this code to your **Repl.it**:
```python
five = 4
print(5)

print(five*3)
```

5. Talk with a partner, and discuss why is this code's **output** *not* equal to `15`? 
   

### 3) Debugging Practice: 
1. Our goal is to make the picture below, using **two turtles**.
![Image of Copy Cat outcome](https://lh4.googleusercontent.com/ykhbjCdVwh8eHFxlphI9prJbFpNiLn9luPZicTQwI7NBs9b7baNsj9sPBFdihEFmyZPqpqS6RDS7a84yrISyCCSNcnWA7_j_OtO26bLVqBhg7qnGCYOeJCdY19CAFIGhNcYt1E8)

2. Note that the **short lines** are `75 pixels` long, and the **long lines** are `150 pixels`. You can name your turtles however you'd like!

> Hint: What do color(), pensize(), and shape() do?

3. Call an Instructor/TA to check your completed task before moving on to the next part!

---
## Great job on completing your first Turtle Lab!
**Call an Instructor/TA to check your completed tasks**
 
If you have extra time, continue to the **Bonus Problems** *below*.  
If not, make sure your code is saved in **Repl.it**!


> [![](https://www.vivaxsolutions.com/images/turtle-11.gif)]()


---
### Bonus Problems:

1. Use Turtle to spell your name!

2. Spell your friend's name!

3. Remember this image from the lecture? 
[![](https://lh4.googleusercontent.com/GPfF_OuZ4soVCwKDxBTBP5gX-m3-fKVxA31TcyGcSu_3M9fzFFLoGmoznudFVHM74VyVP6GT-Cb2gNXa9_V24hu2alIci1_TtamKgEQiZ8gm-tsa1vpgMHKRGyP657m8el4wQhACMw)]()
    - There are many different programming languages, **Python** is one of the most powerful ones!
    - This code (in the image) is written in **Javascript**; We haven't learned Javascript already, but try to understand the lines of code and using python, come up with the same image!
    - **NOTE:** No need to make the eye animations, but if you can, it's a huge bonus!

##### Great job on completing the bonus problems section!  
###### Make sure your code is saved in Repl.it
