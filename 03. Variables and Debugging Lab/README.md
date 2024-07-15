# Variables & Debugging Lab

## Objective: 
In this lab, you will learn how to assign *values* to **variables**, how to change the *values* of a **variable**, and how to *recognize* **errors** in code!




[![](https://gotvantage.com/wp-content/uploads/2017/09/abtest.gif)]()



> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab!


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
    - Find out by printing the values using `print(a, b)`!
    
4. What happened? why didn't it work?
    - When we set `a = b`, the value in `a` changed to `10`. So both variables `a` and `b` have the value of `10`. Then, when we set `b = a`, the value of `a` was `10` so the value of `b` **did not change**.

[![](https://lh6.googleusercontent.com/8_InDsh4L5c_np1x4e7zq5lA7YAzzQaV8AMrOL_aYsuKGssuODuCCur2KUHcgpA7AOIu7kaGl1pLN0p34KCqUi9mV5fPLYoBv9HYPhyrvsQKo3cm-pCHrs0yxC3_XaQPRSej0K0)]()

5. Come up with a solution that fixes this issue, and switches the `a` and `b` values correctly!

---
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

print(five*3)
```

5. Talk with a partner, and discuss why the code's **output** is *not* equal to `15`? 
    - Now make a change to the variable `five` so the output *is* equal to `15`.
   
---
### 3) Debugging Practice: 
Below, you can find 3 mini programs that are written incorrectly.  
We will provide what each program's intention is, and your job is to copy-paste it to your **Repl.it** and fix it!  

1. Intention: Print out `"My name is student"`
```python
my_name = "student"
print("My name is ' + 'my_name")
```  

2. Intention: Print out `"I am 15 years old"`  
```python
my_age = 15
print('I am ' + my_age + ' years old')
```  

3. Intention: Print out the **total score**
```python
score = 4
count = "5"
total = score * count

print(total)
```

## Wrapping up:
Run the test.

- If it passes:
    - When you're done, make sure to submit the lab with the Submit button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps exactly to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!
 
  Let's submit the lab!
    - Once you've followed all the steps in a lab, go to the Master link.
    - Click on the submission link for this lab - https://forms.gle/dcce3aMvjT61x7pcA  
    - In the survey, copy your replit lab url, and copy it in the right place.
    - Submit the survey!

    if you have any questions, ask a classmate, TA or Instructor!


### Great job on completing the Lab!

Make sure the test passes, and that you submit the lab.

> [![](https://i.pinimg.com/originals/d4/20/4d/d4204d385da2a67b114644def349713d.gif)]()
