# Datatypes Lab

## Objective: 
In this lab, you will learn about different data types, including `int`, `float`, `str`, and `bool`, and how to use `type()` to determine what data type a variable is, using **Python**. 
Moreover, you will learn how to assign *values* to **variables**, how to change the *values* of a **variable**.


<img src="https://miro.medium.com/max/1000/1*aNMBIivJppLy2fMRVUSgHA.gif" width=250>


> Before we start, navigate to Repl.it and `+ Create Repl` with the title `DataTypes & Vars - Your Name`


## Instructions:

## Part 1 - DataTypes:

1. Working with other classmates, take a look at the following python snippets:
    - `print(type(259+33))`
    - `print(type(259-33.0))`
    - `print(type(4))`
    - `print(type('4'))`
    - `print(type('four'))`
    - `print(type(5/2.0))`
    - `print(type(12 > 2*5))`
    - `print(type('color'*4))`
    
    > Remember, we use the `print` statement to see what's happening inside python.

1. Go over each line with your partner, and try to guess what each line returns as an **output**... discuss what your guesses are!

1. Now, after you're done guessing and discussing, let's put your theories to the test!
    - Write each line in the Repl.it **editor**, then press the `Run` button and understand why it is what it is.
    - If you don't understand something specific, try and ask your partner first :)
    - Remember! , if there are outputs that you do not understand, don’t hesitate to ask your TAs or Instructors!


   
##### Great job!

## Part 2 - Variables:

### 2.1) Variables Switch: 
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
### 2.2) Strings : 
> Remember! Data types are how the computer understands and interprets the data. So let’s start a conversation with our computer!

1. In the **python editor**, define **a variable** with your favorite number like the following code:  
```python
four = '4'
```

2. What happens when you type:
```python
print(four*3)
```
3. Why did this happen?
    - Discuss this with your partner!

4. Now, set a new variable called `num` and make it equal to the integer of your favorite number. Now, copy this code to your **Repl.it**:
```python
print(num*3)
```

5. Talk with a partner, and discuss the code's **output**. What is the **type** of your output?

##### Great job on finishing the lab!
 

## Wrapping up:
- Please reach out to your TAs or Instructors if you have any questions!
- When you're done, make sure to submit the lab with the Submit button on the top right.
- Try to do the bonus part, but please make sure not to change or delete your previous code.


<!--

Run the test.
- If it passes:
    - You can go on to try the bonus problems at the bottom of the lab. Be sure you don't change any of the code you already wrote!
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!
-->

[![](https://programmer.group/images/article/1a680890c223e534389f27858b5bf33a.jpg)]()

## Bonus Problems: 
1. Try typing all of the lines again without the word `type` at the beginning. First guess what the code will do, then run it. What do you get?

2. If you have extra time, please complete the debugging lab.
