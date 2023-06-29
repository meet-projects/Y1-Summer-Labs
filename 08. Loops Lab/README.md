# Loops Lab

## Objective: 
In this lab, you will learn how to start writing and using **loops**! And apply a lot of previous topics we learned from before with loops! (Some good **input/output** examples as well!!)

<img src="https://www.system-concepts.com/wp-content/uploads/2020/02/excited-minions-gif-360x163.gif">


> Before we start, navigate to the Repl.it assignment associated with this lab in the Teams tab!

## Instructions:

### 1) Lovely Grandma
<img src="https://s3.amazonaws.com/after-school-assets/deaf_grandma.jpg" width="400">

1. Today we're spending time with our grandma. *Define* a variable `text`, which gets input from the user (with `input()`) that allows us to speak.
    - If you shout something to grandma (type in all capitals), she can hear you (or at least she thinks so) and yells back, `NO, NOT SINCE 1938!`.
        - _Hint_: Look up the string method `isupper()` to help you check for capitalization!
    - Otherwise, whatever you say to grandma (whatever you type in), she should respond with `HUH?!  SPEAK UP, SONNY!`

2. Grandma decided she wants to keep talking to you and won't let you leave. Change your program so that it keeps running until you shout `"BYE"`.
    - _Hint_: You will probably want to use a `while` loop to keep the program running.

3. Grandma really doesn't want you to leave! When you shout BYE, she pretends not to hear you. 
    - Change your program so that you have to shout BYE three times before the program will end.
    
> At this point the first 4 tests should pass!

### 2) Searching out closet

Our closet is pretty messy. But we can write code that helps us find stuff in our closet using loops!

1. *Define* a new variable, `my_item`, using `input()`, which represents an item you are looking for.

2. Copy and paste the following list, which represents all the items in our closet:

```python
my_closet = [
 "running shoes",
 "dress shoes",
 "red shirt",
 "blue shirt",
 "brown pants",
 "bagel",
 "book",
]
```

3. Write code to go over each item in `my_closet` until it finds `my_item` you are searching for!
    - If the item is there, print `"I found my [item]"`.
    - If it's not there, your code should print `"I can't find my [item]"`.
        - Hint: You might need an extra variable to keep track of whether you've found `my_item`.

4. We can make our loop faster by breaking out of it as soon as we find our item!
    - Use `break` when finding `my_item` and stop the loop.
    
> At this point the first 6 tests should pass!

### 3) Dictionary Printer!

1. Copy and paste the following dictionary into the python editor:

```
data = {
"Name": "The Meal",
"Age":  "2 Weeks",
"Gender": "Soup",
"Size": "500ml",
}
```

1. Write code to print the keys and the values next to each other
    - It should look kind of like this (make sure you have at least 1 space between the key and the value on each line):
    ```python
    key_a    value_a
    key_b    value_b
    key_c    value_c
    ```
    - Hint: Use loops!
    
> At this point the first 7 tests should pass!

[![](https://i.gifer.com/7tB1.gif)]()

##### Great job!

### Wrapping up:
- Please show your work to an Instructor or TA!
- When you're done, make sure to submit the lab with the Submit button on the top right.

<!-- 

## Wrapping up:

Run the test.
- If it passes:
    - You can go on to try the bonus problems at the bottom of the lab. Be sure you don't change any of the code you already wrote!
    - When you're done, make sure to submit the lab with the `Submit` button on the top right.
- If it fails:
    - Review the lab to see if you missed any steps. You need to follow the steps _exactly_ to pass.
    - If you have questions, ask a classmate, or call over an Instructor or TA!
-->

## Bonus Problems:

1. Finish any previous labs that aren't finished
2. *Define* a variable called `partner_dict`.
    - `partner_dict` should be a dictionary of questions and answers about another MEET student.
    - Using `input()` and `while` loops, write code that prints out each question, and asks the reader for an answer. The code should keep running until the reader gets all of the answers right!
    - Example of how it should look like:
    ```python
    loai = {"When did loai graduate from meet?" : "Summer 2017", "How old is loai?" : 25}
        
    ### The terminal should look like:
    Question: When did loai graduate from meet?
    Answer: Summer 2016 # User input
    Wrong Answer!
    
    Question: When did loai graduate from meet?
    Answer: Summer 2017 # User input
    Correct Answer!
    
    Question: How old is loai?
    Answer: 25
    Correct Answer!
    You win!
    ```

